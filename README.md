dclab@192.168.1.100

dclab@192.168.1.111

dclab@192.168.1.116

dclab@192.168.1.121

dclab@192.168.1.125

passwd: 111111

不要用dclab直接操作，新建自己的用户：sudo adduser username

添加用户至sudoers：sudo vim /etc/sudoers

User privilege specification下追加username	ALL=(ALL:ALL) ALL (x!保存)

或者使用sudo visudo修改也可
