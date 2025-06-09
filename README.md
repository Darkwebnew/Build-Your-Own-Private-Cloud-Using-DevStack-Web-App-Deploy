# Build Your Own Private Cloud Using DevStack + Web App Deploy

---

## Team Registration

| Role                | Reg. No          | Name       | Responsibility                   |
|---------------------|------------------|------------|---------------------------------|
| Team Lead           | 212222103002     | Sriram V   | Team Lead / Implementation      |
| Cloud Configuration | 212224220106     | Sriram E   | Cloud Configuration / Deployment|
| Web App Development | [Your Reg No]    | Harish D   | Web App Development / Testing   |
| Documentation       | 212222103003     | Surothaman | Documentation / Planning        |
| Networking Setup    | [Your Reg No]    | Baradhan   | Networking / Infrastructure Setup|

---

## Project Title

**Build Your Own Private Cloud Using DevStack + Web App Deploy**

---

## Problem Statement

Design and implement a private cloud infrastructure using **DevStack** (an OpenStack development environment) to simulate real-world cloud features. Deploy a web application on the private cloud to demonstrate resource provisioning, management, and scalability within a controlled, self-hosted environment.

---

## Hardware & Software Requirements

### Hardware Requirements

| Component    | Specification                          |
|--------------|--------------------------------------|
| Host System  | CPU: Intel i5 / AMD Ryzen 5 or better (Quad-Core) |
|              | RAM: 16 GB minimum                    |
|              | Storage: 200 GB SSD                   |
|              | Network: Stable internet (100 Mbps+) |
| Client System| CPU: Dual-Core                       |
|              | RAM: 4 GB                           |
|              | Browser: Latest Chrome/Firefox/Edge  |

### Software Requirements

| Component         | Software Options                           |
|-------------------|--------------------------------------------|
| Private Cloud     | DevStack (OpenStack), Ubuntu 20.04/22.04 LTS |
| Web App Backend  | Python Flask / Node.js                      |
| Web App Frontend | React.js / HTML + CSS + JavaScript          |
| Database         | PostgreSQL / MySQL                          |
| Deployment Tools | Docker (optional), Git (GitHub)             |
| Web Server       | Apache / Nginx                             |
| Monitoring Tools | OpenStack Horizon Dashboard, Prometheus + Grafana (optional) |

---

## Platform / Tools

- **DevStack (OpenStack variant):** To simulate and manage cloud infrastructure.
- **Ubuntu OS:** Base OS for installing DevStack.
- **React.js / Flask / Node.js:** For web app development.
- **Git / GitHub:** Version control and collaboration.
- **OpenStack Horizon:** GUI for private cloud resource management.
- **Docker:** For containerizing the web app (optional).
- **SSH / SCP / CLI Tools:** For cloud instance management.

---

## Project Schedule

| Phase                 | Tasks                                             | Timeline   |
|-----------------------|--------------------------------------------------|------------|
| 1. Requirements Gathering | Define project scope, finalize software stack     | Week 1     |
| 2. DevStack Setup        | Install and configure DevStack on Ubuntu           | Week 2     |
| 3. Web App Development   | Build basic web app with backend + frontend         | Weeks 3-4  |
| 4. App Deployment        | Deploy web app on virtual instance inside DevStack  | Week 5     |
| 5. Integration Testing   | Ensure the app runs seamlessly on private cloud     | Week 6     |
| 6. Monitoring & Scaling  | Set up monitoring (optional), simulate scalability  | Week 7     |
| 7. Documentation        | Prepare report, installation guide, and user manual | Week 8     |
| 8. Final Demo           | Present deployment, functionalities, and team contributions | Week 9     |

---

## System Architecture Diagram

![image](https://github.com/user-attachments/assets/3ed9ae77-8c3e-45be-ae16-44ab9b29772a)

---

## DevStack Installation & Configuration

- Installed **Ubuntu 22.04 LTS** on host system.
- Downloaded and configured **DevStack** environment.
- Configured OpenStack core services such as **Nova** (compute), **Neutron** (networking), **Glance** (image), **Keystone** (identity).
- Launched virtual instances to verify cloud environment.

---

## Web Application Overview

- Backend built with **Python Flask**, providing REST APIs for application logic.
- Frontend developed in **React.js** to create interactive user interfaces.
- Data persisted in **PostgreSQL** database.
- Application deployed inside DevStack VM to demonstrate cloud-based deployment.

---

## Deployment & Monitoring

- Web app deployed on private cloud VM using **Apache** web server.
- Configured **OpenStack Horizon Dashboard** to monitor and manage cloud resources.
- (Optional) Implemented resource monitoring with **Prometheus** and visualization via **Grafana**.

---

## Performance Analysis & Monitoring

### VM Resource Utilization Over Time

![image](https://github.com/user-attachments/assets/e43ce628-75d4-4a9c-95e7-610528637bcc)

- Initial CPU usage spikes during VM boot and app deployment.
- Stable usage observed during steady app operation.
- RAM utilization remains within allocated limits ensuring efficient resource management.

### Network Traffic Monitoring

![image](https://github.com/user-attachments/assets/dd839c51-8395-4bd7-b309-ee301d489c80)

- Shows inbound/outbound data packets per second.
- Confirms efficient network bandwidth usage during peak requests.

### Cloud Resource Allocation Breakdown

| Resource Type | Percentage Allocated |
|---------------|---------------------|
| Compute (CPU) | 40%                 |
| Memory (RAM)  | 35%                 |
| Storage       | 15%                 |
| Network       | 10%                 |

![image](https://github.com/user-attachments/assets/393589e7-3fc3-45c8-a727-5f7c145607ce)

---

## Scalability Testing

Simulated scaling of VMs using OpenStack’s compute scaling features. Increased VM instances from 1 to 5 to handle higher load.

| Number of VMs | Average Response Time (ms) |
|---------------|----------------------------|
| 1             | 450                        |
| 3             | 220                        |
| 5             | 150                        |

---

## Challenges & Solutions

| Challenge                      | Solution                                   |
|-------------------------------|--------------------------------------------|
| DevStack installation errors  | Followed official documentation, resolved dependency conflicts by updating packages |
| Network configuration issues  | Used OpenStack Neutron for flexible networking; set up VLAN segmentation |
| Web app deployment delays     | Containerized app using Docker to speed deployment and ensure consistency |
| Monitoring tool integration   | Configured Prometheus exporters and Grafana dashboards carefully to avoid resource overload |

---

## Conclusion

This project successfully implemented a private cloud infrastructure using DevStack and demonstrated web application deployment on the cloud environment. The project provided practical experience in cloud resource provisioning, management, and application scalability, validating the capability of private cloud solutions for controlled environments.

---

## References

1. [OpenStack DevStack Documentation](https://docs.openstack.org/devstack/latest/)
2. [Flask Web Framework](https://flask.palletsprojects.com/)
3. [React.js Official Site](https://reactjs.org/)
4. [PostgreSQL Documentation](https://www.postgresql.org/docs/)
5. [OpenStack Horizon](https://docs.openstack.org/horizon/latest/)
6. [Docker Documentation](https://docs.docker.com/)
7. [Prometheus](https://prometheus.io/)
8. [Grafana](https://grafana.com/)

---

*Report prepared by Team 6 – DEPARTMENT OF SCOFT*
