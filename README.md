# Deploying Multi-Region CI/CD to AWS via Terraform and Ansible Repo

This repo was originally created before Terrafom 0.13 was released however I have updated it to work with version 0.13 in the `terraform_v13_compatible_code` folder.
For following along using Terraform 0.12 refer to the `aws_la_cloudplayground_multiple_workers_version`.
Again, for following along using Terraform 0.13 refer to the `terraform_v13_compatible_code`.

## Warning
1. Parts of this repository expect users to obtain a Route53 domain name, which is available with ACG Playground tier subscription.
2. Following along and deploying resources in AWS as taught by this repo WILL incur charges!!! Be sure to destroy any infrastructure that you do not need.
