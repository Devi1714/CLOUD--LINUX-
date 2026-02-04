# CLOUD--LINUX-
Linux server Web Hosting 
<html><body><h1>My First Heading</h1><p>My first paragraph.</p</body></html>


[ec2-user@ip-172-31-80-79 ~]$ sudo su   //enable
[root@ip-172-31-80-79 ec2-user]# ls     //list the files 
[root@ip-172-31-80-79 ec2-user]# ls -la   //list the predefined files
[root@ip-172-31-80-79 ec2-user]# mkdir ccna    //create folder 
[root@ip-172-31-80-79 ec2-user]# ls
[root@ip-172-31-80-79 ec2-user]# touch aws.text //create file into folder
[root@ip-172-31-80-79 ec2-user]# ls
[root@ip-172-31-80-79 ec2-user]# echo "hiii">aws.text //writer
[root@ip-172-31-80-79 ec2-user]# cat aws.text
[root@ip-172-31-80-79 ec2-user]# yum install httpd  //web hosting 

Is this ok [y/N]: y

[root@ip-172-31-80-79 ec2-user]# systemctl start httpd
[root@ip-172-31-80-79 ec2-user]# systemctl enable  httpd

[root@ip-172-31-80-79 ec2-user]# echo "ccna">/var/www/html/index.html
[root@ip-172-31-80-79 ec2-user]# echo "<html><body><h1>My First Heading</h1><p>My first paragraph.</p</body></html>~">
/var/www/html/index.html
