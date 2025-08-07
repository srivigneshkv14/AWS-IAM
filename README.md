AWS-IAM

AWS Identity and Access Management (IAM) is the central service for controlling who has access to what within your AWS environment.

• IAM Users

This involves creating and managing IAM users and their permissions to interact with AWS resources.

• IAM Groups

This provides a mechanism for managing access to AWS resources efficiently and securely. Instead of individually assigning permissions to each user, you can group users based on their roles or responsibilities, then attach policies to those groups.

• IAM Policies 

AWS IAM policies are JSON documents that define permissions, allowing or denying access to AWS resources and actions. They are fundamental for implementing secure access control within your AWS environment, ensuring that users, groups, and roles can only perform the tasks necessary for their roles.

• IAM Roles

AWS IAM roles are identities that define a set of permissions, allowing trusted entities to temporarily assume those permissions to access AWS resources.

 IAM had built on three fundamental pillars: identification, authentication, and authorization.

• Identification

Identification is the initial step where a user or entity makes a claim about their identity.

   • IAM user
      
   • IAM roles
      
• Authentication

Authentication is the process of verifying an entity's identity by validating the credentials presented during the identification stage.

   • Multi-Factor Authentication (MFA): This crucial security feature adds an extra layer of protection by requiring a second verification factor in addition to         the primary credential

• Authorization

Authorization determines what actions an authenticated entity can perform on specific AWS resources. It's managed through policies, which are JSON documents defining the permitted or denied actions. 

   • Identity-based policies
   • Resource-based policies
