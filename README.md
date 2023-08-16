
    Ensure you have virtial box and vagrant already installed.
    Its good to have vscode and bash installed to make running commands easier in windows

Getting Started

1. Start the VM
    - TF_FOLDER='path-to-terraform-code' vagrant up
1. SSH into the VM to run terraform commands.
    - vagrant ssh
    - cd <path-to-terraform-code> (path specified while runing vagrant up)
1. Run terraform commands
    - terraform init
    - terraform validate
    - terraform plan
    - terraform apply

Note
- change the terraform version in the vagrant file as per version used in CICD
