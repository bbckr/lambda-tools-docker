# lambda-tools-docker
Alpine docker image for packaging and deploying AWS lambda functions using serverless, terraform, and jinja. Only has python and node development tools.

## Git Tags
When tag `X.Y.Z` is pushed, a CircleCi workflow will start the job that builds and pushes the image `bckr/lambda-tools:${CIRCLE_TAG}` to the remote docker repository.
