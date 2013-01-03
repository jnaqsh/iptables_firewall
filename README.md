iptables_firewall
=================

A Linux Shell Script with common rules for IPTABLES Firewall.
By default this script only open port 80, 22, 53 (input)
All outgoing traffic is allowed (default - output)

HOW TO USE IT
=============
	mkdir /root/scripts
	cd /root/scripts
	wget http://bash.cyberciti.biz/dl/381.sh.zip
	wget http://bash.cyberciti.biz/dl/151.sh.zip
	unzip 381.sh.zip
	unzip 151.sh.zip
	mv 381.sh start.fw
	mv 151.sh stop.fw
	chmod +x *.fw

	echo '/root/scripts/start.fw' >> /etc/rc.local

	
	/root/scripts/start.fw


LICENSE
=======
Copyright (c) 2004 nixCraft project <http://cyberciti.biz/fb/>
This script is licensed under GNU GPL version 2.0 or above

This script is part of nixCraft shell script collection (NSSC)
Visit http://bash.cyberciti.biz/ for more information.
