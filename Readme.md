How to make a vm( virtual machine)=
1.make an account on aws.

2.select ec2 service.

3.inside ec2 make an instance,

For an instance select an os( operating system),
5.make an key pair ( the key pair will automatically be downloaded).

6 while making key pair select ppk type ,

7.an public ip will be generated,

8.launch the instance

Install an putty ( search on google how to download putty for (the operating system you have chosen) and download it.

After that open the putty and on ssh option paste the public ip from the instance,

11.in the aut option select credentials and browse the key pair you have created in instance,

Now to download a web server open putty and type :-sudo apt update, after that type :-sudo apt Install apache2,
13:- to remove the dollar sign type:- sudo su,

14:- after that the next step is to type :-/var/www/html/

15.enter the above and on the next line type index.html

16.after that type :-rm index.html

17.enter the above and type :-vi index.html ( by writing this a new page will appear in which you have to either type html code aur copy paste it from GitHub),

18.to run the code type :- control+c ,shift+ ,wq and enter
