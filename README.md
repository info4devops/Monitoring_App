# CPC and Memmory Utilization Monitoring Application 
# Languages Used
 - Python: psutils, flask
 - HTML

# Requirments
- Flask==2.2.3
- MarkupSafe==2.1.2
- Werkzeug==2.2.3
- itsdangerous==2.1.2
- psutil==5.8.0
- plotly==5.5.0
- tenacity==8.0.1
- boto3==1.9.148
- kubernetes==10.0.1

# Git Repository clone

```bash
  git clone https://github.com/info4devops/Monitoring_App.git
  cd Moniroring_App/
   
```

# Docker Installation

```bash
  curl -fsSL https://get.docker.com -o install-docker.sh
  cat install-docker.sh
  sh install-docker.sh --dry-run
  sudo sh install-docker.sh 
```

# Docker Commands
```bash
  sudo docker build -t my-flask-app .
  sudo docker images
  sudo docker run --name mycontainer -d -p 5000:5000 my-flask-app 

```
# Push Docker Images to Docker Hub
```bash
  docker login 
  docker login -u <user_name> 
  # Enter password for Docker Hub
  sudo docker tag  my-flask-app <dockerHub_user_name>/my-flask-app:latest
  sudo docker push <dockerHub_user_name>/my-flask-app:latest
  
```

# Final Result
CPC Utilization: ![alt text](image.png)

Memory Utilization: ![alt text](image-1.png)

