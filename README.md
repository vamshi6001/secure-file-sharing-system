# secure-file-sharing-system

Day 1: Project Setup & Planning
✅ Finalize architecture & assign tasks.
✅ Create a GitHub repository for code collaboration.
✅ Set up AWS accounts and permissions.
✅ AWS Architect starts setting up S3 bucket, VPC, IAM roles.
🔹 Assigned To: PM, AWS Architect, Security Specialist

Day 2: Backend Setup & S3 Integration
✅ Backend Developers set up a Flask/Django project.
✅ Install necessary dependencies (boto3, Flask, Django, etc.).
✅ Write API to upload files to S3.
🔹 Assigned To: Backend Dev 1, AWS Architect

Day 3: Presigned URLs & Secure File Retrieval
✅ Implement presigned URLs for file access.
✅ Test URL expiration & access control.
✅ Security Specialist fine-tunes S3 bucket policies & encryption.
🔹 Assigned To: Backend Dev 2, Security Specialist

Day 4: Authentication System
✅ Implement user authentication (Flask login/Django auth or AWS Cognito).
✅ Restrict file access based on user roles.
✅ AWS Architect ensures IAM roles allow secure access.
🔹 Assigned To: Backend Dev 2, AWS Architect

Day 5: Frontend Development Begins
✅ Frontend Developer sets up a basic UI (React or simple HTML/Bootstrap).
✅ Implements file upload & list-view of stored files.
✅ Connects frontend with backend APIs.
🔹 Assigned To: Frontend Dev

Day 6: Deployment on EC2 & Security Enhancements
✅ DevOps sets up EC2 instance, configures Flask/Django server.
✅ Backend team tests API endpoints on EC2.
✅ Security Specialist ensures HTTPS, IAM security best practices.
🔹 Assigned To: DevOps, Backend Devs, Security Specialist

Day 7: Logging & Monitoring (CloudWatch & CloudTrail)
✅ DevOps sets up CloudWatch for error monitoring.
✅ Logs unauthorized access attempts.
✅ PM checks if all components are working as expected.
🔹 Assigned To: DevOps, Security Specialist, PM

Day 8: CloudFront Integration & Performance Optimization
✅ AWS Architect sets up CloudFront for faster file access.
✅ Tests caching & performance.
✅ Backend team refines API error handling.
🔹 Assigned To: AWS Architect, Backend Devs

Day 9: Testing & Bug Fixing
✅ Frontend & backend teams run integration tests.
✅ Check file upload/download, authentication, and security policies.
✅ Fix UI bugs, API errors, IAM misconfigurations.
🔹 Assigned To: Entire Team

Day 10: Final Review & Deployment
✅ Deploy project on AWS (EC2, S3, CloudFront, IAM).
✅ Write a short project documentation (README.md).
✅ PM & team test final version.
✅ Present/demo the project.
🔹 Assigned To: Entire Team

Bonus Enhancements (If Time Permits)
🚀 Implement a dashboard to track file-sharing statistics.
🚀 Add a notification system (SNS) for file-sharing alerts.
🚀 Use Lambda functions to auto-delete expired files.
