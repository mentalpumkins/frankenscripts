Mary Shellys Frankenscripts 
---------------------------
changepass:
 - changes the password for any user that has the same login shell as the user running the script.
 - prompts you for the password and tells you what user.

iptables-config:
 - sets iptables rules to be fairly paranoid
 - usage: ./iptables-config [-h/-?] [-s <ssh_port>] [-p <port_1>,<port_2>,...,<port_n>]
