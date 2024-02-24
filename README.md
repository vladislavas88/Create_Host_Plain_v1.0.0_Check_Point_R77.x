 
Using the script for create hosts for Check Point dbedit
#===============================================================================
#
#       FILE: create_host_plain.pl 
#
#       USAGE: $ touch ./in.txt
#		10.1.1.1
#		10.2.2.2
#		10.3.3.3
#		10.4.4.4
#		etc
#
#		$ ./create_host_plain.pl
#
#		$ cat ./host_plain.txt
#		create host_plain Organization_User_Computer_10.1.1.1
#		modify network_objects Organization_User_Computer_10.1.1.1 ipaddr 10.1.1.1
#		modify network_objects Organization_User_Computer_10.1.1.1 color 'forest green'
#		create host_plain Organization_User_Computer_10.2.2.2
#		modify network_objects Organization_User_Computer_10.2.2.2 ipaddr 10.2.2.2
#		modify network_objects Organization_User_Computer_10.2.2.2 color 'forest green'
#		create host_plain Organization_User_Computer_10.3.3.3
#		modify network_objects Organization_User_Computer_10.3.3.3 ipaddr 10.3.3.3
#		modify network_objects Organization_User_Computer_10.3.3.3 color 'forest green'
#		create host_plain Organization_User_Computer_10.4.4.4
#		modify network_objects Organization_User_Computer_10.4.4.4 ipaddr 10.4.4.4
#		modify network_objects Organization_User_Computer_10.4.4.4 color 'forest green'
#
#  DESCRIPTION: Create hosts for Check Point dbedit
#
#      OPTIONS: ---
# REQUIREMENTS: Perl v5.14+ 
#         BUGS: ---
#        NOTES: ---
#       AUTHOR: Vladislav Sapunov 
# ORGANIZATION:
#      VERSION: 1.0.0
#      CREATED: 04.10.2023 22:48:36
#     REVISION: ---
#===============================================================================
