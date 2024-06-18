## Integrating AWS DevOps: Complete CI/CD Pipeline 

This project demonstrates the implementation of DevOps practices on the AWS cloud platform. It showcases a complete CI/CD pipeline using AWS services such as CodeCommit, CodeBuild, CodeDeploy, and CodePipeline.

### Project Overview

The project flow involves a developer pushing code to a website stored in an AWS CodeCommit repository. Subsequently, AWS CodeBuild automatically builds the code and deploys it to an S3 bucket. In the next stage, the built and tested code from CodeBuild is uploaded to an Amazon S3 bucket configured as a website. Finally, AWS CodeDeploy takes the tested code from CodeBuild and deploys it to an Elastic Beanstalk environment.

### Project Steps

1. **Setting up the AWS and Git Environment**: Create a new CodeCommit repository, clone it locally, and add project files.

2. **CodeBuild**: Configure a CodeBuild project to build the source code, execute tests, and generate deployable artifacts.

3. **Creating EC2 Instance and Setting Up CodeDeploy Agent**: Create an EC2 instance and install the CodeDeploy agent to facilitate deployments.

4. **CodeDeploy**: Set up a CodeDeploy application and deployment group to automate software deployments to the EC2 instance.

5. **Creating Deployments**: Create a deployment in CodeDeploy, specifying the S3 artifact location and target EC2 instances.

6. **Creating a Complete CI/CD Pipeline with CodePipeline**: Set up a CodePipeline that orchestrates the entire workflow, from source code management to deployment, automating the CI/CD process.

### Technologies Used

- AWS CodeCommit
- AWS CodeBuild
- AWS S3
- AWS CodeDeploy
- AWS EC2
- AWS CodePipeline
- AWS IAM (for roles and permissions)

### Getting Started

To get started with this project, you'll need an AWS account and the necessary permissions to create and manage the required AWS services. Follow the step-by-step guide provided in the project documentation for detailed instructions.

