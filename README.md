# CI-CD-Website-update:

**Project Report: Setting Up CodePipeline for Website Deployment**

**Overview:**
This project involved setting up an automated deployment process for a static website using AWS CodePipeline, GitHub, and Amazon S3. The objective was to establish an efficient and reliable workflow where updates made to a GitHub repository are automatically deployed to an S3 bucket, ensuring seamless website updates.

**Project Steps:**

1. **CodePipeline Configuration:**
   - Created an AWS CodePipeline in the Amazon Web Services (AWS) Management Console.
   - Linked the CodePipeline to my GitHub repository containing the static website's source code.
   - Configured the pipeline to automatically trigger when changes are pushed to the GitHub repository.

2. **Pipeline Stages:**
   - Designed the pipeline with stages that facilitate the deployment process.
   - Set up a source stage to fetch changes from the GitHub repository.

3. **Local Host Configuration:**
   - Established a local development environment on my machine.
 
4. **Website Updates**
   - Made code changes to the static website's source code.
   - Tested the changes locally using the local development environment.

5. **GitHub Commits and Triggers:**
   - Committed the changes to the GitHub repository.
   - GitHub's integration with CodePipeline triggered the pipeline to initiate the deployment process.

6. **Deploy Stage:**
   - Configured the deployment stage to upload the changes directly to the Amazon S3 bucket hosting https://iamjossi.com/
   
7. **Update Reflection:**
   - After the changes were successfully deployed to the S3 bucket, the website reflected the update.

