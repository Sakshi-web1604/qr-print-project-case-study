# qr-print-project-case-study
Documentation and product case study of a browser-based Linux printing and scanning application.
# QR Print – Mobile-to-HP Direct Print Gateway

## Project Overview

QR Print is a browser-based printing and scanning application developed as part of a team internship project at Mphasis.

The application was designed to simplify access to Linux-based printing and scanning functionality by allowing users on the same local network to access a web interface through a QR code.

## Problem Statement

Traditional Linux printing and scanning workflows can require users to interact with command-line utilities and configure devices manually. QR Print aimed to make these operations more accessible through a unified browser-based interface.

## Key Capabilities

- QR-code-based access over a local network
- Printer and scanner discovery
- Support for USB and network-connected devices
- Document uploads and print initiation
- Document scanning and downloadable outputs
- Conversion of supported document formats into PDF

## Technology Stack

- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Python, Flask REST APIs
- **Printing:** CUPS, HPLIP
- **Scanning:** SANE
- **Network discovery:** Zeroconf / mDNS
- **Document processing:** LibreOffice, Pillow

## My Project Experience

This was a collaborative engineering internship project. My experience involved working within a team developing a browser-based solution that integrates frontend functionality, backend APIs and Linux printing/scanning utilities.

This repository presents a retrospective case study of the project, focusing on its user problem, solution, functionality, technology architecture and potential product improvements.

## Project Documentation

- Case study presentation: `QR_Print_Case_Study.pdf`
- Application screenshots: `screenshots/`
- Workflow and architecture diagrams: `diagrams/`

## Potential Future Improvements

- User authentication and access control
- Improved device-discovery and connectivity feedback
- More detailed error handling
- Device compatibility improvements
- Print-job status and monitoring

## Important Note

This repository contains documentation and portfolio material only. The original internship source code is not included because it was not retained and may be subject to confidentiality restrictions. This is a team project, and the repository does not claim ownership of the original implementation.
