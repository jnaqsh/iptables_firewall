iptables_firewall
=================

A Linux Shell Script with common rules for IPTABLES Firewall.
By default this script only open port 80, 22, 53 (input)
All outgoing traffic is allowed (default - output)

HOW TO USE IT
=============
    cd ~
    mkdir scripts
    cd scripts
    git clone https://github.com/jnaqsh/iptables_firewall/
    cd iptables_firewall
    chmod +x *.fw
    mv server_ip.example server_ip
    vi server_ip # write your server ip

    echo '~/scripts/iptables_firewall/start.fw' >> /etc/rc.local

    ~/scripts/iptables_firewall/start.fw

LICENSE
=======
Copyright (c) 2012 Naqsh Jahan Toos <http://jnaqsh.com/>
This script is licensed under GNU GPL version 3.0 or above
