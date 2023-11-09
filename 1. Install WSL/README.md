# Windows 10 Pro

# Powershell as Admin
```
wsl --list -o
wsl --install -d Ubuntu
```

# WSL
```
username: ady
password: ady78945
```

# CMD as Admin
```
wsl
apt update -y
apt install ansible -y
ansible localhost -m ping
```



# Troubleshoot

```
systeminfo
wsl --update
wsl --set-default-version 1
```