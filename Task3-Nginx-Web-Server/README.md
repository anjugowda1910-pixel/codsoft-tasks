# CodSoft DevOps Internship - Task 3

## Nginx Web Server Deployment

This task demonstrates the installation and configuration of Nginx on Ubuntu Linux and the deployment of a static website using an Nginx virtual host.

### Objectives

- Install and configure Nginx on Linux
- Host a static website using Nginx
- Configure a virtual host/server block
- Configure a custom 404 error page
- Test website accessibility

### Technologies Used

- Ubuntu Linux
- Nginx
- HTML
- WSL2

### Nginx Configuration

Nginx was installed using:

sudo apt install nginx -y

Nginx was configured with a server block for:

codsoft.local

The website is served on:

http://codsoft.local:8081

### Website Files

- index.html - Main static website
- 404.html - Custom 404 error page

### Testing

The Nginx configuration was validated using:

sudo nginx -t

The website was tested successfully with HTTP 200 response.

The custom error page was tested using a non-existent URL and returned HTTP 404 with the custom error page.

### Result

The static website was successfully deployed using Nginx on Ubuntu Linux. The virtual host and custom 404 error page were configured and verified successfully through a web browser.