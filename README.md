# continuous-delivery
This project will set up infrastructure on AWS to allow developers to deploy their application automatically.

# Requirements
* terraform
* aws cli configured
* github token (<a href="https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/">details</a>)

# Architecture

<img src="https://github.com/thiagonache/continuous-delivery/blob/master/CI_CD%20platform%20-%20Page%201.png">

# Bootstraping
1. Clone repo
```
$ git clone https://github.com/thiagonache/continuous-delivery/
```

1. Apply changes
```
$ terraform init
$ terraform plan
$ terraform apply
```
