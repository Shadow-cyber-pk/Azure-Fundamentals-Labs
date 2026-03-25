# Azure Fundamentals: Compute & Networking Lab (AZ-900)

## 🎯 Objective
To demonstrate proficiency in deploying and securing cloud infrastructure using Microsoft Azure's Core Architectural components.

## 🛠️ Infrastructure Deployed
* **Resource Group:** Logical container for lifecycle management.
* **Linux VM (Ubuntu):** IaaS compute instance for hosting services.
* **Virtual Network (VNet):** Configured subnets and IP addressing.
* **NGINX Web Server:** Installed via terminal to handle HTTP requests.

## 🛡️ Security Configuration (NSG)
I implemented a **Network Security Group (NSG)** to act as a stateful firewall with the following rules:
* **Inbound Rule (Port 22):** Allowed SSH for remote administrative access.
* **Inbound Rule (Port 80):** Allowed HTTP traffic to serve web content to the public internet.

## 🧠 Key Takeaway
This exercise solidified my understanding of **Inbound Security Rules** and how to bridge the gap between a private virtual network and the public internet.

## Scrennshots showing my Azure Resource group, Resources and the NGINX web serer

### Resource Group
![image](https://github.com/Shadow-cyber-pk/pfsense-Multi-subnet-Lab/blob/3842beda94561b412771b99e467ab33367da41fc/images/Screenshot%202026-03-25%20094608.png)

### Resources
![Image](https://github.com/Shadow-cyber-pk/pfsense-Multi-subnet-Lab/blob/3842beda94561b412771b99e467ab33367da41fc/images/Screenshot%202026-03-25%20094632.png)

### NGINX website
![Image](https://github.com/Shadow-cyber-pk/pfsense-Multi-subnet-Lab/blob/3842beda94561b412771b99e467ab33367da41fc/images/Screenshot%202026-03-25%20094645.png)
