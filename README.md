# Cisco Identity Services Lab 1

![Status](https://img.shields.io/badge/Status-Complete-success)
![Category](https://img.shields.io/badge/Category-Network%20Security-blue)
![Platform](https://img.shields.io/badge/Platform-Cisco%20Packet%20Tracer-blueviolet)
![Portfolio](https://img.shields.io/badge/Portfolio-LinkedIn-orange)

## Project Overview

This lab demonstrates the configuration of secure administrative access on Cisco network devices using local authentication, encrypted credentials, SSH version 2, login banners, and configuration verification.

The project was completed as part of a hands-on identity services and network security portfolio.

## Objectives

- Configure secure local user authentication
- Protect privileged access with an enable secret
- Configure SSH version 2
- Generate RSA encryption keys
- Restrict remote access to SSH
- Configure a security warning banner
- Verify device interfaces and connectivity
- Save and back up the device configuration
- Troubleshoot authentication and remote-access issues

## Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS
- SSH
- RSA encryption
- Local authentication
- Command-line interface
- GitHub
- Technical documentation

## Security Concepts Demonstrated

- Secure administrative access
- Authentication
- Authorization fundamentals
- Encrypted credentials
- Least privilege
- Login warning banners
- Configuration protection
- Secure remote management

## Key Configuration Tasks

1. Assigned hostnames and basic device settings
2. Created local administrator accounts
3. Configured encrypted privileged access
4. Defined domain information
5. Generated RSA keys
6. Enabled SSH version 2
7. Configured VTY lines for local authentication and SSH-only access
8. Added a message-of-the-day security banner
9. Verified interfaces and connectivity
10. Saved the running configuration

## Example Verification Commands

```text
show ip interface brief
show running-config
show ip ssh
show users
show startup-config
