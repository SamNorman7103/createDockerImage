Cd into the docker project location and run the following 
Build: docker build -t myapp:latest .   
Run: docker run -d --name test -p 8080:8080 myapp 

Open browser and go to localhost:8080
