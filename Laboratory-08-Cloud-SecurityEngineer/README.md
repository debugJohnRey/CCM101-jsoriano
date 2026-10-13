# Checkpoint 6 - Technical Documentation

**Mission Overview:**
I secured a Linux server using a host-based firewall.

**Objectives:**
I audited network ports and configured UFW with a Default Deny policy. I selectively allowed SSH and HTTP traffic.

**Commands Executed:**
* `docker run -d --name secure-web-app -p 8080:80 nginx`
* `curl http://localhost:8080`
* `sudo ufw allow ssh`
* `sudo ufw default deny incoming`
* `sudo ufw default allow outgoing`
* `sudo ufw enable`
* `sudo ufw status verbose`
* `sudo ufw allow 8080/tcp`
* `sudo ufw status numbered`

**Skills Learned:**
I learned granular port management and defense in depth.