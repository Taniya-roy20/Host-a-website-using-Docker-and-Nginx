# DOCKER
Docker is a platform that enables developers to create, deploy, and manage applications in lightweight containers. is a popular open source containerization tool used to provide a portable and consistent runtime environment for software applications, while consuming less resources than a traditional server or virtual machine. Docker uses containers, isolated user-space environments that run at the operating system level and share system resources such as the kernel and the filesystem.
<br>
<br>
Key features of Docker include:

**Containerization:** Applications run in isolated environments, which makes them portable and easy to manage.

**Images and Dockerfile:** Docker uses images as blueprints for containers. A Dockerfile is a script that contains instructions to build an image.

**Docker Hub:** A cloud-based registry where users can share and distribute Docker images.

**Orchestration:** Tools like Docker Compose and Kubernetes can manage multi-container applications and services.

Overall, Docker streamlines development workflows, improves resource utilization, and enhances application deployment speed.
![image](https://github.com/user-attachments/assets/180efde6-39b6-4834-9d12-451e1aa9d1b4)
<br>
<br>
# CONTAINERS
Containers are lightweight, portable units that package an application and all its dependencies, including libraries, configuration files, and runtime. They run in isolation from one another on the same operating system kernel, which makes them more efficient than traditional virtual machines.

Key characteristics of containers include:

**Isolation:** Each container operates independently, ensuring that applications do not interfere with each other.
<br>
**Portability:** Containers can run consistently across different environments, from a developer's laptop to production servers.
<br>
**Efficiency:** Containers share the host OS kernel, reducing overhead and improving resource utilization compared to virtual machines.
<br>
**Scalability:** Containers can be easily scaled up or down to handle varying workloads.
<br>
Overall, containers facilitate rapid development, testing, and deployment of applications, making them a cornerstone of modern DevOps practices.
<br>
<br>
# NGINX
NGINX is an open source web server used for serving static or dynamic websites, reverse proxying, load balancing, and other HTTP and proxy server capabilities. It was built to handle large amounts of concurrent connections, and is a popular web server used to host some of the largest and most high-traffic sites on the internet.
![image](https://github.com/user-attachments/assets/d5ae01a0-774f-4a84-8999-6e49c2fe3ca9)
<br>
<br>
Key features of NGINX include:

1.*Web Server:* It can serve static content (like HTML, CSS, and images) quickly and efficiently.

2.*Reverse Proxy:* NGINX can act as an intermediary for requests from clients seeking resources from other servers, distributing the load and improving performance.

3.*Load Balancing:* It can distribute incoming traffic across multiple servers to ensure availability and reliability.

4.*SSL/TLS Termination:* NGINX can handle SSL/TLS encryption, improving security while offloading the processing from backend servers.

5.*Caching:* It can cache content to reduce latency and improve response times.

6.*Support for WebSockets:* NGINX supports real-time communication for applications that require persistent connections.
![image](https://github.com/user-attachments/assets/1eb25173-363a-4251-87d7-28419734e994)
<br><br>
# Advantages of NGINX
![image](https://github.com/user-attachments/assets/361486c1-b572-4b52-9b9f-d3ed6df6e333)
<br>
# HOW TO INSTALL NGINX
In this tutorial, we’ll show you how to install NGINX on Linux. Open your Linux machine and run an update using the command below:
<br>
sudo apt-get update
<br>
<br>
Next, run this command:

sudo apt-get install nginx
<br><br>
Then, enable your firewall with the following:

sudo ufw enable
<br><br>
To verify NGINX is installed, run the following:

nginx -v
<br><br>
You can run the command below to find out if NGINX is running:

sudo ufw status
<br><br>
After running this command, you should see the following:

status: active
<br><br>
To check whether your NGINX server is working fine, run the following:

sudo systemctl status nginx
<br><br>
# Host a website using Docker and Nginx
1.Login to your AWS account and download your passkey and launch the EC2 instance.
<BR>
2.Launch PuTTY and add the IP address from instance and add key pair file and open the PuTTY terminal.
<BR>
3.Login to the OS by writing "ubuntu"
<BR>
4.After that I have to install docker in my OS .
<BR>
Now install Docker using following command:
<BR>
















