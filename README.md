# RapidFortTask  
This is a simple REST-API bsed Web Server where you can submit a file and get complete file details in response . It uses NodeJs  for making API and also has a simple UI for interaction . The Service is also Hosted on GKE .

# Getting Started  
**Prerequistes**  
1. NodeJs (backend)
2. Docker (Containerisation)
3. Kubectl ( for Local Kuberentes Deployment)

**Cloning Repository**  
  
```git clone https://github.com/SaarthakMarkandey/RapidFortTask```  
  
```npm start```

**Installing Docker Desktop**  

  https://www.docker.com/products/docker-desktop/

**Building Docker File**

```docker build -t image-name:tag path-to-dockerfile-directory```

**Installing Kubectl(Minikube)**  

  https://minikube.sigs.k8s.io/docs/start/  
  
**Creating Kuberenetes Manifest Files**  

  ```kubectl apply -f deployment.yaml``` 
  
  ```kubectl apply -f service.yaml```
  
**Running the Application Locally**  

  ```minikube service express-api```

**For Live Demo**  
http://35.239.111.107:5000/

  
  
  
  



