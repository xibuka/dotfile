# install git and ansible 2.8+
```
$ sudo apt update
$ sudo apt install git
```

# add ansible ppa repo (only for OS under 20.04)
```
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
```

# install ansible 2.8+
```
$ sudo apt install ansible
```


# Grant root access to User
```
$ sudo echo "<username> ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers.d/<username>
```

# run playbook
```
ansible-pull -U https://github.com/xibuka/dotfile.git
```
