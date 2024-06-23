# Simple Notes App
This is a simple notes app built with React and Django.

#Requirements
1. Python 3.9
2. Node.js
3. React

#Installation
1. Clone the repository
 ```bash
   git clone https://github.com/LondheShubham153/django-notes-app.git
 ```
3. Build the app
```bash
  docker build -t notes-app .
```
3. Run the app
```bash
  docker run -d -p 8000:8000 notes-app:latest
```
#Nginx
Install Nginx reverse proxy to make this application available
```bash
  sudo apt-get update
```
```bash
  sudo apt install nginx
```
   
