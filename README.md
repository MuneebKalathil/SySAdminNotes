# SyS Admin Notes
<h3 Topics </h3> 
1) Submitting Projects to Github <br>
2) Long Boot time for Windows<br>

----------------------------------------<br>
<b>1) Submitting Projects to Github</b><br>
Register Github Account and create a Project.<br>
Install Git on your System.<br>
Configure git one your local system.<br>
```git config --global user.name "<Your Name>"```<br>
```git config --global user.emal "<Your Email>"```<br><br>
Example :<br>
```git config --global user.name "Muneeb Kalathil"```<br>
```git config --global user.email "muneebkalathil@b-on.in"```<br><br>
Clone Github project to your system. You can get your URL from ```Clone or DOwnload``` Tab<br>
```git clone <URL>```<br>
```git clone https://github.com/MuneebKalathil/SySAdminNotes.git```<br><br>
A New Folder Will be created. Here, it is ```SysAdminNotes```. Go to the folder & Create or Copy Files <br>
```cd SySAdminNotes```<br>
```touch file1 file2 file3```<br><br>
Add All files & Commit the changes to git.<br>
```git add *```<br>
```git commit -m "Initial Commit"```<br><br>
Pushing these changes to Gihub<br>
```git push -u origin master```<br>
Enter Your Username & Password<br>

Pulling from Github to your System<br>
```git pull origin master```<br><br>
<i>Yes !! Done your first Github project </i>



<b>2) Long Boot time for Windows</b><br>
Start in Safe Mode.<br>
     While Booting, Press ```F5 or F8``` Continously.<br>
     Select Safe Mode or Direct Services Mode.<br>
     After Log in to the user, Open ```CMD```, type ```chkdsk /f /r``` - It will Check on Next system boot time.<br>
     Install ```CCleaner``` - Clean Registery, Temp Files, Startup & uninstall apps you dont need.<br>
     ```Reboot```. Wait for Disk Check. Login to System. ```Shutdown```. Wait for Some time and power on the system<br>
   
     
