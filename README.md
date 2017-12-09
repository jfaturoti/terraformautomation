# terraformautomation
---------------------
provider "aws" {
  region     = "us-east-2"
}

resource "aws_instance" "example" {
  ami           = "ami-4b270e2e"
  instance_type = "t2.micro”
}
-------------------------------------
