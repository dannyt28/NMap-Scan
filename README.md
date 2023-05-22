# NMap-Scan


<h2>Description</h2>
<p>
The following Nmap Scan will be conducted within the same Kali Linux VM utilized in the previous labs mentioned above, employing specific Nmap commands. These commands are intended to identify vulnerabilities on the host machine of the vulnerable virtual machine (in this case, "Metasploitable 2"), which should already be connected to the same NAT network.
</p>

<h2>Environments Used</h2>
<ul>
  <li>
    <p><b>Kali Linux VM</b></p>
  </li>
</ul>

<ul>
  <li>
    <p><b>Metasploitable 2 VM</b></p>
  </li>
</ul>

<h2>Tools Used</h2>
<ul>
  <li>
    <p><b>Nmap</h2>
      
<h2>IMPORTANT NOTE!</h2>
<p>For security reasons, IP addresses and other sensitive information in screenshots have been blurred out.</p>

<h2>Lab walk-through:</h2>

<h2>Screenshot 1:</h2>
<p align="center">
UUtilizing the previous Kali Linux Machine employed in the preceding labs, execute the command "nmap -sn IP Address" while taking care to confirm that the specified IP address corresponds accurately to the vulnerable machine, specifically the metasploitable 2
</p>
<img src="https://i.imgur.com/gwtfQ5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Screenshot 2:</h2>
<p align="center">
Now input the other IP: "nmap -sn IP Address" and proceed by pressing the enter key to initiate the process.
</p>
<img src="https://i.imgur.com/2kUrdbR.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<ul>
    <li>Here we can see the nmap scan perform and the display of hosts connected.</li>
</ul> 


<h2>Screenshot 3:</h2>
<p align="center">
Enter the command 'info' and press the 'Enter' key. Subsequently, input the command 'run' and press 'Enter' once more. Evaluate the displayed IP results and take note of the number of hosts identified.
</p>
<img src="https://i.imgur.com/Y7LSo2z.png" height="80%" width="80%" alt="Disk Sanitization Steps" />


<h2>Screenshot 4:</h2>
<p align="center">
Enter the command 'show hosts' and press the 'Enter' key. This will present host information, including IP details, for your examination.
</p>
<img src="https://i.imgur.com/gVrEF7Z.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
