

**IAM Users:** \
#```
Users are individuals who have access to the AWS account resources. \
Users are created and managed in the IAM console. \
Each user is assigned a unique username and an access key ID. 
#```
**IAM Groups:** \
Groups are collections of users. \
Groups make it easier to manage permissions for multiple users. \
Groups are created and managed in the IAM console. 

**IAM Roles:** \
Roles are used to delegate permissions to AWS services or applications. \
Roles are created and managed in the IAM console. \
Roles can be assigned to AWS resources such as EC2 instances, AWS Lambda functions, and more. 

**Policies:** \
Policies are used to define permissions and restrictions on AWS resources. \
Policies can be attached to IAM users, groups, or roles. \
Policies are written in the JSON format. 

**Access Advisor:**\
Access Advisor is a feature within IAM that provides information on the last time an IAM user or role accessed a particular AWS service. \
Access Advisor helps you to identify the least privileged policies for your IAM roles and users. 

**Credential Report:** \
The IAM Credential Report is a document that provides detailed information about the IAM users and their credentials in your AWS account. \
The report is generated as a CSV file and can be used to audit and manage the security of your AWS account. 

**Best Practices:** \
Use strong passwords and multi-factor authentication for IAM users. \
Follow the principle of least privilege when assigning permissions to IAM users, groups, and roles. \
Use IAM roles to delegate permissions to AWS services and applications. \
Regularly review and audit IAM policies and users to ensure they are up-to-date and secure.  
