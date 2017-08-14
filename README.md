# creating-multiple-users-using-ansible-and-copying-ssh-keys
This playbook will help you to create multiple users at once and copy the public ssh keys to authorized_keys, resulting in passpharase or password less login for remote hosts. 

*Playbook tasks assumes that the users have created the public-private key pair and provided the public key to their admin for distribution.

![creating multiple users and distributing ssh keys using ansible](https://raw.githubusercontent.com/rulebreaker4/creating-multiple-users-using-ansible-and-copying-ssh-keys/master/distributessh%20keys.png)

*Users want to use the single private key for all remote hosts.
