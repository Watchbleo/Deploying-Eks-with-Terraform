# terraform_eks
Creates an EKS cluster with a desired capacity of 2 in AWS
Create a new key-pair named "MyKey" in the region you are deploying this cluster.
Perform Terraform deployment process: init, validate, plan, apply --auto-approve.
few mins later the deployment will be completed,
# complete configuartion updates :
aws eks update-kubeconfig --region <region> --name <name of cluster>
# The project ends here. to tear down your resources use:
terraform destroy --auto-approve
