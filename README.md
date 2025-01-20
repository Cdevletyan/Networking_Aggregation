# Creating a DHCP Network
This is a small project of Network topology and how I aggregate my network logs into one central log-aggregate software.

# Tools used for this project:
- Packet Tracer

Configured This network using a simulated topology. Topology shown in diagram below;

![image](https://github.com/user-attachments/assets/be8ed664-bb53-491b-a5fe-867c3e61a33c)

After creating a Network topology, I woul;d then enter the router CLI and began creating my DHCP router.
Step 1: Go into Cisco CLI and Enter priviledge mode
(Enter "enable" in CLI)

![Screenshot 2025-01-12 005429](https://github.com/user-attachments/assets/cf4d5865-f93d-4ef8-9e03-7a5f0996b905)

Step 2: Go into Global Configuration Mode
(Enter "Configure terminal" in CLI)
![Screenshot 2025-01-12 234516](https://github.com/user-attachments/assets/74e21243-2073-4d82-968d-d225b29f08f6)

Step 3: Create a DHCP pool
(Command: "ip dhcp pool Chris-pool" With the name of the DHCP pool named "Chris-Pool")

![Screenshot 2025-01-12 235003](https://github.com/user-attachments/assets/7032e86b-e740-412e-90ba-1fe29410784e)

Step 4: Initialize a gateway router
(Command: default-router <default-gateway>)

---------> Optionally I've exempted a range of IP addresses (for the sake of practice)
(Command: no ip dhcp excluded-addresses <starting-address> <ending-address>)

