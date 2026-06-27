# Day 03 - Understanding How the Internet & Applications Work

## Objective

To understand how the internet works, how users access applications, the role of servers, and the difference between web servers and application servers. These concepts form the foundation of Cloud Computing and DevOps.

---

# How the Internet Works

The Internet is a global network of interconnected computers that communicate using standard protocols such as **TCP/IP**.

When a user opens a website, several steps happen behind the scenes:

1. The user enters a website URL.
2. The browser sends a request over the internet.
3. DNS translates the domain name into an IP address.
4. The request reaches the web server.
5. The web server or application server processes the request.
6. A response is returned to the browser.
7. The webpage is displayed to the user.

### Basic Request Flow

```text
User
   │
   ▼
Browser
   │
   ▼
Internet
   │
   ▼
DNS
   │
   ▼
Web Server
   │
   ▼
Application Server
   │
   ▼
Database
   │
   ▼
Response Returned to Browser
```

---

# What is a Server?

A **server** is a computer or software system that provides services, resources, or data to other computers known as **clients**.

Examples include:

* Web Server
* Database Server
* Mail Server
* File Server
* Application Server

### Responsibilities of a Server

* Process client requests
* Store and retrieve data
* Run applications
* Provide security
* Handle multiple users simultaneously

---

# Web Server

A **Web Server** delivers static content to users.

Examples of static content include:

* HTML pages
* CSS files
* JavaScript files
* Images
* Videos

### Popular Web Servers

* Apache HTTP Server
* Nginx
* Microsoft IIS

### Responsibilities

* Accept HTTP/HTTPS requests
* Serve static files
* Forward dynamic requests to an application server

---

# Application Server

An **Application Server** executes business logic and processes dynamic user requests.

Unlike a web server, it can:

* Run application code
* Authenticate users
* Communicate with databases
* Process transactions
* Generate dynamic content

### Examples

* Apache Tomcat
* JBoss
* WildFly
* GlassFish

---

# Web Server vs Application Server

| Web Server                        | Application Server        |
| --------------------------------- | ------------------------- |
| Serves static content             | Processes business logic  |
| Faster for simple requests        | Handles dynamic requests  |
| Doesn't directly access databases | Interacts with databases  |
| Handles HTTP requests             | Executes application code |

---

# Types of Applications

## Standalone Applications

Applications installed directly on a user's device.

Examples:

* VLC Media Player
* Microsoft Word
* Notepad
* Calculator

### Characteristics

* Works without internet (in many cases)
* Installed locally
* Uses local system resources

---

## Web Applications

Applications accessed through a web browser.

Examples:

* Gmail
* Facebook
* Amazon
* ChatGPT
* YouTube

### Characteristics

* Accessible from anywhere
* Requires internet connection
* Runs on remote servers
* Easy to update and maintain

---

# Application Support

Application Support ensures that applications continue to operate correctly after deployment.

Common tasks include:

* Monitoring applications
* Resolving user issues
* Performance optimization
* Security monitoring
* Backup management

---

# Application Maintenance

Application Maintenance involves improving software after deployment.

Types include:

* Bug fixing
* Feature enhancements
* Security updates
* Performance improvements
* Compatibility updates

---

# Why This Matters in Cloud Computing

Cloud providers host applications on virtual servers.

Understanding application architecture helps Cloud Engineers and DevOps Engineers:

* Deploy applications efficiently
* Scale applications based on demand
* Monitor application health
* Improve reliability
* Troubleshoot production issues

---

# Key Learnings

* The Internet connects millions of devices worldwide.
* Servers provide resources and services to clients.
* Web Servers mainly serve static content.
* Application Servers process dynamic requests and business logic.
* Standalone applications run locally on a device.
* Web applications run on remote servers and are accessed through browsers.
* Application Support and Maintenance ensure software remains reliable and secure.

---

# Hands-On Understanding

Today I explored:

* Internet request flow
* Server architecture
* Web Server vs Application Server
* Types of applications
* Role of servers in Cloud Computing
* Application Support concepts
* Application Maintenance lifecycle

---

# Day 03 Summary

Today strengthened my understanding of how applications work behind the scenes before they are deployed to the cloud. Learning the interaction between users, browsers, servers, and databases provides a strong foundation for future Cloud Computing and DevOps topics such as Linux, Networking, Docker, Kubernetes, and AWS.

**Status:** ✅ Day 03 Completed
