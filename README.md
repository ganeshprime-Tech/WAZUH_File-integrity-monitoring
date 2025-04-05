# WAZUH_File-integrity-monitoring
File Integrity Monitoring For Linux

Step 1:
ADD the Agent
![image](https://github.com/user-attachments/assets/206b6ea9-4130-4b35-91cc-616171cb5b79)
![image](https://github.com/user-attachments/assets/9d6c1bf0-99a0-4f18-925e-a8fc307aecff)
![image](https://github.com/user-attachments/assets/694bdcbe-fa02-4e91-8630-bf0fd92f6e70)

I'm already added the two agents if i want to change the wazuh_server ip refer this place /var/ossec/etc/ossec.conf

![image](https://github.com/user-attachments/assets/277b15e0-ab08-4d8c-89cd-6868d79485c5)

within the <syscheck> block
ADD <directories check_all="yes" report_changes="yes" realtime="yes">/root</directories> 

![image](https://github.com/user-attachments/assets/2c6b7e5d-fe96-4cc3-8953-d0604bbfc056)

![image](https://github.com/user-attachments/assets/fcf899f5-58c4-4c75-8a11-7c32fd85b7c8)





