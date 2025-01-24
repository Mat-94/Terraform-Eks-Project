# Terraform-Eks-Project
EKS Terraform Project Documentation

Initial Setup

Launch EC2 Instance
![Screenshot (298)](https://github.com/user-attachments/assets/57d5f4fa-4e89-4fed-b1be-b1e7082cfb0c)


Instance type: t2.medium.

SSH into the instance.

Open Port 8080

Ensure port 8080 is open on your EC2 instance to allow Jenkins connections.
![Screenshot (300)](https://github.com/user-attachments/assets/fec3ea61-879d-4501-b025-463924a24901)

Install Jenkins Plugins

Install the Pipeline Stage View plugin in Jenkins.
![Screenshot (302)](https://github.com/user-attachments/assets/0c488ef7-4d80-48b2-93e4-df7680e02090.
![Screenshot (303)](https://github.com/user-attachments/assets/a400fc19-2fe9-4781-9dca-28ca71b8bbed)


Configure AWS CLI

Create an IAM user with necessary permissions.


Generate and configure secret access keys in Jenkins


Jenkins pipeline was built with the script as seen in the image below


![Screenshot (309)](https://github.com/user-attachments/assets/d0fd9878-6188-4b7d-98bd-538b54f29ce4)


Challenges Encountered

GitHub Code Not Found

Issue: The pipeline failed to locate the code in the GitHub repository.

Resolution: Identified a wrong name reference in the Jenkins configuration. Corrected it, and the pipeline succeeded.

Indentation Problems in Groovy Script

Issue: Errors due to improper indentation in the pipeline script.

Resolution: Carefully reviewed and corrected the indentation to align with Groovy syntax requirements.

Skills and Tools Highlighted

Skills: Debugging, Jenkins pipeline creation, AWS CLI configuration, Terraform management.

Tools: Jenkins, Terraform, AWS CLI, GitHub.





