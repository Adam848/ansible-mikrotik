# ansible-mikrotik
<h1>Ansible Roles</h1>
mtk-ros-upgrade is a role that when used will check that ROS is updated and if not will get the router upgraded<br>
!<br>
mtk-firmware-upgrade is a role that when used will upgrade the firware on a Mikrotik<br>
!<br>
mtk-ssh-keys is a role that when used will create an RSA keypair on the Ansible host, and install the public key on a MTK device<br>
!<br>
mtk-password is a role that when used will update the password for a supplied user<br><br>
<h1>Ansible Playbooks</h1><br><br>
mtk-wlan2-ani enables adaptive noise immunity on wlan2(usually the 5ghz radio)<br>
!<br>
mtk-wlan2-power drastically lowers power on wlan2 by setting its dBi on the interface artifically high and setting it to indoor<br>
!<br>
mtk-wlan2-tuning enables a whole host of tweaks for the wlan2 radio<br>
