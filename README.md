# docker-terraform

This repository contains a templated `Dockerfile` for image variants designed to run deployments using the AWS CLI and `terraform`.

## Usage

### Template Variables

- `TERRAFORM_VERSION` - Terraform version

### Testing

An example of how to use `cibuild` to build and test an image:

```bash
$ CI=1 TERRAFORM_VERSION=0.12.13 ./scripts/cibuild
```
