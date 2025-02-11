# AWS_Terraform_Template
Terraform Template for AWS Cloud Platform.


**Prerequisites**
- Install Chocolatey (Windows OS)
Running using Powershell With Admin Role:
`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`
Verify:
`choco -version`
- Install Terraform CLI (Windows OS) - Chocolatey
`choco install -y terraform`
- Install AWS CLI (Windows OS) - Chocolatey
`choco install awscli -y`
`Import-Module "$env:ChocolateyInstall\helpers\chocolateyProfile.psm1"`
`refreshenv`
Verify:
`aws --version`
- Install Kubectl (Windows OS) - Chocolatey
`choco install kubernetes-cli -y`
Verify:
`kubectl version --client`
- Install Amazon EKS CLI (Windows OS) - Chocolatey
`choco install eksctl -y`
Verify:
`eksctl version`

# Git Process
- merge a branch to main/master branch
`git checkout main`
`git pull orgin main`
`git merge dev`
`git push origin main`


Steps to runs:
At root dir run `terraform init`


