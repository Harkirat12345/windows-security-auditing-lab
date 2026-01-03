# Windows Security Auditing Lab

## Overview
This project demonstrates host-based security monitoring using Windows Event Viewer.
Advanced audit policies were configured to capture authentication activity and process creation events.

## Objectives
- Enable Windows Advanced Audit Policies
- Generate authentication success and failure events
- Monitor process creation activity
- Filter and analyze security logs using Event Viewer

## Audit Policies Configured
- Logon/Logoff: Success and Failure
- Detailed Tracking: Process Creation (Success)

## Event IDs Analyzed
- **4624** – Successful logon
- **4625** – Failed logon attempt
- **4688** – Process creation

## Tools Used
- Windows Event Viewer
- Local Security Policy
- Windows 10/11 Virtual Machine

## Results
- Analyzed **800+ Windows Security events**
- Investigated authentication failures and successful logons
- Reviewed parent-child process relationships for executed processes

## Screenshots
Screenshots documenting audit configuration and event analysis are included in this repository. The screenshots will reflect chronological order of steps taken. 
