<p align="center"\>
<img src="https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/img/What%20happen%20when%20you%20type%20google%20(2).png"\>
</p>


---

# What Happens When You Type google.com in Your Browser

## 🌐 Project Overview

This project is a deep dive into the inner workings of the Internet. The goal is to explain in detail every step and technology involved when a user types a URL (specifically `https://www.google.com`) in their browser and presses **Enter**. This exercise assesses a Full-Stack Engineer's ability to understand and explain the communication between a client and a server across various infrastructure layers.

## 🎓 Learning Objectives

By completing this project, I have explored and documented the following concepts:

* **DNS Resolution**: How domain names are translated into IP addresses.
* **TCP/IP Stack**: The fundamental communication protocols of the Internet.
* **Security**: The role of Firewalls and the **HTTPS/SSL** handshake for encrypted communication.
* **Traffic Management**: How a **Load-balancer** distributes incoming requests.
* **Web Stack**: The interaction between the **Web Server**, **Application Server**, and **Database**.

## 📝 The Journey of a Request

The project is presented as a comprehensive blog post covering the following milestones:

1. **DNS Request**: The browser checks its cache, then the OS, then queries Recursive DNS servers to find the IP address of `google.com`.
2. **TCP/IP Connection**: A Three-way Handshake (SYN, SYN-ACK, ACK) is established to create a reliable connection.
3. **Firewall**: Traffic is inspected to ensure it complies with security rules before entering the server's network.
4. **HTTPS/SSL Handshake**: Encryption keys are exchanged to secure the data transfer.
5. **Load Balancer**: The request hits a load balancer which chooses the best server to handle the traffic.
6. **Web Server**: Software (like Nginx or Apache) receives the request and manages static content.
7. **Application Server**: The request is passed to the application server to handle dynamic logic.
8. **Database**: The application server queries the database to retrieve or store information.

## 📂 Repository Structure

| File | Description |
| --- | --- |
| `0-blog_post` | Contains the URL to the published blog post (Medium/LinkedIn). |
| `README.md` | This documentation file. |

## ✍️ Author

**Mathieu**

[Mathieu GODALIER](https://github.com/Mathieu7483) - Élève en programmation à la Holberton School

## 🙏 Acknowledgments

* **Holberton School**: For the "What Happens When" challenge.
* **Sylvain Kalache**: For the curriculum design.