iptables_firewall
=================

A Linux Shell Script with common rules for IPTABLES Firewall.
All outgoing traffic is allowed (default - output)

HOW TO USE IT
=============
    cd /root
    git clone https://github.com/jnaqsh/iptables_firewall/
    cd /root/iptables_firewall
    chmod +x *.fw
    mv server_ip.example server_ip
    vi server_ip # write your server ip

    echo '/root/iptables_firewall/start.fw' >> /etc/rc.local

    /root/iptables_firewall/start.fw

LICENSE
=======
Copyright (c) 2012 Naqsh Jahan Toos <http://jnaqsh.com/>
This script is licensed under GNU GPL version 3.0 or above
