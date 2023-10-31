<p align="center">
<img src="https://i.imgur.com/AeiqMDZ.png" alt="File Share Graphic"/>
</p>

<h1>Building Intuition with DNS</h1>
This demo explores integrity as found in the CIA Triad.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- PowerShell ISE

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Creating sample files.
- Overall FIM Demonstration, using a basic PowerShell script.
- Manually checking hash(es).


<h2>Deployment and Configuration Steps</h2>

<p>
Welcome back! This is going to be more of a demonstration than a tutorial, just because it isn't designed to be very lengthy or long-winded.
</p>
<br />

<p>
<img src="https://imgur.com/bAC6cqK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Just for ease of use, and to not dirty up my actual computer, I'm going to use an Azure VM. First, I'll make a folder for everything related to the demo on the VM. Then, I'll create a few mock text files and open PowerShell as an Admin to begin. I'll paste the source code into PowerShell and then save the .ps1 file into the FIM folder. I'll also make sure that the file path is set correctly to show up in \\Desktop.
</p>
<br /> 

<p>
<img src="https://imgur.com/ejazv70.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I'll run the program and it will give me two options. I'll create a new baseline and it will create a new .txt file with SHA512 hashes for each document.
</p>
<br /> 

<p>
<img src="https://imgur.com/TwmTjUJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the program is running, we can observe various changes such as a file changing or being created, and the FIM will notify us. See above image.
</p>
<br /> 

<p>
Again, this is very rudimentary, and more of a proof of concept/demo than anything. Regardless, thank you for following along!
</p>
<br /> 
