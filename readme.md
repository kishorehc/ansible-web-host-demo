### instances

<img width="3834" height="1680" alt="Screenshot 2026-06-26 002431" src="https://github.com/user-attachments/assets/9179cdfb-7b17-4e5b-941d-be8a6d625b96" />

### control-node-running-status

<img width="3837" height="1935" alt="Screenshot 2026-06-26 002346" src="https://github.com/user-attachments/assets/48a21876-f621-4acc-ba8e-54e1c3039e49" />

### running webpage on each node

<img width="3837" height="2040" alt="Screenshot 2026-06-26 002356" src="https://github.com/user-attachments/assets/138b7572-0466-4f54-91dd-09a8095afb13" />

<img width="3837" height="2019" alt="Screenshot 2026-06-26 002406" src="https://github.com/user-attachments/assets/2eb94f8c-c531-4bc9-9a17-212b45124160" />


    1  nano key.pem
    2  ls
    3  nano inventory
    4  ls -a
    5  cd .ssh/
    6  ls
    7  cd ..
    8  ssh-keyscan -H 3.110.51.237 13.203.214.229 >> ~/.ssh/known-hosts
    9  ansible all -i inventory -m ping
   10  sudo apt update && sudo apt install ansible -y 
   11  ansible all -i inventory -m ping
   12  chmod 400 key.pem
   13  ansible all -i inventory -m ping
   14  chmod 400 /home/ubuntu/key.pem
   15  ansible all -i inventory -m ping
   16  ssh-keyscan -H 3.110.51.237 13.203.214.229 >> ~/.ssh/known-hosts
   17  ansible all -i inventory -m ping
   18  ssh-keyscan -H 3.110.51.237  >> ~/.ssh/known-hosts
   19  ssh-keyscan -H 13.203.214.229 >> ~/.ssh/known-hosts
   20  ls -a
   21  cd .ssh/
   22  ls
   23  lscd ..
   24  cd ..
   25  chmod 400 /home/ubuntu/key.pem
   26  ssh-keyscan -H 13.203.214.229 >> ~/.ssh/known-hosts
   27  ansible all -i inventory -m ping
   28  nano inventory
   29  ansible kish -i inventory -m ping
   30  ssh -i "key.pem" ubuntu@ec2-13-203-214-229.ap-south-1.compute.amazonaws.com
   31  nano inventory
   32  ansible kish -i inventory -m ping
   33  nano inventory
   34  ansible kish -i inventory -m ping
   35  chmod 600 /home/ubuntu/key.pem
   36  ansible kish -i inventory -m ping
   37  ls -a
   38  cd .ssh/
   39  ls
   40  rm known-hosts 
   41  rm known_hosts
   42  rm known_hosts.old 
   43  ls
   44  cd ..
   45  ssh-keyscan -H 3.110.51.237 13.203.214.229 >> ~/.ssh/known_hosts
   46  ansible kish -i inventory -m ping
   47  nano playbook
   48  ls
   49  nano playbook
   50  ls
   51  mv playbook playbook.yml
   52  ls
   53  nano playbook.yml 
   54  ansible-playbook -i inventory playbook.yml
   55  nano playbook.yml 
   56  sudo apt install zip 
   57  ls
   58  wget -O app.zip https://www.tooplate.com/download/2158_forge_reality
   59  ls
   60  unzip app.zip 
   61  ls
   62  pwd
   63  nano playbook.yml 
   64  ansible-playbook -i inventory playbook.yml 
   65  nano playbook.yml 
   66  ansible-playbook -i inventory playbook.yml 
   67  nano playbook.yml 
   68  ansible-playbook -i inventory playbook.yml 
   69  nano playbook.yml 
   70  ansible-playbook -i inventory playbook.yml 
   71  ls
   72  nano playbook.yml 
   73  nano inventory 
   74  ls
   75  ansible-playbook -i inventory playbook.yml
   76  hisatory
