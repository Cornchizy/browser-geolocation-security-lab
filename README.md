# Browser Geolocation and Location Privacy Security Lab

## Overview

This project documents a controlled cybersecurity lab exploring how browser-based geolocation works, how websites request location permissions, and the difference between precise device location and approximate IP-based location.

The lab was performed for educational purposes using authorized systems and a self-owned test device.

## Objectives

- Understand how browser geolocation works
- Observe browser location permission requests
- Test location permission behavior
- Understand the difference between browser geolocation and IP geolocation
- Learn about GPS, Wi-Fi positioning, and cell-tower positioning
- Practice using Kali Linux in a controlled cybersecurity lab
- Understand tunneling concepts using Cloudflared
- Document privacy and security risks related to location sharing

## Lab Environment

- Kali Linux
- Oracle VirtualBox
- Seeker
- Cloudflared
- Web Browser
- Self-owned test device
- Local test environment

## Technologies and Concepts

- Linux
- Kali Linux
- Browser Geolocation
- GPS Location
- IP Geolocation
- Wi-Fi Positioning
- Cell-Tower Positioning
- Cloudflared Tunneling
- Web Server Concepts
- Location Privacy
- Social Engineering Awareness

## Key Findings

Browser geolocation requires user permission before a website can access precise location information through the browser's geolocation feature.

IP-based geolocation is different because it estimates location from an internet connection's public IP address. This can provide an approximate location without providing precise GPS coordinates.

Device location can also be determined using multiple technologies, including GPS satellites, nearby Wi-Fi networks, and cell towers. The accuracy depends on the technology and the surrounding environment.

Cloudflared was used in the controlled lab environment to demonstrate how a locally hosted service can be accessed through a secure tunnel for authorized testing.

## Ethical Scope

All testing documented in this project was performed in a controlled and authorized environment using systems, devices, and accounts owned or controlled by the researcher.

No unauthorized tracking, data collection, or testing against third parties was performed.

## Skills Demonstrated

- Linux command-line usage
- Kali Linux
- Cybersecurity lab setup
- Browser permission analysis
- Location technology fundamentals
- Cloud tunneling concepts
- Security and privacy analysis
- Technical documentation
- Ethical cybersecurity practices

## Screenshots

Screenshots from the controlled lab environment are available in the `screenshots` folder.

Sensitive information, personal data, public tunnel URLs, precise location coordinates, and credentials have been removed or redacted.

## Project Structure

```text
browser-geolocation-security-lab/
│
├── README.md
│
├── screenshots/
│   ├── 01-kali-environment.png
│   ├── 02-seeker-menu.png
│   ├── 03-local-server-running.png
│   ├── 04-cloudflared-tunnel-running.png
│   ├── 05-location-permission.png
│   ├── 06-option-6-recaptcha.png
│   └── 07-option-7-custom-preview.png
│
├── notes/
│   └── findings.md
│
└── report/
    └── lab-report.md
