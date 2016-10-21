# Usermod
Script to change a user's group to grant or revoke SSH access

##Usage

To add user to group to grant SSH access, execute the script as below 
with replacing \<username\> with the actual name of the user.

./usermod -g \<username\>

To add user to group to revoke SSH access, execute the script as below

./usermod -r \<username\>
