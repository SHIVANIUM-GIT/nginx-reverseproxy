# Nginx Project

 - This NGINX configuration sets up a basic HTTP server listening on port 80.

 - It serves static files from /usr/share/nginx/html for requests to /, and it proxies requests to /app1, /app2, and /devops to other backend services (app1, app2, and http://google.com/ respectively). 

 - It also specifies custom error pages for server errors. 

 - This configuration is typical for routing and proxying requests to different backend applications or services based on URL paths.
