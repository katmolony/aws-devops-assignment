# AWS DevOps Assignment

This repository contains resources for demonstrating the deployment and automated management of a load-balanced auto-scaling web application on AWS.

## CloudFormation Template

The `cloudformation_template.yaml` file in this repository defines the infrastructure for the web application, including:

- Virtual Private Cloud (VPC)
- Subnets
- Security Groups
- Elastic Load Balancer (ELB)
- Auto Scaling Group
- Launch Configuration
- And more

## Scripts

- `deploy.sh`: A shell script to deploy the CloudFormation stack.
- `delete.sh`: A shell script to delete the CloudFormation stack.

## How to Use

1. **Clone this repository to your local machine:**
   ```sh
   git clone https://github.com/katmolony/aws-devops-assignment.git

2. **Deploy the CloudFormation stack using the provided script:**
    ```sh
    cd aws-devops-assignment
    ./deploy.sh

3. **Access the deployed web application using the Load Balancer DNS name.**

4. **When finished, delete the CloudFormation stack using the provided script:**
     ```sh
    ./delete.sh

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.