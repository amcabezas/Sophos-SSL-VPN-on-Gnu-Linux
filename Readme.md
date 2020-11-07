# Sophos SSL VPN Client for GNU/Linux


Step 1: Add VPN.

![step1](img/openvpn_step1.png "step1")

Step 2: Identity > "Gateway:" add Remote IP or domain.

![step2](img/openvpn_step2.png "step2")

Step 3: On IPv4, click "Use this connection only for resources on its network".

![step3](img/openvpn_step3.png "step3")

Step 4: Check setting in file ovpn. "remote [IP or Domain] 8443" view example config in Step 7.

![step4](img/openvpn_step4.png "step4")

Step 5: View example config in Step 7.

![step5](img/openvpn_step5.png "step5")

Step 6: Extract the certificate and key from .ovpn file. Download from repository [script](https://gist.github.com/dleonard00/fa482b4e803bf1f905526275c116c6d8)
```
Execute:
explode-opvn.sh file.ovpn
```

![step6](img/openvpn_step6.png "step6")

Step 7: example ovpn config.

![step7](img/openvpn_step7.png "step7")
