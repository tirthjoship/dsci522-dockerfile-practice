# DSCI 522 Dockerfile Practice

This repository contains a Docker image that extends the Jupyter minimal-notebook with additional Python packages (pandas and numpy).

## Contents

- `Dockerfile`: Docker image configuration
- `environment.yml`: Conda environment specification
- `conda-linux-64.lock`: Locked dependencies for reproducibility
- `.github/workflows/docker-publish.yml`: CI/CD workflow for automated Docker builds

## Docker Image

The Docker image is automatically built and published to DockerHub via GitHub Actions.

DockerHub: https://hub.docker.com/r/tirthjoship/dsci522-dockerfile-practice
