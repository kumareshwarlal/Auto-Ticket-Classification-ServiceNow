# Auto Ticket Classification using ServiceNow Flow Designer

## Project Description

This project implements an automated IT ticket classification system
using ServiceNow Flow Designer.

## Features

- Automatic ticket classification
- Wi-Fi/Network issue classification
- Projector/Hardware issue classification
- Forgot Password/Access issue classification
- Slow Computer/Performance issue classification
- Automatic category and subcategory updates
- Automated email notification to the caller

## Technology Used

- ServiceNow
- Flow Designer
- Update Sets

## Flow

Trigger:
Incident Workflow Created where Category is NULL

Classification:
- Wi-Fi / Network → Network / Wi-Fi
- Projector → Hardware / Projector
- Forgot Password → Access / Forgot Password
- Slow Computer → Performance / Slow Computer

## Testing

The flow was tested using Incident Workflow records and the
email notification was verified successfully.

## Update Set

The completed ServiceNow Update Set is included as an XML file
in this repository.
