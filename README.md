# NetworkScanner-With-ShellScript

## Technologies
<ul>
<li> Shell Script </li>
</ul>

<br>

## Running This Program
In order to run this program, first on the terminal screen; <br>

<code> git clone https://github.com/SeymaAtmaca/NetworkScanner-With-ShellScript.git </code> <br>
<code> bash networkScanner.sh.save </code> <br><br>
commands must be run. <br> <br>

After the program runs, the IP address of the relevant device is shown and then other devices connected on the network are shown with their IP addresses. The user is prompted to select a target IP <br><br>

After selecting the target IP address, the user is presented with 7 options for the actions they want to do. <br>
<ul>
      <li> 1)   Scan for available hosts</li>
      <li>  2)   Scan all ports with fake IP</li>
      <li> 3)   Check Firewall</li>
      <li> 4)   Send Ping </li>
      <li> 5)   ARP Spoofing </li>
      <li> 6)   DNS Attack with MITMF </li>
      <li> 7)   Start attack for network connection</li>
</ul><br>

![1](https://github.com/SeymaAtmaca/NetworkScanner-With-ShellScript/blob/main/images/Options.jpg) <br><br>

The user has to choose one of the above options. The first option brings up the hosts of the target IP. Option 2 shows open ports. Option 3 use to perform Firewall control. Option 4 sends a ping to the remote device for control purposes. Option 5 is used for ARP attack. Option 6 performs DNS attack via MITMF Framework. Option 7 is the most comprehensive. Here, a general attack is organized for devices on the network. The hooking script created via Beef can be published on Linux apache2, and requests coming to the relevant website and logged in devices can be monitored with the BEEF Tool. <br><br>

![2](https://github.com/SeymaAtmaca/NetworkScanner-With-ShellScript/blob/main/images/Info.jpg) <br><br>

The existence of tools such as BEEF used in the program is checked. If the desired tool is not available, the user is asked whether he wants to download these programs. If not downloaded, the program terminates. <br><br>

After selecting one of the 7 options given above and starting the attack, this list is presented to the user again and again in order to be able to perform different scans and an effective use is ensured.
<br> <br>


## Contact

 My [LinkedIn](https://www.linkedin.com/in/%C5%9Feyma-atmaca-925b57195/) profile.
