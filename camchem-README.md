# camts4
Installation

Clone repository

for linus os x - cd /opt/
for windows - cd /Bruker 

git clone https://github.com/CamNMRService/camchem-ts3

For linux you may need to do sudo git clone if /opt/ is 'protected' 
(Then chmod -R 777 *)

Install files to topspin

Once per Topspin instalation

Copy serv-windows-layoutsearchpath (or linux one)
to $TSHOME\conf\global\layoutsearchpath

For each user

copy serv-windows-parfile-dirs.prop to 
$USERHOME\.topspin1\prop\parfile-dirs.prop
Or to $USERHOME\.topspin-$HOSTNAME\prop\parfile-dirs.prop

A successfull instalation should see the automated test au program just work.

Tested on :-
Tospin 4.1.3 on :-
OS X
Windows 7
Windows 8 in virtualbox
Linux Ubuntu in virtualbox



