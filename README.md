*MyDirection App
A feature-rich web application designed for interactive navigation and real-time mapping. Developed using modern web technologies and deployed with CI/CD practices for enhanced reliability and scalability.

*Features
Interactive Front-End: Built with HTML, CSS, and JavaScript for an engaging user experience.
Google Maps API Integration: Provides accurate mapping functionality and real-time navigation capabilities.
DevOps Workflow: Leveraged AWS CodeCommit, CodeBuild, and CodeDeploy for a seamless CI/CD pipeline.
AWS Deployment: Deployed on an EC2 instance with services like IAM, S3, and EC2 for security and scalability.

*Technologies Used
Frontend: HTML, CSS, JavaScript
API Integration: Google Maps API
DevOps Tools:
AWS CodeCommit
AWS CodeBuild
AWS CodeDeploy
Deployment Platform: AWS EC2
Additional AWS Services: IAM, S3

*Setup and Installation
Follow these steps to set up and run the application locally:

1. Clone the repository:
git clone https://github.com/yourusername/mydirection-app.git
cd mydirection-app
2. Open the index.html file in a browser to view the app.
3. Add your Google Maps API Key:

Navigate to the JavaScript file where the API key is used.
Replace <YOUR_API_KEY> with your Google Maps API key.
4. Deploy on AWS EC2:

Configure your EC2 instance.
Upload the project files to the instance.
Ensure the required IAM roles and S3 buckets are set up.

Continuous Integration/Deployment
CodeCommit: Manages source code repositories.
CodeBuild: Automatically builds the project after code changes.
CodeDeploy: Deploys the application to the EC2 instance seamlessly.
