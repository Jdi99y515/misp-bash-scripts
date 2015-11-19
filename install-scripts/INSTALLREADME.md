Once you have a basic LAMP stack up you can run this script to install misp and its dependecies to bring it up quickly for development and testing.

If you would like to run this using vagrant you could use https://box.scotch.io/

1. Clone the scotch box repo:
git clone https://github.com/scotch-io/scotch-box.git

2. cd into it

3. Run vagrant up

4. ssh into the box and navigate to var/www/public

5. run the script
sh ubuntu-MISP-install-script-v0.01.sh

Then sit back while it install itself and think about all the people round the world currently coping and pasting from a readme, or just go and get a coffee or anything else really.
