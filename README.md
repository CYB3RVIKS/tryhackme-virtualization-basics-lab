# tryhackme-virtualization-basics-lab
# Virtualization Basics – Case Study & Lab Report

## Scenario Overview

I was assigned as a system administrator responsible for managing a virtual environment in a company that recently adopted virtualization technology.

The organization experienced a critical issue where **all employees stopped receiving emails**, and the root cause was unknown.

---

## Incident Investigation

Upon accessing the virtual infrastructure dashboard, I observed three main sections:

- Summary
- Virtual Machines (VMs)
- Host systems

### Key Finding:
The VM named **Mail-Server** was in an **error state**, which was likely responsible for the email outage.

### Resolution:
I restarted the Mail-Server VM, and it successfully returned to a running state with no errors. Email services were restored.

---

## Additional Task – VM Deployment

After resolving the issue, I was assigned to create a new virtual machine for the marketing team’s website.

### Configuration used:
- CPU: 4 Cores  
- Memory: 8GB RAM  
- Storage: 100GB Disk  

The VM was successfully deployed and configured for use.

---

## Infrastructure Monitoring Task

I was also tasked with monitoring the health of physical servers (hypervisors) and reporting their status.

### Observations:

- **HV-PROD-01**: Hosting 3 VMs, with available capacity for more workloads  
- **HV-PROD-02**: Hosting 8 VMs and operating at nearly 100% capacity (requires attention)  
- **HV-PROD-03**: Disconnected and hosting no virtual machines

---

## Final Assessment

I completed all assigned tasks and successfully answered all evaluation questions.

---

## Key Takeaways

- Virtual machines can directly impact critical business services like email systems
- Hypervisors must be actively monitored to avoid overload or downtime
- Resource allocation (CPU, RAM, storage) is essential for VM performance and stability
- Virtualization improves scalability but requires proper monitoring and management

---

## Conclusion

This lab helped me understand how virtualization is used in real-world IT environments to manage infrastructure, deploy services, and troubleshoot system failures.

I now have a clearer understanding of how virtual machines interact with hypervisors and how system administrators ensure service reliability in enterprise environments.

---

Learning in public 🚀
