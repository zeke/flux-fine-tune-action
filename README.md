# Flux Fine-tune action

This is an example repo for **fine-tuning and publishing your own custom [Flux](https://replicate.com/blog/fine-tune-flux-with-faces) model** using [Replicate](https://replicate.com) and [GitHub Actions](https://github.com/features/actions).

## Preqrequisites

- A [Replicate](https://replicate.com/account) account
- A handful of training images

## Training the model

1. Fork this repository.
1. Remove the images in the [data](data) directory and replace them with your own images.
1. Commit your changes to Git and push to your main branch on GitHub.
1. Create a [Replicate API token](https://replicate.com/account/api-tokens) and add it as a [repository secret](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository) named `REPLICATE_API_TOKEN`.
1. Trigger the workflow from your GitHub repo page: "Actions" > "Train a model" > "Run workflow".
1. Go to the [replicate.com/trainings](https://replicate.com/trainings) to see your training in progress.

## Running the model

Check out these guides for tips on training and running Flux models:

- https://replicate.com/blog/fine-tune-flux-with-faces
- https://replicate.com/blog/fine-tune-flux-with-an-api
- https://replicate.com/blog/using-synthetic-data-to-improve-flux-finetunes