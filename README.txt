DOCKER DEMO APPLICATION

1. Open this folder in VS Code.
2. Make sure Docker Desktop is running.
3. Open Terminal in this folder.
4. Run:
   docker build -t restaurant-demo .
5. Run:
   docker run -d -p 8080:80 --name restaurant-demo-container restaurant-demo
6. Open:
   http://localhost:8080
7. Show the professor:
   docker images
   docker ps

To stop:
   docker stop restaurant-demo-container

To remove:
   docker rm restaurant-demo-container
