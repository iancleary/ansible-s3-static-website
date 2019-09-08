# AWS S3 Static Website Deployment w/ localhost Ansible Playbook

Hi, I'm Ian Cleary and please use this code to help you deploy a static site to an AWS S3 bucket.

## Dependencies and Installation

------------

* [AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Setup

------------
I used this ansible playbook to deploy my website to an AWS S3 Bucket using an ansible role described in [roles/deploy-website-s3/README.md](roles/deploy-website-s3/README.md). After configuring the ansible [playbook](main.yml), please execute it us the localhost ansible [deploy bash script](deploy.sh).  Use [this bash script](check.sh) to check your ansible playbook.

## Attributions

* [Ansible playbook](https://github.com/dmitri-lerko/ansible-jekyll) for showing me how much simpler of a solution this is than using the s3 boto python interface, for this type of task.
