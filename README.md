
<h1 align="center">Multi-Region Jenkins CI/CD Deployment to AWS via Ansible-Terraform</h1>


<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
- [Built With](#built-with)
- [Features](#features)
- [How to use](#how-to-use)
- [Contact](#contact)
- [Warning] (#warning)

<!-- OVERVIEW -->

## Overview

![ScreenShot](https://github.com/sezginerdem/p11-MultiRegion_Jenkins_CI-CD_Dep_Ansible-Terraform/blob/master/images/1Distributed_Multi-Region_Jenkins_CI-CD_Deployment.png)

I compared and contrasted Terraform, Ansible, and Terraform in this project as I gear up for diving into this project to use all of these infrastructure-as-code technologies.

In this project, I went through a brief summary of what I did building as an end result of this goal, and how those individual units of infrastructure were going to be connected and deployed via Ansible and Terraform.

### Built With

- Terraform
- Ansible
- AWS
- Jenkins

## Features

This deployment is to use Terraform and Ansible to deploy a distributed Jenkins CI/CD pipeline and put it behind one of the company's DNS domains for testing.

## How To Use

To clone this repo and you'll need [Git](https://git-scm.com) installed on your computer and [AWS](https://us-east-1.signin.aws.amazon.com/) account. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/sezginerdem/p11-MultiRegion_Jenkins_CI-CD_Dep_Ansible-Terraform.git

```

You can find the solution in this repo at [Solution.md](https://github.com/sezginerdem/p11-MultiRegion_Jenkins_CI-CD_Dep_Ansible-Terraform/blob/master/Solution.md) file.

## Contact

- GitHub [@sezginerdem](https://{https://github.com/sezginerdem})
- Linkedin [@sezginerdem](https://{https://www.linkedin.com/in/sezginerdem/})
- Medium [@sezginerdem](https://serdem.medium.com/)
)

## Warning
1. Parts of this repository expect users to obtain a Route53 domain name, which is available with ACG Playground tier subscription.
2. Following along and deploying resources in AWS as taught by this repo WILL incur charges!!! Be sure to destroy any infrastructure that you do not need.
