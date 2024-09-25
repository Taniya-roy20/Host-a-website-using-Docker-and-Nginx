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
# HOW TO INSTALL DOCKER
To install Docker on a remote server using PuTTY, you'll first need to ensure you have access to a Linux server (like Ubuntu, CentOS, etc.) via SSH. Here's a step-by-step guide:

**Step 1: Connect to Your Server**
<br><br>
1.Open PuTTY.
<br>
2.Enter the hostname or IP address of your server.
<br>
3.Click "Open" to initiate the connection.
<br>
4.Log in with your username and password.
<br><br>
**Step 2: Update Your Package Index**
<br><br>
Before installing Docker, it’s a good idea to update the package index:

     sudo apt update
<br><br>
**Step 3: Install Prerequisites**
<br><br>
For Ubuntu, install the required packages:

      sudo apt install apt-transport-https ca-certificates curl software-properties-common
<br>
For CentOS, run:

       sudo yum install -y yum-utils
<br><br>
**Step 4: Add Docker’s Official GPG Key**
<br><br>
For Ubuntu:

        curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
<br><br>
For CentOS:

         sudo rpm --import https://download.docker.com/linux/centos/gpg
<br><br>
**Step 5: Set Up the Stable Repository**
<br><br>
For Ubuntu:

         sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
<br><br>
For CentOS:

          sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
<br><br>
**Step 6: Install Docker**
<br><br>
For Ubuntu:

                 sudo apt update
                 sudo apt install docker-ce
<br><br>
For CentOS:

                 sudo yum install docker-ce
<br><br>
**Step 7: Start Docker**
<br><br>
Enable and start the Docker service:

                 sudo systemctl start docker
                 sudo systemctl enable docker
<br><br> 
**Step 8: Verify the Installation**
<br><br>
Check if Docker is running:

                  sudo systemctl status docker
<br><br>
You can also run a test container:

                 sudo docker run hello-world
<br><br>
**Step 9: (Optional) Manage Docker as a Non-Root User**
<br><br>
If you want to run Docker commands without sudo, add your user to the Docker group:

                sudo usermod -aG docker $USER
<br><br>
After running this command, log out and back in for the changes to take effect 
















