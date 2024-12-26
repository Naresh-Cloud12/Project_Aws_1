# Project_Aws_1
Create AWS Account, Instances Created for Linux &amp; Windows also install Apache Servers in both
<img width="519" alt="AWS-Connect and change to Rootuser_Capture" src="https://github.com/user-attachments/assets/10166cc0-921e-4286-8edc-48f8e6599901" />
<img width="802" alt="AWS-Installed the Apache Server-Capture" src="https://github.com/user-attachments/assets/a1ad15de-ac37-4ae6-abe0-75060dc2493e" />
<img width="960" alt="Aws-Now deploy the apache as a server" src="https://github.com/user-attachments/assets/ed0059c2-34b6-4789-a6f4-319e7a52f9b2" />


1. A frontend developer gave a code to our organization it was a Apache Server they want that code to deploy 
for that we need to create a server to deploy that.

Step 1- Create Server and give a name for that select the OS and Instance type for optimization eg- 1cpu and memory
also concept Keypair - lets take a example now we going to connect the third party application or for the security
it will use as a Lock.Public key will be in AWS and private key is the keypair.If they want to try to open they need this 
key.

Subnet is the availabilty will be there if want particular availability zone
EC2 - Elastic Compute Cloud ----> Instance compute services

Instance Created.
Now we can connect the instance in Amazon Console also.

Step -2 Opened, now we need to change user to root user because our aws console is working in root user.
 (sudo -i)
After Please check the screenshot for the reference , Now we need cross check whether it was
installed by using Ip address and paste it in console.
If facing any issue now we need go to aws console and need to check the status and start that.
3.89.63.161 for start - systemctl start httpd
Now apache server was installed and done.

Now we can see that in Windows-

Also we see how to connect the instance through thirdparty
for that we need to download putty for windows for linux vmware we need to run

why we are using putty of having aws account because in organization they wont give aws acount
they will provide the ip address and private keypair

So now in putty - pastetheIpAddress-SSH(Linux)-SSH-Authenticator-Credential in there only we
need to give the Keypair to login
 
Now we can see that in Windows- Same process and in putty we can connect

2. Now we need create instance in window for a new desktop(Virtual)
   
Buckets -
S3- Storage services ,cloud storage - Datacentre , S3 - any format (files,videos,phots) also It was serverless
Bucket - Global
Object - in Region it will create
ACl-Access control list

Upload file ss & Object URL and run that in console
![image](https://github.com/user-attachments/assets/c47a71e1-2b60-4743-a07f-2e57a989b95d)
![image](https://github.com/user-attachments/assets/4cac37b7-4f89-4e9b-91c1-0c5fccfe8926)

Bucket -->Versioning (Orginal data will save and future it will change and it change to version changes)
    After enabling version show version will be visible and Now edit the date the same and upload through versioning
    ![image](https://github.com/user-attachments/assets/9490d877-5cc8-4b1c-b330-b4848cbe3efe)
    By Mistake orginal data was loss, if the versioning was there we can retrive if not it will permanently deleted.
    ![image](https://github.com/user-attachments/assets/e4191f0f-52f9-4e36-9565-7ca04ef9c262)

Website Hosting -->Static website hosting & dynamix Hosting
Now let's see how to host static website-----> 
S3 will act as -- server+Middleware(It is for Testing Purpose for a organization)

Now create a html file and in properties enable the static website now we get the URL and paste in Console.
![image](https://github.com/user-attachments/assets/32ac8328-85b2-4b70-b916-5a8c22e708b3)

