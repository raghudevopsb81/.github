Following are the links that we will refer in the training 

| __  | Link | Comments |
| ------------- | ------------- | ------------- |
| | Linux -> Kilercoda           ---    Project -> LINK       ----      Starting from Scripting -> DIGITAL DOC - https://youtu.be/JwqtkS3Qk4k | |
| Reference Note & Code | https://github.com/r-devops/ref-note-and-code | Here you will find the reference code blocks for all the tools and some notes |
| Project Documentation | https://learndevopsonline.github.io/learndevopsonline/build/docs/RoboShop-Project-V3/project-overview | |
| Killercoda | https://killercoda.com/rkalluru |  |
| Miro Link | https://miro.com/app/board/uXjVLbj2YRo=/?share_link_id=537403438667 | |
| AWS Account Signup Video | https://www.youtube.com/watch?v=JFwAS_8BZvM |  |
| AWS Account Signup Link  | https://portal.aws.amazon.com/billing/signup#/start/email |  |
| AWS Login Page  | https://us-east-1.console.aws.amazon.com/console/home?region=us-east-1 |  |
| APp repos | https://github.com/roboshop-devops-project-v3 | |

### Linux Username - ec2-user
### Linux Password - DevOps321

Linux Basic Commands.

```
ls  / -l / -A / -h 
cd 
pwd 
touch 
mkdir 
rm / -r / -f 
cp / -r 
mv 
vi 
cat / -n 
head 
tail / -n 
grep 
awk 
curl / -L / -o / -O 
tar -x -f 
unzip 
PIPE 

ps 
kill / -9
sudo 
dnf list / install | repo files in /etc/yum.repos.d 
systemctl start /stop /restart /enable 
useradd 
chown / chgrp / chown 
lsblk / df -h 
```

# Create a server in AWS 


Open URL:

https://us-east-1.console.aws.amazon.com/ec2/home?region=us-east-1#Instances:


Click on Launch Instance 


<img width="1680" alt="image" src="https://github.com/user-attachments/assets/1ce5b429-2a91-4e8c-b736-008cbe2adb52">

Click on Browse AMIs

<img width="1281" alt="image" src="https://github.com/user-attachments/assets/6003502f-e1ab-46e3-8a75-95a9485a1a8b">


<img width="1637" alt="image" src="https://github.com/user-attachments/assets/05feec8d-188f-42a2-9711-5c33cff9e9ec">

<img width="1315" alt="image" src="https://github.com/user-attachments/assets/db67446e-5377-45ac-b61d-41e04e815c2b">



Now we need to connect to the instance.

MacOS - Use inbuilt terminal 

Windows - Download Putty - https://the.earth.li/~sgtatham/putty/latest/w64/putty.exe

Copy Public IP address.

MacOS -> Open Terminal -> ssh ec2-user@<PUBLIC-IP> -> It will prompt for yes or no -> Type yes -> Enter Password -> DevOps321 

<img width="1099" alt="image" src="https://github.com/user-attachments/assets/641012f1-a037-4070-8c40-86449b00418b">


Windows -> Open Putty -> Enter IP address -> You will be prompted to Accept -> Enter username as ec2-user -> Enter Password -> DevOps321

![image](https://github.com/user-attachments/assets/c6f8c5f3-7c83-4432-be48-41c26ed0295e)

![image](https://github.com/user-attachments/assets/7a5a9c84-ec34-4bf2-9b88-eced473ef444)

Choose Accept 

![image](https://github.com/user-attachments/assets/8c9db21a-4465-4c2c-ade6-0aa59bdf83b1)



