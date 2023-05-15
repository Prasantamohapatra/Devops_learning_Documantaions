# Devops_learning_Documantaions
This Repo includes all the learning of DevOps tools with each steps of implementation.

# How To connect to an EC2 Instances useing Putty and putty gen?
First of all we need to Create an EC2 instance in AWS and  create a key pair to ssh with putty.
Then we will wait for server to pass 2/2 check show that we can start working on the server, after that copy the public ip .
![image](https://github.com/Prasantamohapatra/Devops_learning_Documantaions/assets/97822297/e50656ae-9a7c-44fa-b1cd-58818fdeaa3e)

while server is getting ready download PuTTY https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html  and PuTTYgen from [ the official website](https://www.puttygen.com/download.php?val=4).
Useing PuTTYgen we need to convert the key pair to a .ppk file so that we can acess it through Putty
Then Open Putty enter the public IP address then go to SSH > auth > Credentials then browse and select the ppk file created by PuTTYgen an click on open.
![image](https://github.com/Prasantamohapatra/Devops_learning_Documantaions/assets/97822297/5e05dfa5-c57e-4c0e-ac3b-30f83021d759)

Enter the instance username as ec2-user now we are ready to use the EC2 instances.
![image](https://github.com/Prasantamohapatra/Devops_learning_Documantaions/assets/97822297/afc1f708-95aa-4479-9325-9626741b5541)
