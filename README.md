# how_to_setup_VPS
Setup VPS Easily | Step-by-Step Guide 🚀 A simple and beginner-friendly guide to setting up a VPS from scratch. Covers server configuration, security, and optimization with easy-to-follow steps. Perfect for developers and sysadmins! 🔧💻

 Get 20% Discount https://hostinger.pk?REFERRALCODE=1KSOFT82

Step 1: Login your Hosting provider Panel (Hostinger/Godday/Namecheap...)

Step 2: Got to VPS Panel and install Ubuntu 

Step 3: login your vps using ssh 
        ssh root@your vps ip here
        enter password

Step 3: first lets update ubuntu 
        sudo apt update && sudo apt upgrade -y

Step 4: Install Wget
        sudo apt install wget curl -y

Step 5: lets clone webuzo using wget (what is webuzu ? read more here )
        wget -N http://files.webuzo.com/install.sh

Step 6: once webuzo clonned we need to give permission 
        sudo chmod 777 install.sh

Step 7: lets install webuzo
        sudo ./install.sh

        Note (it will ask you for password you need to add password and confirm password you will be able to login your webuzo panel using that Credentials also it will take some time to install all applications)
        
