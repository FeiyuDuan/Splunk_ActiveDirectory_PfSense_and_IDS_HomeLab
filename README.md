# Splunk_ActiveDirectory_PfSense_and_IDS_HomeLab
The lab environment simulates a SOC where real-time monitoring and response to security incidents take place. The combination of PfSense(Firewall), Active Directory, Splunk, and Security Onion(IDS) creates a comprehensive framework for managing and securing IT infrastructure.

---

## **Project Overview**

1. **Active Directory Setup**: Configuring a Windows Server, creating domain users, and joining a Windows 10 client to the domain.
2. **Log Analysis with Splunk**: Integrating Splunk to collect and analyze logs from multiple sources, including servers and Kali Linux.
3. **Red Team Testing with Kali Linux**: Simulating attack scenarios and generating telemetry data that will be analyzed using Splunk.
4. **Intrusion Detection with Security Onion**: Continuously monitoring network traffic and analyzing responses to simulated attack vectors for threat detection and prevention.

---

## **Lab Specifications**

- **PfSense Firewall**: Securing the network with pfSense-CE
- **Splunk**: Using the free version for log collection and analysis
- **Kali Linux**: For red team activities
- **Security Onion**: Network monitoring and IDS

---

## **Host System Specifications**

- **CPU**: AMD Ryzen™ 7 5800X  
- **RAM**: DDR4 64GB  
- **Storage**: 1TB NVMe SSD (WD_Black SN750)  
- **Operating System**: Windows 11 Pro  
- **Virtualization Software**: VMware Workstation 17 Pro  

---

## **Project Steps**

### **1. Building the Network Diagram**
Plan and create a detailed network diagram outlining the connections between Active Directory, Splunk, Kali Linux, Security Onion, and PfSense. This ensures a clear understanding of how each component interacts within the environment.

### **2. Downloading and Installing Software**
Download and install the necessary software, including Windows Server, Splunk, Kali Linux, PfSense, and Security Onion. Set up the virtual machines in VMware to prepare the lab environment for testing and monitoring.

### **3. PfSense Configuration**
Configure PfSense as a firewall to manage and secure network traffic between the different subnets in the lab. It plays a key role in protecting the network and controlling access.

### **4. Configuring Ubuntu Server and Splunk**
Install and configure Splunk on Ubuntu Server. Set it up to collect and analyze logs from different components in the environment, ensuring efficient data ingestion for security analysis.

### **5. Active Directory Setup**
Install and configure Active Directory on Windows Server. Create users, set up domain management, and join the Windows 10 client to the domain for a fully functioning directory service.

### **6. Kali Linux Red Team Operations**
Use Kali Linux to conduct red team activities, such as simulating brute force attacks. Capture and analyze logs to gain insights into potential vulnerabilities and telemetry from these attacks.

### **7. Intrusion Detection with Security Onion**
Deploy Security Onion to monitor network traffic and detect intrusions. Analyze responses to simulated attacks and collect data for further investigation, enhancing the overall security posture of the environment.

---
