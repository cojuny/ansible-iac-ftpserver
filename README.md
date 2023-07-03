# ansible-iac-ftpserver
Infrastructure as Code (IaC) practice project.
Given a linux operating system, building a vsftpd server straight from ansible playbook. 


### How to Run
1. Prepare a Linux server, preferably Ubuntu.
2. For file inventory, change ip address and user for the target server.
3. Run the following line:
  ```bash
  ansible-playbook  ftp-server.yaml -k -K
