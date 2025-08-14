
Netdata System Monitoring with Docker

## Objective

- This project demonstrates how to set up Netdata using Docker to monitor system resources (CPU, Memory, Disk, Network) and application metrics in real-time.

## Tools Used

- Netdata – Open-source, real-time performance monitoring tool
- Docker – Containerization platform to run Netdata easily
- Linux Server / EC2 Instance – Environment for deployment

## Project Setup

1. Install Docker

- sudo yum update -y
- sudo yum install -y docker
- sudo systemctl start docker
- sudo systemctl enable docker

2. Run Netdata Container

- docker run -d --name=netdata -p 19999:19999 netdata/netdata

3. Access Netdata Dashboard

- Open browser and go to:

- http://<your-server-ip>:19999

Example:

- http://3.110.45.67:19999

4. Screenshot

* Netdata Dashboard *

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/783cec40-0dd8-4394-813b-ae30a0b8c967" />

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/c26c6c12-932a-49d3-9b1a-a7c0a401ad05" />

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/1091fc36-fb38-437d-8bca-b9a91893e770" />

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/5894258b-9a77-494d-8be7-481de98c3d8c" />

* Docker logs *

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/2825140c-458e-4c77-a826-2b5387906013" />

* Docker container (Netdata) *

<img width="940" height="219" alt="image" src="https://github.com/user-attachments/assets/10e33a24-0277-4341-a3c3-41ab4dc1e796" />


5. Features Monitored

- CPU usage
- Memory consumption
- Disk I/O
- Network traffic
- Docker container performance
- Alerts & notifications

6. Reference

- Netdata Official Docs: https://learn.netdata.cloud/docs

7. Outcome

By completing this project, you will:

- Understand real-time monitoring using Netdata
- Be able to deploy monitoring tools via Docker
- Learn how to visualize system performance for DevOps workflows




