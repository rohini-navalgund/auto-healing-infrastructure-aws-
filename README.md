# ☁️ AWS Auto-Healing Infrastructure — DevOps Monitoring & Automated Self-Recovery System

##  Project Overview

This project demonstrates a **production-grade DevOps implementation** of automated monitoring and self-healing cloud infrastructure using AWS services.

The system continuously monitors the health of an EC2 instance and automatically triggers recovery actions when failures are detected. Real-time alerts are sent to administrators, ensuring high availability, reliability, and operational resilience of cloud resources.

This project simulates how modern DevOps and Site Reliability Engineering (SRE) teams maintain fault-tolerant infrastructure in real-world production environments.

---

##  Architecture

![Architecture Diagram](architecture1.png)

---

## ☁️ AWS Services Used

- **Amazon EC2** — Virtual server hosting the application
- **Amazon CloudWatch** — Monitoring metrics and alarm triggering
- **Amazon SNS** — Email notifications and alert delivery
- **AWS Lambda** — Automation logic for alert processing
- **IAM** — Secure role-based access control and permissions

---

## ✨ Key Features

✅ Real-time infrastructure monitoring  
✅ Automated failure detection  
✅ Self-healing (automatic EC2 recovery)  
✅ Email alert notifications  
✅ Health status validation  
✅ Production-style DevOps workflow  

---

## 🔄 How It Works

1. EC2 instance runs a web server workload.
2. CloudWatch continuously monitors instance health metrics.
3. When abnormal behavior or failure occurs:
   - CloudWatch alarm is triggered.
   - EC2 auto-recovery action executes automatically.
   - Notification is sent via SNS email.
4. The instance returns to a healthy state without manual intervention.

---

## 📸 Project Screenshots

### EC2 Instance Running
![EC2](screenshots/ec2-running.png)

### CloudWatch Alarm Configuration
![Alarm](screenshots/alarm-config.png)

### SNS Email Notification
![Email](screenshots/email-notification.png)

### SNS Subscription Confirmation
![SNS](screenshots/sns-subscription.png)

### CPU Utilization Spike Simulation
![CPU](screenshots/cpu-spike.png)

### CloudWatch Alarm Triggered
![Alarm Triggered](screenshots/alarm-triggered.png)

---

## 🧪 Failure Simulation

Failures were intentionally simulated to validate the self-healing system:

- High CPU load generation
- Manual instance reboot scenarios
- Alarm threshold triggering

The system successfully detected failures and performed automated recovery without human intervention.

---

## 🎯 DevOps & SRE Concepts Demonstrated

- Infrastructure Monitoring & Observability
- Incident Detection & Alerting
- Automated Recovery & Self-Healing Systems
- Cloud Automation
- Reliability Engineering (SRE Principles)
- Production Operations Workflow
- Event-Driven Architecture

---

## 📈 Learning Outcomes

- Hands-on experience with AWS production infrastructure
- Understanding monitoring and alerting systems
- Implementation of automated recovery mechanisms
- Practical DevOps automation knowledge
- Real-world incident response workflow design

---

## 🚀 Future Improvements

- Infrastructure as Code (Terraform / CloudFormation)
- Auto Scaling Group integration
- CI/CD pipeline automation
- Containerization using Docker
- Centralized logging with CloudWatch Logs
- Multi-AZ high availability architecture

---

## 👩‍💻 Author

**Rohini Navalagund**  
Cloud & DevOps Enthusiast

---

## 📜 License

This project is for educational and demonstration purposes.
