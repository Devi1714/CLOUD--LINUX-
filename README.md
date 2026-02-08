<html><body><h1>My First Heading</h1><p>My first paragraph.</p</body></html>

   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
[ec2-user@ip-172-31-14-79 ~]$ sudo su
[root@ip-172-31-14-79 ec2-user]# ls
[root@ip-172-31-14-79 ec2-user]# ls -la

[root@ip-172-31-14-79 ec2-user]# mkdir cloud
[root@ip-172-31-14-79 ec2-user]# ls
cloud
[root@ip-172-31-14-79 ec2-user]# touch aws.text
[root@ip-172-31-14-79 ec2-user]# ls
aws.text  cloud
[root@ip-172-31-14-79 ec2-user]# echo "hello"aws.text
helloaws.text
[root@ip-172-31-14-79 ec2-user]# cat aws.text
[root@ip-172-31-14-79 ec2-user]# echo "hello"aws.txt
helloaws.txt
[root@ip-172-31-14-79 ec2-user]# echo "hello"aws.text
helloaws.text
[root@ip-172-31-14-79 ec2-user]# cat aws.text
[root@ip-172-31-14-79 ec2-user]# yum install httpd

[root@ip-172-31-14-79 ec2-user]# systemctl login httpd
[root@ip-172-31-14-79 ec2-user]# systemctlenable httpd
bash: systemctlenable: command not found
[root@ip-172-31-14-79 ec2-user]# systemctl enable httpd
[root@ip-172-31-14-79 ec2-user]# systemctl login  httpd
Unknown command verb login.
[root@ip-172-31-14-79 ec2-user]# echo "ccna">/var/www/html/index.html
[root@ip-172-31-14-79 ec2-user]# echo "<html><body><h1>My First Heading</h1><p>My first paragraph.</p</body></html>">/var/www/html/index.html

877934   536386



