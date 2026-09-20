# GoPhish Campaign Analysis

## Overview

This project documents a controlled phishing simulation conducted using GoPhish in a Kali Linux laboratory environment.

The project focuses on the configuration, execution, monitoring, and analysis of a simulated phishing campaign.

## Objectives

- Configure a controlled GoPhish phishing simulation
- Create and configure a simulated phishing email
- Configure a landing page
- Create a target group
- Execute the phishing campaign
- Monitor campaign activity
- Analyze campaign results
- Identify phishing indicators
- Document security awareness recommendations

## Lab Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Phishing Simulation Platform | GoPhish |
| Environment | Controlled Laboratory |
| Purpose | Phishing Simulation & Security Awareness |
| Virtualization Platform | Oracle VirtualBox |

### Lab Environment
The following screenshot shows the Kali Linux environment used during the project.

### Gophish Configuration

The phishing campaign was configured using the different components available within GoPhish. These components included the email template, landing page, target group, and campaign settings.

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/d72ffbe0-b09b-48da-a012-7864d2357a5c" />


<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/58b3ce49-d7c8-4110-bff4-b70d73efb548" />


Retrieved the auto-generated admin credentials from the terminal output and logged into the admin panel at [https://127.0.0.1:3333](https://127.0.0.1:3333/)


### Sending Profile

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/95c40861-d3d3-4222-aaf1-1c4e278dac43" />

### Landing Page

A landing page was configured in GoPhish as part of the simulated phishing campaign.
The landing page was used to record interaction with the simulated campaign and demonstrate how a phishing campaign can direct a user from an email to a web page.

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/ba75b51a-f9fb-49d1-8a55-b669fcd7c959" />

### Email Template

An email template was created in GoPhish for the phishing simulation. The template contained the message that was delivered to the authorized test recipient. The purpose of the template was to simulate a realistic phishing communication and observe how users interact with the simulated message.
<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/da78c8e6-4dbc-400b-8b0d-c90471ac8542" />

### Users & Groups

A target group was configured in GoPhish containing the authorized test recipient(s) used for the simulation.The target group allowed the campaign to identify the recipients to whom the simulated phishing email would be delivered.

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/5665fb00-0a55-4e90-852c-ed38c021e1e0" />

### Campaigns 

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/641a75e9-3387-449d-958e-430b9d47f734" />

### Campaign Monitoring

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/a5b3a41d-351e-4d5f-9a93-a13bf4ca00c5" />

### Results Analysis

<img width="1280" height="606" alt="Image" src="https://github.com/user-attachments/assets/4f3d9912-99f3-4991-82f0-7b36a5201243" />

### | Metric | Result |

Emails Sent: 3

Emails Delivered: 3

Emails Opened: 3

Links Clicked: 3

Landing Page Visits: 3

Data Submitted: 3

## Tools Used

- Kali Linux
- GoPhish
- Web Browser
- SMTP Service

## Project Workflow

```text
GoPhish Configuration
        ↓
Email Template
        ↓
Landing Page
        ↓
Target Group
        ↓
Campaign
        ↓
Campaign Monitoring
        ↓
Results Analysis

## Lessons Learned

This project provided practical experience in planning, configuring, executing, and analyzing a controlled phishing simulation using GoPhish and Kali Linux.

Key lessons learned include:

* Understanding the components required to conduct a phishing simulation.
* Configuring GoPhish campaign components such as sending profiles, email templates, landing pages, and target groups.
* Understanding how phishing campaigns can be monitored through user interaction and campaign metrics.
* Analyzing campaign results to identify potential security awareness gaps.
* Understanding common characteristics and indicators associated with phishing emails.
* Improving practical skills in cybersecurity documentation and evidence collection.
* Understanding the importance of conducting phishing simulations in a controlled and authorized environment.

## Conclusion

The GoPhish Campaign Analysis project provided hands-on experience with phishing simulation and campaign monitoring in a controlled laboratory environment.

The exercise demonstrated how GoPhish can be used to configure and monitor simulated phishing campaigns and analyze recipient interactions. The results and observations from the simulation were documented as part of the security analysis process.

Overall, the project strengthened practical knowledge of phishing awareness, email security, campaign analysis, and cybersecurity documentation.

## Ethical and Security Considerations

This project was conducted strictly for educational and cybersecurity training purposes in a controlled environment.

All simulated phishing activities were performed against authorized test accounts and systems. No unauthorized individuals, organizations, or systems were targeted.

The techniques demonstrated in this project should only be used with appropriate authorization and within legally permitted environments.


