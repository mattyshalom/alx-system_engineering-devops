Postmortem: Service Outage - INTERNET SERVICE OUTAGE

Issue Summary:

Duration: May 15, 2023, 1:15 AM - May 15, 2023, 09:30 AM (WAT)

Impact: There was an outage from our uplink provider, resulting in service disruption for approximately 80% of the users.

Timeline:

1:15 AM: The issue was detected through our automated monitoring software(PRTG) which beeps an error alert and red indicator on the screen to show there's an outage from the links being monitored.

Actions taken: The NOC team immediately started investigating the issue by checking on the SFP port to see if it was a port freeze, and changing the patch cord as the troubleshooting continues but things seem to be the same. 

They further the investigation by running a traceroute on the network path, which later indicates multiple fiber cuts along the points of connections from our provider down to the office. As the cause of the outage was detected, we switch to our backup link while we proceed with proferring solutions to the main link.

Misleading investigation/debugging paths: Initially, the focus was based on the connections within the server room, leading to a thorough examination of the patch cords and the ports.

Escalation: The incident was escalated to the engineering team to investigate the possible cause of the multiple cuts on the fiber joints as detected by our OTDR trace machine.

At 7:00 AM: Collaborative efforts between the engineering team at our end and that of our upstream provider in tracing the fiber path revealed that the issue was a result of a fire outbreak along the path of our cable.

Resolution: The burnt cables were replaced and laid underground to prevent future occurrences.
At 09:30 AM: the link was restored.





Corrective and Preventative Measures:

Routine cable check: An engineer was engaged with the responsibility of regular checking on all the network paths to ensure all observable or potential damage is fixed and corrected to avoid unnecessary network downtime.

Enhance Monitoring: Strengthen monitoring capabilities to proactively detect loss of signal and receive alerts in real time.

Scheduling regular system maintenance: making sure systems are checked to ensure performance is optimal and confirming signals are at their best.

TODO:

Conducting regular checks on the server and router ensuring all necessary LED signals are up.

Testing of the backup link in other to confirm they are intact should in case of emergency switchover.

Ensuring Monitoring systems are performing at optimal in detecting performance issues promptly.

Monitoring and taking records of the optical power level in other to detect a rise in power value.


By OLUSEGUN SUNDAY.(olusegesunday@yahoo.com)

