## Python-app

Python app to deploy in Docker <br>
Is to use with Docker compose or Docker stack

### With Docker compose

Clone the repository:
```
  git https://github.com/lunabacilio/python-app.git
```
Join to the folder:
```
  cd python-app
```  
Run Docker compose command:
```  
  docker-compose up -f docker-compose.yml -d
```
Join to your public IP in your navigator to check if is running the app:
```
  http://<PUBLIC_IP>
```
### With Docker Stack

Run Docker Stack command:
```
  docker stack deploy --compose-file docker-compose-stack.yml python_app
```
Check your stacks
```
  docker stack ls
  
  docker service ls
```
