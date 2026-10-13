. Abstract
The Student Platform DevOps application is a practical demonstration of modern software engineering practices, combining version control, containerization, cloud hosting, and automated deployment workflows. The project is stored in GitHub, serving as the central hub for collaboration and code management. This report documents the application setup, the role of version control, the integration of cloud services, and the deployment pipeline. It also includes AWS screenshots provided by the student and illustrative command-terminal images. These images are included for clarity and explanation, but they are examples only and do not serve as proof of execution on the current project.
Project Details
Project repository: 
Purpose: maintain a student-platform application in source control and document a repeatable way to retrieve, configure, run, validate, and potentially deploy it.
Important verification note: inspect the repository README and file list before running commands. The app entry point, requirements file, Dockerfile, Jenkinsfile, and actual CI/CD configuration can vary. Commands below are labelled by scenario and should only be used when the matching files exist.
Aim and Objectives
•	Understand the project repository and its file structure.
•	Use Git to clone and inspect source code.
•	Install project dependencies using the repository's dependency manifest.
•	Run and test the app locally before deployment.
•	Explain AWS EC2 and SSH access for a Linux cloud server.
•	Document optional Docker and CI/CD workflows without claiming unverified execution.
DevOps
DevOps combines development and IT operations practices to improve collaboration, automation, repeatability, and feedback.
Git and GitHub
Git tracks code changes; GitHub hosts repositories and supports collaboration, reviews, issues, and automation.
AWS EC2
EC2 provides virtual servers. An instance is configured with an operating-system image, instance type, network rules, key pair, and storage.
