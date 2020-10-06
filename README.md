
# groovygdm3

_**This script assumes that the Installation of Ubuntu 20.10 is a fresh install. If you tried to change the GDM background with some other scripts you first need to reset those changes. Other scripts may have the option --reset.**_


_**Change the login screen background for Ubuntu 20.10 only**_

this script is to change the login screen background of Ubuntu 20.10 only.

you can download the `groovygdm3` file via command line

make sure git and libglib2.0-dev are installed if not enter this command :

sudo apt-get install git libglib2.0-dev

git clone https://github.com/ackr-8/groovygdm3.git

Once you downloaded the script `groovygdm3`. cd to the folder groovygdm3.

run the below command with root privileges (sudo) and follow the prompts.
`./groovygdm3 --set`

to reset everything that the script made
run the below command with root privileges (sudo)
`./groovygdm3 --reset`

if you are having issues running the script enter the following command :
chmod +x groovygdm3

