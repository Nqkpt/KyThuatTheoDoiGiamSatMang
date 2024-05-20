Project: DoS Attack Analysis with Splunk

 Objectives: 
- To detect and analyze DoS attacks using Splunk.
- To configure Splunk alerts for real-time attack detection.
- To implement and test defense measures against DoS attacks.

 Role: Splunk Configuration, DoS Attack Simulation, Monitoring 

 Description: 

 Configuring Rules in Splunk: 
-  Add Alert Rule: 
  - Navigate to Settings → Searches, Reports, and Alerts → New Alert.
  - Configure the alert with:
    -  Title:  Name of the alert
    -  Permissions:  Set alert permissions
    -  Alert Type:  Real-time (triggers when an event is detected)
    -  Trigger Conditions:  Alert if more than 50 events occur per minute

 DoS Attack Simulation: 
-  Scenario: 
  - Create a login page and perform a Brute Force attack to cause a DoS condition.
-  Preparation: 
  -  Environment:  Apache2, MySQL
  -  Attack Tool:  Burp Suite
  -  Monitoring Tool:  Splunk
-  Execution: 
  - Use Burp Suite to perform a Brute Force attack on the login page.

 Monitoring and Analysis: 
-  Event Monitoring: 
  - Capture and display all events in Splunk.
-  Anomaly Detection: 
  - Visualize abnormal request volumes over time.
-  Alerting: 
  - Splunk triggers an alert, indicating a DoS attack on the website.
