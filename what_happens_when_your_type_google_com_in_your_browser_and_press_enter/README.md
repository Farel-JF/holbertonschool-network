# What Happens When You Type `https://www.google.com` in Your Browser and Press Enter

This project explores the steps that take place from the moment a user types `https://www.google.com` into their browser until the Google homepage is displayed. It delves into various components of the web stack and infrastructure, including DNS resolution, TCP/IP, firewalls, HTTPS/SSL encryption, load balancers, web servers, application servers, and databases.

## Table of Contents
1. [Overview](#overview)
2. [DNS Resolution](#dns-resolution)
3. [TCP/IP](#tcp-ip)
4. [Firewall](#firewall)
5. [HTTPS/SSL](#https-ssl)
6. [Load Balancer](#load-balancer)
7. [Web Server](#web-server)
8. [Application Server](#application-server)
9. [Database](#database)
10. [Diagram](#diagram)
11. [References](#references)

## Overview
When you type `https://www.google.com` into your browser and hit Enter, a complex series of actions take place behind the scenes to retrieve the requested web page. This blog post explains each of these steps, breaking down the journey of the request across the internet.

## DNS Resolution
The first step is DNS (Domain Name System) resolution, where the domain name (`www.google.com`) is translated into an IP address. This allows the browser to know which server to communicate with.

## TCP/IP
Once the IP address is found, the browser establishes a connection using the TCP/IP protocol. TCP ensures reliable transmission of data, while IP handles addressing and routing.

## Firewall
The request passes through firewalls, which act as security barriers between the client and server to protect from malicious traffic.

## HTTPS/SSL
HTTPS encrypts the communication between the browser and the server using SSL/TLS protocols, ensuring that sensitive data remains secure.

## Load Balancer
The request is routed to a load balancer, which distributes incoming traffic across multiple web servers to ensure availability and reliability.

## Web Server
The web server is responsible for handling the request and serving static files such as HTML, CSS, and JavaScript.

## Application Server
The web server often interacts with an application server that generates dynamic content by running backend code.

## Database
In many cases, the application server will query a database to retrieve data needed to generate the web page dynamically.

## Diagram
To further illustrate the flow of this request, the following diagram outlines the major steps involved in the process:

![Diagram URL here]

## References
- [Link to Blog Post](#)
- [Other useful references]

