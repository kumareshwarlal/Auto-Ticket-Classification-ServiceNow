# Project Design

## System Design

The system is designed using ServiceNow Flow Designer to automatically classify IT tickets based on the Short Description.

## Flow Design

### Trigger
Incident Workflow record is created where Category is NULL.

### Classification Logic

- Wi-Fi / Network → Category: Network, Subcategory: Wi-Fi
- Projector / Hardware → Category: Hardware, Subcategory: Projector
- Forgot Password → Category: Access, Subcategory: Forgot Password
- Performance issue → Category: Performance

### Notification

After ticket processing, an automated email notification is sent to the caller confirming that the IT ticket has been submitted.

## Technology Used

- ServiceNow
- Flow Designer
- Update Sets
