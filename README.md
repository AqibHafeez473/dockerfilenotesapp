# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Docker installation must be in the machine  ubuntu


## Installation
1. Clone the repository
```
git clone https://github.com/Hitstar53/notesapp.git
```
2. Create a virtual environment and activate it
```
virtualenv venv
source venv/bin/activate
```
3. build docker file 
```
sudo docker build -t django_app .
```
4. Run the Container 
```
docker run -p 5000:5000  django_app
```



## Deployment
App is deployed on Railway: [Notes App](https://notesapp-production-8c87.up.railway.app/)  
Refer this article on how to: [deploy a django app on Railway](https://dev.to/osahenru/using-railway-app-to-deploy-your-django-project-3ah1)
