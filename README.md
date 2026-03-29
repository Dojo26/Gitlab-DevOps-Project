# Gitlab-DevOps-Project
Stood up a Gitlab Ec2 Server
Setup Production environment for application
--Created Iam role that allowed runner to access S3
--Attched created role to the Gitlab Server
--Created an S3 bucket
--Enabled "Static Hosting" to allow public access to the website.
CI/CD Configuration
--Created a .gitlab-ci.yml file in Yaml format and saved it to root repo
--The yml file contained the stages and commands in each stage.
--Added the deploy stage with the commands and commited it to the master branch.
Modified the index.js and added additional text and commited this change to the master branch.
