This project demonstrates containerizing a Node.js application using Docker and deploying it on Amazon EKS using Kubernetes.

Node.js App
   ↓
Docker Container
   ↓
Docker Hub
   ↓
EKS Cluster
   ↓
Kubernetes Deployment
   ↓
LoadBalancer Service
   ↓
Accessible via Browser

 Technologies Used
	•	Docker
	•	Kubernetes
	•	Amazon EKS
	•	Node.js
	•	AWS CLI
	•	eksctl

  Steps Performed
	1.	Created a Node.js application
	2.	Dockerized the application using Dockerfile
	3.	Built and pushed image to Docker Hub
	4.	Created EKS cluster using eksctl
	5.	Deployed application using Kubernetes Deployment
	6.	Exposed app using LoadBalancer service


Output

Application successfully deployed and accessed via AWS LoadBalancer URL

Challenges Faced
	•	Docker installation issues on macOS
	•	Kubernetes service exposure delays
	•	Debugging pod and service connectivity

  Key Learnings
	•	Containerization using Docker
	•	Kubernetes deployments and services
	•	EKS cluster management
	•	Debugging real-world deployment issues

  


  
