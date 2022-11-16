# Welcome to V2 of Sumo's CSPM ;)  

### Steps taken below!


1. Create my [RDS database](https://github.com/terraform-aws-modules/terraform-aws-rds/tree/master/examples/complete-postgres) in AWS. 
    ``` 
    git clone https://github.com/terraform-aws-modules/terraform-aws-rds.git 
    ```
    - Then CD into the examples directory, in this cause I chose the "complete-postgres" because CQ prefers this.
    ``` 
    cd terraform-aws-rds/examples
    ```
    - *If you need to update your configuration (i.e., change default instances size, please change line for "[instance_class](*will insert link*)" )
    - Deploy the configuration 
    ```terraform
    terraform init
    terraform plan
    terraform apply
    ```

    