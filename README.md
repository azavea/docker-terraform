# docker-terraform [![CI](https://github.com/azavea/docker-terraform/workflows/CI/badge.svg?branch=master)](https://github.com/azavea/docker-terraform/actions?query=workflow%3ACI) [![Docker Repository on Quay](https://quay.io/repository/azavea/terraform/status "Docker Repository on Quay")](https://quay.io/repository/azavea/terraform)

This repository contains a templated `Dockerfile` for image variants designed to run deployments using the AWS CLI and `terraform`.

## Usage

### Template Variables

- `TERRAFORM_VERSION` - Terraform version

### Testing

An example of how to use `cibuild` to build and test an image:

```bash
$ CI=1 TERRAFORM_VERSION=0.13.5 ./scripts/cibuild
```
