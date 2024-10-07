Port Scanner in Python

This code is designed to perform a port scan using the nmap module. IMPORTANT! The scanning target (IP address 45.33.32.156) is the test server provided with permission to all by Nmap (permission for reconnaissance is allowed using this target).

This port scanning exercise is useful for understanding what devices/services are running on a network and allowing for better visibility of assets (see what is in inventory - organisations may not know full extent). The code reports all
ports and services that are open including those that may be unused or unecessary. These areas can be exploited by threat actors. It's important to note that because this program detects all services running on a host, it will spot unauthorised ones too
that could be a means for threat actors to maintain access to a system. Nmap also accesses information on what versions of services are running on a network, which is useful for tracking knowingly vulnerable or outdated software updates which can be used 
by threat actors to exploit systems. Port scanning is useful in the event of a security breach - the user can establish what services a threat actor has targeted. Ultimately, the breach can be terminated by closing vulnerable ports/services. 
