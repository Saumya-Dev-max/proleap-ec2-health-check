# ProLEAP EC2 Health Check Project
## Objective
This project performs automated health checks on an Ubuntu AWS EC2 web server.
## AWS Services Used
- EC2i
- Security Groups
- IAM

- VPC networking
## Technologies Used
- Ubuntu Linux
- Bash
- Nginx
- Git
- GitHub
## Checks Performed
- Server identity
- Operating system information
- System uptime
- CPU load
- Memory usage
- Disk usage
- Top processes
- Nginx service status
- Port 80 status
- Localhost website test
- Public website test
- Internet connectivity
- DNS resolution
## How to Run
```bash
chmod +x scripts/ec2-health-check.sh
bash scripts/ec2-health-check.sh
## EC2 Deployment Checklist
- EC2 instance is running
- SSH is restricted to My IP
- HTTP port 80 is open
- Nginx service is active
- Custom website is deployed
- Health check script is executable
- Health report is generated
