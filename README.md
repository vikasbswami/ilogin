# ilogin
Simple script to automate the web form based login using curl for jailbroken iPhone.


/* CREATED BY ViKING (@vikasbswami) */


#Description:
Automatic ISP webform login script which starts up automatically and runs at interval of an hour.


#Prerequisites:

1) Jailbroken iPhone

2) ssh enabled

3) cUrl installed


#Steps:

1) Edit ilogin script, edit your username, password and the url of your ISP's login page.

2) (Optional) Edit com.ViKing.ilogin.plist file, edit value between <integer>seconds</integer> tags. It's the interval you want the ilogin to execute. Default is 1 hour, the ilogin script will try to login to the ISP after every 1 hour.

3) ssh into your iPhone, if you couldn't ssh into your iPhone then use Saurik's guide on Cydia app. 

4) Create a directory /var/root/ViKing

5) Copy the com.ViKing.ilogin.plist file into /Library/LaunchDaemons

4) Run launchctl load /Library/LaunchDaemons/com.ViKing.ilogin.plist
