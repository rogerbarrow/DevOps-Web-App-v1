# DevOps-Web-App-v1

The main goal of this project is to implement DevOps practices in the Go web application. The project is a simple website written in Golang. It uses the net/http package to serve HTTP requests.
# DevOps practices include the following:
1. Creating Dockerfile (Multi-stage build)
2. Containerization
3. Continuous Integration (CI)
4. Continuous Deployment (CD)
# Summary Diagram
![image](https://github.com/user-attachments/assets/99b3c34b-80de-451a-a628-e3f36ccffcfa)
# Step 1. Clone you App locally via the Git Clone command
![image](https://github.com/user-attachments/assets/d27c82ad-9b41-4929-8cf0-c8d871c83b18)
# Step 2.  Open the Application I will be using VScode
![image](https://github.com/user-attachments/assets/0b80916e-26d2-42cf-ab0d-07b077d97150)
# Step 3. Create and Write the Multi Stage Dockerfile
![image](https://github.com/user-attachments/assets/5b3f3229-2fbe-4bc0-a42d-9a033ffee144)
# Step 4. Run your Docker build -t Command and Docker run Command
![image](https://github.com/user-attachments/assets/068c1128-ab74-4b78-833c-cca6c3fe8495)
![image](https://github.com/user-attachments/assets/49fe083e-5c90-44ef-9d07-c3473a3334c5)
![image](https://github.com/user-attachments/assets/3f8aa7b1-5a39-4d01-87f2-1134ad4febb0)
# Go to Localhost to verify that your App Containerized and Running
# Step 5.  Step 3 Push the Docker image to Docker Hub Repository
![image](https://github.com/user-attachments/assets/c561550a-c89c-49b7-9664-7137c12bf19e)
# Step 6.  Next we will write the Kubernetes Manifest File. First we will Create a Deployment.yaml
![image](https://github.com/user-attachments/assets/f7268afb-6176-47b0-8838-3d267ec3bcef)
# Step 7. Then we create a service.yaml
![image](https://github.com/user-attachments/assets/8097d262-5d75-4bd8-9804-a7a6dbb7747d)
# Step 8. After we will now create a ingress.yaml file
![image](https://github.com/user-attachments/assets/bac63544-697b-4311-aa65-e0af1a2f0f1d)
# Next Create a EKS Cluster Login to AWS using aws configure
![image](https://github.com/user-attachments/assets/f0c661d3-2fb7-4392-b912-c4861eca1b32)
![image](https://github.com/user-attachments/assets/9160d5fe-91dc-462e-91d3-912b1aa0cfff)
![image](https://github.com/user-attachments/assets/62afc920-9d02-4cf1-89da-424a2a5318ab)
#  run the Kubectl command to create the pods
![image](https://github.com/user-attachments/assets/fbecfa5e-76e3-48e9-bc21-a346b14f5873)
# Create Ingress pod 
![image](https://github.com/user-attachments/assets/d68e0f67-f370-40bc-8961-9b63ead43105)
# Create service pod
![image](https://github.com/user-attachments/assets/ba60dfb3-50ec-472f-a0e0-d4ae6b921e5f)
# Get the Node IP address and Cluster IP
![image](https://github.com/user-attachments/assets/caeef347-1c01-4168-bfe6-3bc77a9485be)








