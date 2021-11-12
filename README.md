# terraform-aws-module
for aws via terraform

module "s1" {
  source  = "app.terraform.io/ibm-nov/ibmserver/aws"
  version = "1.0.0"
  bucket-name = "gagan-new-tf-bucket-3"
  name = "gds-server-3"
}
