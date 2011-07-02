# Anti Brute Force #

## Secure your Symphony backend login page against brute force attacks ##

Prevents people and software to brute force your authors, account.  
After **x** failed attempt, the IP address will be banned for **y** min.  
**x** and **y** are settings in the preferences page

### REQUIREMENTS ###

- This Extension relies on the "Advanced Symphony Database Connector" (ASDC) library. Read more about it 
  at https://github.com/symphonycms/asdc and grab the latest stable version using 
  "git clone git://github.com/symphonycms/asdc.git". 

### INSTALLATION ###

- Install *ASDC*
- Unzip the anti_brute_force.zip file
- (re)Name the folder anti_brute_force
- Put into the extension directory
- Enable/install just like any other extension
- (optional) Go to the *Preferences* page to customize settings

*Voila !*

http://www.nitriques.com/open-source/

### History ###

- 1.0 - 2011-07-01  
  First release