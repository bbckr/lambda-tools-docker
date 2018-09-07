# lambda-deploy-tools
Docker image for packaging and deploying AWS lambda functions using serverless, terraform, and jinja.

## Git Tags
When tag `X.Y.Z` is pushed, a CircleCi workflow will start the job that builds and pushes the image `bckr/minecraft-forge:${CIRCLE_TAG}` to the remote docker repository.
