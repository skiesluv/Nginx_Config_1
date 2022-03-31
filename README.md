# Change the Nginx config for:
Tasks:
1. Redirect to medium.com

2. Redirect to medium.com with another status code.

3. Proxy to whatever you like site from URL/proxy path.

4. Display 4xx from URL/forbidden.

5. Do the basic auth for URL/login. 

6. Display the “success” status code.

7. Do load balancing with Nginx web server (upstream).

On the back end web servers, run the following commands to install NGINX:
sudo apt-get install -y nginx
uname -n | sudo tee /usr/share/nginx/html/index.html

