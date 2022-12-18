# General

<details>

<summary>How do IDS and IPS differ from one another?</summary>

The administrator must stop incursion once the IDS, or _intrusion detection system_, discovers them. Contrarily, in an IPS (_intrusion prevention system_), the system not only detects the intrusion but also addresses it.&#x20;
</details>

<details>
<summary>How is encryption different from hashing?</summary>

Hashing and encryption change one type of data into another. Encrypted data can be decrypted and converted to the original, while hashed data cannot be reconverted.
</details>

<details>
<summary>Why do organizations use firewalls? What does it do?</summary>

A firewall is a type of network security device installed on a system or network perimeter. It monitors and manages network traffic. They also allow you to block content filtering and remote access.
</details>

<details>
<summary>Describe the 3-way handshake.</summary>

A three-way handshake is a procedure used in a TCP/IP network to establish a client-host connection and exchange packets. Here’s the three-step procedure: \


* The client sends an SYN (synchronization) to check for available ports and whether the server is online.
* If the client has open ports, the server will send an SYN-ACK message.
* The client acknowledges the message and returns an ACK(Acknowledgment) packet to the server.
</details>

<details>
<summary>What distinguishes HIDS and NIDS from one another?</summary>

Both HIDS (Host IDS) and NIDS (Network IDS) are intrusion detection systems that find intrusions. Programmers employ the HIDS on a specific host or device — the only distinction. It keeps an eye on a device’s suspicious system activity and traffic. However, NIDS is configured on a network. It keeps track of every _network_ device’s traffic.
</details>

<details>
<summary>What are the possible response codes for a web application?</summary>

* Informational responses
* Server-side error
* Redirection
* Client-side error
* Success
</details>

<details>
<summary>What distinguishes penetration testing (PT) from vulnerability assessment (VA)?</summary>

Vulnerability assessment is a process for finding target _faults_. In this case, the organization is aware that its systems or networks have defects or weaknesses, and they want to identify these flaws and prioritize them.&#x20;

\
Meanwhile, penetration testing is a process for finding _vulnerabilities_. In this scenario, the firm would have installed all security precautions they could think of and would wish to investigate any more vulnerabilities in their network or system.\
</details>

<details>
<summary>What procedures are involved in installing a firewall?</summary>

Here are the steps to install a firewall:

* Username/password: Change a firewall device's default password
* Remote administration: Turn off the remote administration feature.
* Port forwarding:Set up the proper port forwarding to ensure applications like a web or FTP server function properly.
* DHCP server:Disable the firewall’s DHCP server to ensure no conflict.&#x20;
* Logging:Enable logging and learn how to view logs to fix firewall problems or potential assaults.
* Security policies: Establish strong, enforceable security policies for your firewall.
</details>

<details>
<summary>How does the SSL protocol guarantee network security?</summary>

The SSL (Secure Sockets Layer) authenticates the sender and establishes secure connections between the browser and web server. Still, it does not offer security once the data has been sent to the server. That’s why server-side encryption and hashing are necessary to guard against data breaches. \
</details>


<details>
<summary>Establishing an SSL connection:</summary>

* A browser tries to establish a connection with an SSL-secured web server.
* A copy of the browser's SSL certificate is sent to the browser.
* The browser verifies the SSL certificate's trustworthiness.&#x20;
* If it is reliable, the browser notifies the web server that it wants to create an encrypted connection.The web server transmits an acknowledgment to create an SSL-encrypted connection.
* The web server and browser communicate using SSL encryption.
</details>


<details>
<summary>How can you secure a server?</summary>

Secure servers encrypt and decode data using the Secure Sockets Layer (SSL) protocol to prevent unauthorized access to it.\
Here are four fast ways to safeguard a server:

* Step 1:Make sure your root and administrator account passwords are safe.
* Step 2:Create new users to manage the system.&#x20;
* Step 3: Ensure the root and administrator accounts cannot access the internet by default.
* Step 4: Configure your firewall rules for remote access.
</details>

<details>
<summary>What do you know about data leakage?</summary>

Data leakage is a purposeful or unintentional transmission of data (private information from within the company to an unapproved outside location (unauthorized party). \
Based on how it occurs, we can split data leakage into three categories:

* Accidental Breach:When an organization accidentally sends information to a third party due to a mistake or error.
* Intentional Breach:When an authorized entity sends data to an unauthorized party on purpose.
* System hack:A hacker accesses private data.&#x20;

You can stop data leakage with DLP (Data Leakage Prevention) tools, software, and techniques.\
</details>


<details>
<summary>What is a brute force attack? What can you do to stop it?</summary>

Brute force is a method for accessing credentials by trial and error — continually attempting all possible combinations of credentials until you hit the right one. Here’s how you can avoid brute force attacks:

* Maximum Length Password:Specify the maximum length of a password, so it becomes harder to find the right combination.
* Password Complexity:Requiring many character types in the password makes brute force attacks more difficult. You might establish requirements for special characters, upper- and lower-case letters, and numbers.\

* Limiting Login Attempts:Establish a cap on failed login attempts, which makes it impossible to try all possible password combinations.
</details>

<details>
<summary>Why do ports get scanned?</summary>

Port scanning is a technique to determine a host’s available and open ports. Hackers use it to exploit vulnerabilities, while administrators use it to check the network's security procedures. \
Common methods for port scanning include:

* Ping Scan
* TCP Half-Open
* TCP Connect
* UDP
* Stealth Scanning
</details>

<details>
<summary>What are the OSI model layers?</summary>

The OSI layers are as follows:

* Physical layer:Digital data transmission from sender to receiver via a communication medium.&#x20;
* Data Link Layer:Encodes and decodes data bits and controls data transfer to and from the physical link.&#x20;
* Network Layer:Forwards packets and offers routing channels for network communication.
* Transport Layer:Ensures end-to-end network connection by dividing the data from the layer above, sending it to the network layer, and verifying the recipient received all the data.&#x20;
* Session Layer:Establishes and manages a session-layer connection between the sender and the recipient. In addition to starting, halting, and controlling the session, it is responsible for establishing, maintaining, and synchronizing contact between the sender and the receiver.
* Presentation Layer:Displays the data in a suitable manner and structure.
* Application Layer:Interface between the network and the application, emphasizing process communication on a communication interface.
</details>
