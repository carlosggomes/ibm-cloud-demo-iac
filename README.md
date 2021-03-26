Example for VPC resources
This example illustrates how to use the vpc resources to create on IBM Cloud.

Terraform 0.12.

Usage
To run this example you need to execute:

$ terraform init
$ terraform plan
$ terraform apply

Run terraform destroy when you don't need these resources.

Notes
The Variables used in main.tf are declared in variables.tf
source = https://github.com/IBM-Cloud/terraform-provider-ibm/blob/master/examples/ibm-is-vpc/main.tf


**IAAS
SCHEMATICS**


https://registry.terraform.io/providers/IBM-Cloud/ibm/latest/docs
https://cloud.ibm.com/docs/ibm-cloud-provider-for-terraform?locale=en

https://github.com/IBM-Cloud/terraform-provider-ibm/tree/master/examples



**TERRAFORMS**
    WORKSPACE    infra-as-code-demo
    GIT                      https://github.com/carlosggomes/ibm-cloud-demo-iac
    SSH_KEY            ssh-fra-cguarany
    NAME                demo-iac

**ANSIBLE**
    ACTION           myaction-ansible-demo
    GIT                   https://github.com/carlosggomes/ibm-cloud-demo-ansible
    VARIAVEL       domain:cguarany-demo-cloud
    BASTION         IP xxxxx
    INVENTORY    [web] + IP
    SSH_KEY          PRIVATE


-----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAACFwAAAAdzc2gtcn
NhAAAAAwEAAQAAAgEA1v+QqlgR9v2cjpFskDgyDKO14UyR/ihgXdve0F0H7QjhSMv63hQD
...
oH3bsbd4qKsfAAAACGNndWFyYW55AQI=
-----END OPENSSH PRIVATE KEY-----




**IBM CLOUD OBJECT STORAGE**


CRIAR SERVIÇO ICOS (SIMULAR)
EXPLICAR AS REGRAS
Archive rule
Expiration
Retention policy
Static website hosting
CRIAR WEB SERVER
CRIAR BUCKET
b3-demo-website1
demo-icos.html
https://b3-demo-website1.s3-web.sao01.cloud-object-storage.appdomain.cloud

