# unityhub-install-error-rocky-linux-9.4
A quick tip to fix the SHA-1 error on Rocky Linux 9.4

First step: After fresh installing Rocky Linux 9.4 run the command 
"sudo update-crypto-policies --set LEGACY"
Reboot your PC

Second step: Follow installing instructions here 
https://docs.unity3d.com/hub/manual/InstallHub.html

Third step: When you done if you wanna keep your system safe run
"sudo update-crypto-policies --set DEFAULT"
Reboot your PC

Reference documentation here:
https://www.redhat.com/en/blog/rhel-security-sha-1-package-signatures-distrusted-rhel-9
