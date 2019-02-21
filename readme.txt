https://www.terraform.io/
https://cloudbuilder.io/documentation/2018-04-02-Terraform-from-the-Beginning-part1/   (explains about 'terraform init')

https://aws.amazon.com/free/
https://aws.amazon.com/amazon-linux-ami/

git init
git add main.tf
git commit -m "Initial commit"
git add .gitignore
git commit -m "Add a .gitignore file"
git remote add origin https://github.com/adrianyorke/aws_terraform.git
git push origin master

terraform plan
terraform apply
terraform graph
terraform destroy
terraform output public_ip
