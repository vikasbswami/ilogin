# ilogin
Simple script to automate the web form based login using curl for jailbroken iPhone.


/* CREATED BY ViKING (@vikasbswami) */


#Description:
Automatic ISP webform login script which starts up automatically and runs at interval of an hour.


#Prerequisites:

1) Jailbroken iPhone

2) cUrl installed


#Steps:

1) Create a directory /var/root/ViKing and place the ilogin script.

2) Copy the com.ViKing.ilogin.plist file into /Library/LaunchDaemons

3) Run launchctl load /Library/LaunchDaemons/com.ViKing.ilogin.plist
