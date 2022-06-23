# DirAttack

<div style="display:flex !important;align-items:center !important">

DirAttack tools, Search file and directory on website,<br>open source tools available for Termux and Linux.<br>Easy to use!
</div>

| options | Description                | example usage                                   |
|---------|----------------------------|-------------------------------------------------|
| -u      | set your target url        | dirattack -u site.com                           |
| -d      | use default wordlist       | dirattack -u site.com -d                        |
| -w      | use costum wordlist        | dirattack -u site.com -w /path/to/wordlist.txt  |
| -r      | remove/uninstall dirattack | dirattack -r                                    |


# install


**Linux**
```
root@linux# apt-get install git python3 -y
root@linux# git clone https://github.com/Transmetal/DirAttack-master
root@linux# cd DirAttack
root@linux# chmod 777 -R install.py
root@linux# python3 install.py

Done...

Press super on your keyboard and search dirattack. or just type: 'dirattack --help'

```

**Termux**
```
$ pkg install git python -y
$ git clone https://github.com/Transmetal/DirAttack-master
$ cd DirAttack
$ chmod +x install.py
$ python3 install.py
$ dirattack --help
```
