# devops challenge

Get this [app](https://github.com/pbuditi/Devops-challenge) up and running on any public cloud (AWS for example) using your known 
best practices as well as the instructions in the guidelines below.

You should use [provisioner](https://www.terraform.io/docs/provisioners/index.html/) to install and configure everything. You can use provisioner of your choice.

When you're done, we should be able to type `terraform apply` and terraform should output the app url example:
APP is running and reachable on http port 80 at `http://10.10.10.20`

The URL can contain either a DNS or a public IP accessible.

### Guidelines:
  - The provisioner should clone [this github repo](https://github.com/pbuditi/Devops-challenge) into the instance under `/webapps/`
  - You should be able to find what system packages are needed by looking through the app
  - You should not need to change the app code in any way


You may use another any preferred flavor of Linux.
