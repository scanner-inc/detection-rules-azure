# Scanner Detection Rules - Azure

This repository contains Scanner detection rules for Azure.

### Examples

Here are a few examples of the detections that are included in this repository:
- Network Security Group Open to the World
- User Viewed CosmosDB Access Keys
- Firewall Threat Intelligence Alert

### Event Sinks

When these detection rules are triggered, alerts are sent to the [event
sinks](https://docs.scanner.dev/scanner/using-scanner/detection-rules/event-sinks)
you have configured in Scanner. Depending on the alert's severity level, it
will be sent to one of these event sink keys:
- `informational_severity_alerts`
- `low_severity_alerts`
- `medium_severity_alerts`
- `high_severity_alerts`
- `critical_severity_alerts`
- `fatal_severity_alerts`

### Deployment

To deploy these rules into your Scanner instance, you can follow the
instructions in the [Scanner documentation](https://docs.scanner.dev) under
**Detection Rules as Code**.
