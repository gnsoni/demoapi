--Publish application
dotnet publish


--Build docker image
docker build -t "demoapi:1.0" .


--Run image as container
docker run -p 80:80 -p 7137:7137 demoapi:1.0


Go to browser, navigate to local host, however swagger isn't working.

