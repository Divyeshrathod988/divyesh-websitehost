
# divyesh-websitehost
       website host using aws instance 

     step 1:
         Launch Instance and Create an EC2 Instance.  // use instance ubantu //linux
     step 2:
         sudo su -
         apt-get update -y
         git clone this repo //http copy
         git pull
         goto  cd divyesh-websitehost
         mv *   /var/www/html/
         
    step 3:
        apt install -y httpd
        systemctl status httpd   //apache2  --on use httpd 
        systemctl enable httpd
        systemctl start httpd
    step 4:
          goto instance AND copy ip4 and paste crome 
