
### caddy as a reverse proxy to asp.net core application
The repository contains a demo application to use caddy2 webserver as reverse proxy to asp.net core application

###Steps to follow

1. Download caddy2 webserver from the URL https://caddyserver.com/v2
2. Make sure it is in path. (type caddy on command prompt)
3. Open command prompt and navigate to 'src/caddyaspnetcore' directory
4.  type 'dotnet run'. 	The application will start listening http://localhost:5000
5. Open another command prompt window and navigate to 'src/caddyaspnetcore' directory
6. type 'caddy run'. caddy will run as reverse proxy
7. open browser and type 'localhost'