# Fourth Project
The main goal of this project is to Configure and test the basic firewall rules to allow or block the traffic.
# Steps followed
1.Opened Windows firewall by using search bar on the desktop.
2.In the advanced settings of the fire wall travelled through inbound rules and clicked on new rule.
3.Chosen the port option in the new rule and clicked next.
4.Given a name to the rule.
5.Entered port number 23 after selecting port option and clicked next.
6.Selected block the connection and finally created the rule.
7.Similarly created another rule with port number 22 but allowed the connection.
8.To test the rule I opened the *CMD* and entered the command *telnet localhost 23* and it showed as *Connecting To localhost...Could not open connection to the host, on port 23: Connect failed*.
9.Again I tested the port using *telnet localhost 22* ,The connection failed which is expected because no SSH service is running on Windows by default.
  This shows the rule exists, but there's no active listener.
10.Finally I eraised the rules present in the advanced settings of the firewall that I had created.

