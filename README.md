# Debian Server MOTD Files

To install these files on Debian 13 (trixie) run the following command from the root of this project:
```bash
sudo install -o root -g root -m 0755 00-header 01-banner 02-status 03-services 04-apt-updates /etc/update-motd.d/ \
  && sudo install -o root -g root -m 0644 colors.txt /etc/update-motd.d/
```

When ran these files will result in output similar to:

```
Welcome to Debian GNU/Linux 13 (trixie) (GNU/Linux 6.12.48+deb13-cloud-amd64 x86_64)

  ___            ___
 /   \          /   \
 \_   \        /  __/
  _\   \      /  /__    ███╗   ███╗ ██████╗  ██████╗ ███████╗███████╗
  \___  \____/   __/    ████╗ ████║██╔═══██╗██╔═══██╗██╔════╝██╔════╝
      \_       _/       ██╔████╔██║██║   ██║██║   ██║███████╗█████╗
        | @ @  \_       ██║╚██╔╝██║██║   ██║██║   ██║╚════██║██╔══╝
        |               ██║ ╚═╝ ██║╚██████╔╝╚██████╔╝███████║███████╗
      _/     /\         ╚═╝     ╚═╝ ╚═════╝  ╚═════╝ ╚══════╝╚══════╝
     /o)  (o/\ \_
     \_____/ /
       \____/

 Last login..........: root at Fri Jun 9 11:19 from 1.1.1.1
 Uptime..............: 1 day, 11 hours, 34 minutes
 Load Averages.......: 1 min: 0.01% | 5 mins: 0.07% | 15 mins: 0.08%
 Memory..............: Used: 342 MB | Free: 63174 MB | Total: 64277 MB
 Disk................: Used: 1.7 .GB | Free: 412 GB | Total: 436 GB
 SSH Logins..........: 1 users logged in
 Processes...........: 199 running processes
```
