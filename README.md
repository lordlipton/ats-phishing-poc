# ATS Name Field PoC

## Overview
This repository contains a proof-of-concept (PoC) HTML file that demonstrates a security vulnerability in Applicant Tracking Systems (ATS) where the applicant's name field is unsanitized. In real-world systems, unsanitized input could be used to inject malicious content into automated emails. This PoC is **safe and educational** and does not send any emails or collect data.

## Purpose
- Illustrate how user-supplied input can be reflected in automated emails.
- Provide a visual example for security awareness and educational purposes.
- Help developers understand why server-side sanitization is critical in ATS platforms.

## File
- `index.html` – a simple HTML form simulating a career portal. Whatever is entered in the "Name" field is reflected directly into a simulated email output.

## Usage
1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. Enter any value into the "Name" field.
4. Observe how the input appears in the simulated email section below the form.

**Note:** This PoC is for educational purposes only. Do **not** use it to attack live systems.

## Screenshots
*Add screenshots here to illustrate the form and the reflected input.*

## Disclaimer
This repository is strictly for educational and security awareness purposes. No data is collected, and no phishing attacks are performed. Always follow responsible disclosure practices when testing real systems.
