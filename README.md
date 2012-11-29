hconfig is a small shell script to help developpers and testers switching DNS environnement between project to manage their /etc/hosts file.

to install it:
```
sudo wget -O /usr/sbin/hconfig https://raw.github.com/povtux/hconfig/master/hconfig
sudo hconfig --init
```

then you just need to put special conf parts of your hosts file to separate files in /etc/hconfig.d/my_env/my_conf_file to be able to use them
for complete usage, refer to:
```
sudo hconfig --help
```
