<p align="center">
<img src="https://imgur.com/wYucC7L.png" alt="osTicket logo"/>
</p>

<h1>Microsoft Azure Compute and Networking 🪟 - Observing ICMP Traffic (Internet Control Message Protocol)</h1>
This section outlines the process of using Powershell within the Windows 10 Virtual Machine to send a Ping (Packet Internet Groper) request to the Linux Virtual Machine, and observing the resulting reply from the Linux Virtual Machine in Wireshark Network Protocol Analyzer. <br /> (Link Back to Main Project Contents Page is at the Bottom of this Repo)

<h2>Environments and Technologies Used</h2>

- Lenovo Ideapad 5 Pro 16gb AMD Ryzen 7
- Microsoft Azure Resource Group (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Microsoft Azure Windows 10 Pro version 22H2 - x64 Gen2 Virtual Machine (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Microsoft Azure Ubuntu Pro 24.04 LTS - x64 Gen2 Virtual Machine (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Wireshark Network Protocol Analyzer Software
- Windows Powershell

<h2>Operating Systems Used </h2>

- Local Windows 11 Home Version 21H2</b>
- Windows 10 Pro version 22H2 Virtual Machine
- Ubuntu Pro 24.04 LTS - x64 Gen2 Virtual Machine

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Microsoft Azure Subsription Credit
- Wireshark Installed on Windows 10 Virtual Machine

<h2>Installation, Setup, Resource Setup, Executing Functions</h2>

1. Below is an instance of the Windows 10 Virtual Machine opened using the Remote Desktop Protocol (Windows Remote Desktop).
<p>
<img src="https://imgur.com/9IqV3PR.png" alt="Disk Sanitization Steps"/>
</p>
<p>
2. I then installed the Wireshark Protocol Analyzer on the same Windows 10 Virtual Machine.
</p>
<br />

<p>
<img src="https://imgur.com/ywlg3Rq.png" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Within Wireshark I then started packet capture as shown below
</p>
<br />

<p>
<img src="https://imgur.com/ldh9u1W.png" alt="Disk Sanitization Steps"/>
</p>
<p>
4. I then filtered for ICMP traffic only. Initially nothing showed as expected. I then initiated a Ping request to the Linux Virtual Machine using it's Private IP address 10.0.0.6. From the echo reply packet we can see that the Linux Virtual Machine was available. 
</p>
<br />

<p>
<img src="https://imgur.com/d3DXlgU.png" alt="Disk Sanitization Steps"/>
</p>
<p>
LINK BACK TO THE MAIN PROJECT CONTENTS PAGE - https://github.com/wahidonchain/Azure-Compute-and-Networking
