# SageMaker training and evaluation notebook

Course notebook for an image-classification learning project by **Patrik Szepesi**, from [Deploy a Production Machine Learning model with AWS & React](https://www.udemy.com/course/build-and-deploy-a-ml-model-to-production-with-aws-and-react/).

## What the notebook contains

- Kaggle dataset acquisition and image exploration.
- Image resizing, train/test data preparation and S3 upload.
- SageMaker estimator and hyperparameter tuning setup.
- Endpoint deployment and inference examples.
- Confusion matrix and classification-report evaluation.

The notebook uses AWS resources and includes empty values that must be configured. It is an interactive course workflow, not an unattended training pipeline.

## Run requirements

Use a SageMaker-compatible notebook environment with an appropriately scoped execution role. Configure dataset access outside the committed notebook, choose an AWS region, bucket and permitted instance types, then review and execute cells in order.

The course notebook contains cells that write Kaggle configuration and perform file operations. Review paths and credentials before execution. Keep dataset archives, trained artifacts and notebook output containing credentials out of Git.

## Reproducibility and evaluation

For a reproducible run, record dataset version, split integrity, random seeds, environment versions, training job name, selected hyperparameters and model artifact URI. Report precision, recall, F1 and the confusion matrix alongside class distribution. Do not claim accuracy or production readiness without a recorded run and evaluation artifact.

## Platform operations

Training, tuning, notebook instances and inference endpoints incur AWS charges. Record the resources created during a run and remove endpoints, endpoint configurations and temporary resources when the demonstration is finished. Preserve model artifacts only under an explicit retention policy.

## Portfolio scope

The notebook remains attributed to its author. Improvements to documentation and workflow validation are recorded separately. Course completion and a fork do not by themselves establish production deployment or model-development ownership.

## References

[Original notebook](https://github.com/patrikszepesi/StartingNotebook/blob/main/StartingNotebook.ipynb) · [Backend](https://github.com/patrikszepesi/MedicAIBackEnd) · [Frontend](https://github.com/patrikszepesi/MedicAIFrontEnd)
