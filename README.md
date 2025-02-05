<h1>Secure File Sharing System - Project Plan</h1>
    <div class="day-section">
        <h2>Day 1: Project Setup & Planning ✅</h2>
        <ul>
            <li>Finalize architecture & assign tasks.</li>
            <li>Create a GitHub repository for code collaboration.</li>
            <li>Set up AWS accounts and permissions.</li>
            <li>AWS Architect starts setting up S3 bucket, VPC, IAM roles.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: PM, AWS Architect, Security Specialist</p>
    </div>
    <div class="day-section">
        <h2>Day 2: Backend Setup & S3 Integration ✅</h2>
        <ul>
            <li>Backend Developers set up a Flask/Django project.</li>
            <li>Install necessary dependencies (boto3, Flask, Django, etc.).</li>
            <li>Write API to upload files to S3.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Backend Dev 1, AWS Architect</p>
    </div>
    <div class="day-section">
        <h2>Day 3: Presigned URLs & Secure File Retrieval ✅</h2>
        <ul>
            <li>Implement presigned URLs for file access.</li>
            <li>Test URL expiration & access control.</li>
            <li>Security Specialist fine-tunes S3 bucket policies & encryption.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Backend Dev 2, Security Specialist</p>
    </div>
    <div class="day-section">
        <h2>Day 4: Authentication System ✅</h2>
        <ul>
            <li>Implement user authentication (Flask login/Django auth or AWS Cognito).</li>
            <li>Restrict file access based on user roles.</li>
            <li>AWS Architect ensures IAM roles allow secure access.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Backend Dev 2, AWS Architect</p>
    </div>
    <div class="day-section">
        <h2>Day 5: Frontend Development Begins ✅</h2>
        <ul>
            <li>Frontend Developer sets up a basic UI (React or simple HTML/Bootstrap).</li>
            <li>Implements file upload & list-view of stored files.</li>
            <li>Connects frontend with backend APIs.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Frontend Dev</p>
    </div>
    <div class="day-section">
        <h2>Day 6: Deployment on EC2 & Security Enhancements ✅</h2>
        <ul>
            <li>DevOps sets up EC2 instance, configures Flask/Django server.</li>
            <li>Backend team tests API endpoints on EC2.</li>
            <li>Security Specialist ensures HTTPS, IAM security best practices.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: DevOps, Backend Devs, Security Specialist</p>
    </div>
    <div class="day-section">
        <h2>Day 7: Logging & Monitoring (CloudWatch & CloudTrail) ✅</h2>
        <ul>
            <li>DevOps sets up CloudWatch for error monitoring.</li>
            <li>Logs unauthorized access attempts.</li>
            <li>PM checks if all components are working as expected.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: DevOps, Security Specialist, PM</p>
    </div>
    <div class="day-section">
        <h2>Day 8: CloudFront Integration & Performance Optimization ✅</h2>
        <ul>
            <li>AWS Architect sets up CloudFront for faster file access.</li>
            <li>Tests caching & performance.</li>
            <li>Backend team refines API error handling.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: AWS Architect, Backend Devs</p>
    </div>
    <div class="day-section">
        <h2>Day 9: Testing & Bug Fixing ✅</h2>
        <ul>
            <li>Frontend & backend teams run integration tests.</li>
            <li>Check file upload/download, authentication, and security policies.</li>
            <li>Fix UI bugs, API errors, IAM misconfigurations.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Entire Team</p>
    </div>
    <div class="day-section">
        <h2>Day 10: Final Review & Deployment ✅</h2>
        <ul>
            <li>Deploy project on AWS (EC2, S3, CloudFront, IAM).</li>
            <li>Write a short project documentation (README.md).</li>
            <li>PM & team test final version.</li>
            <li>Present/demo the project.</li>
        </ul>
        <p class="assigned">🔹 Assigned To: Entire Team</p>
    </div>
    <div class="bonus">
        <h2>Bonus Enhancements (If Time Permits) 🚀</h2>
        <ul>
            <li>Implement a dashboard to track file-sharing statistics.</li>
            <li>Add a notification system (SNS) for file-sharing alerts.</li>
            <li>Use Lambda functions to auto-delete expired files.</li>
        </ul>
    </div>

<h2>Developed by: Yash, Vamshi, Rafiya, Shruti, Snehal, Vinay and Krutika</h2>
