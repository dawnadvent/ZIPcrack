# ZIPcrack

**Brute Force - Password - ZIP**

![](/01.png)

* Usage

```cmd
root@kali:~# ZIPcrack /usr/share/wordlists/rockyou.txt file.zip
```

* Download / Install
```cmd
root@kali:~# wget "https://raw.githubusercontent.com/d4t4s3c/ZIPcrack/main/ZIPcrack.sh" -O /opt/ZIPcrack.sh
root@kali:~# chmod +x /opt/ZIPcrack.sh
```

* Add Alias
  * Bash --------> `root@kali:~# echo "alias ZIPcrack='/opt/ZIPcrack.sh'" >> /root/.bashrc`
  * Zsh ---------> `root@kali:~# echo "alias ZIPcrack='/opt/ZIPcrack.sh'" >> /root/.zshrc`
  * Powerlevel --> `root@kali:~# echo "alias ZIPcrack='/opt/ZIPcrackk.sh'" >> /root/.p10k.zsh`

(Close terminal and reopen again)

---
