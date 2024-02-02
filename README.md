                                         #  **Netflix-clone-DevSecOps project**  #

Tool used:

1. AWS Account
2. Jenkins
3. Sonarqube
4. Trivy
5. EKS
6. ArgoCD
7. Docker and Dockerhub
8. Common Sense

Step 1: Launch EC2 (Ubuntu 22.04):

     Provision of an EC2 instance on AWS with Ubuntu 22.04.
     
     Connect to the instance using SSH.
     
   ![EC2](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/374c2f70-74e0-4191-9914-ac175b7ece07)


Step 2: Clone the Code:

    Update all the packages and then clone the code.

    Clone your application's code repository onto the EC2 instance

Step 3: Install Docker and Run the App Using a Container

Step 4: Build and run your application using Docker containers

Step 5:Step 4: Get the API Key:

     Open a web browser and navigate to TMDB (The Movie Database) website and generate API key.
     
   ![TMDB-api](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/d967fc5c-c999-4fd3-b3f0-ddaeb001a12e)


PHASE:Security

Step 6:    Install SonarQube and Trivy

    Install SonarQube and Trivy on the EC2 instance to scan for vulnerabilities.
    
  ![sonarqube dash](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/b4b09887-f568-410b-92f6-2c68546c9e4a)


Step 7: Integrate SonarQube and Configure:

    Integrate SonarQube with your CI/CD pipeline.
    
    Configure SonarQube to analyze code for quality and security issues
    
PHASE: CI/CD

Step 8: Install Jenkins for Automation.

Step 9: Configure Java and Nodejs in Global Tool Configuration in Jenkins.

Step 10: Install Dependency-Check Plugin: OWASP

    Now, you have installed the Dependency-Check plugin, configured the tool, and added Docker-related plugins along with your DockerHub credentials in Jenkins. 
    You can now proceed with configuring your Jenkins pipeline to include these tools and credentials in your CI/CD process.

Step 11: Add content from Pipeline.text into pipeline script in Jenkins

  ![jenkins pipeline](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/d9b95dcd-3fdc-47fc-be62-b6586469fa24)


Phase 4: Monitoring

Step 12: Install Prometheus and Grafana:

    Set up Prometheus and Grafana to monitor your application and create a systemd service unit.

Step 13: Install the Node Exporter

Step 14: Configure Prometheus Plugin Integration

         Install Grafana on Ubuntu 22.04 and Set it up to Work with Prometheus
         
   ![prometheus](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/10b76eb7-568b-4624-8c92-897b5fe75ca4)
         
  ![grafana](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/b3e92aff-5716-49df-82b3-9513c633c5ba)


         
Phase 6: Kubernetes

Step 15: Create Kubernetes Cluster with Nodegroups

  ![eks-cluster](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/3a0f1bb2-a884-42c8-b939-c635097f4594)
         
  ![node](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/68047b6a-193d-45a8-9c5a-b106ce26ff3c)


        Monitor Kubernetes with Prometheus

        Install Node Exporter using Helm

Step 16: Deploy the Application with ArgoCD

   ![Argocdbest](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/3a5a9c9d-8232-4466-be70-352ef4354b71)
         
  ![deplyed-site](https://github.com/hijackhim/Netflix-clone-DevSecOps-project/assets/105789918/15cc9f3a-bbea-4a6c-bbdb-85bf4349be0d)




Phase 7: Cleanup
        
       
