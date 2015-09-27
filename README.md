OSX Dope Login
===================

This bash script makes your mac login screen have a randomly chosen PNG ONLY background image from a file you specify.

Installation
-------------

MAC:
```
sudo git clone git@github.com:rgehring/osxDopeLogin.git /usr/local/osx_dope_login
sudo ln -s /usr/local/osx_dope_login/set_perms /usr/local/bin/osx_login_set_perms
sudo ln -s /usr/local/osx_dope_login/dopenize /usr/local/bin/osx_login_dopenize
```
put in ~/.bash_profile: 

```
osx_login_dopenize
```

 - Add images to ~/Pictures/wallpaper
 - Run ./osx_login_set_perms
