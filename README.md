# scalapi
camera and pi with battery mounted in a derby

tim sayre tim@kitswv.com Kanawha IT Security, ltd. 

i got most of the information off of the internet, this is just me putting it together into one place and testing
to make sure it works.  if you have any problems, please let me know and i will see what i can do.  if you have 
any suggestions or improvements, again, feel free to share them with me.  you can use it as you see fit, just keep 
the credit in tact, as it may be a derivative of someone else.  

the way i did the install was to first install raspbian, and enable ssh and camera use.  then, i typed the commands
individually to download and install mjpg streamer.  i have not yet installed from the script, so there may be bugs 
to work out, let me know if you find any, and feel free to fix them also, as i am not much of a programmer.

i have tested the start_camera script via ssh.  don't forget to chmod the settings, <chmod 777 start_camera.sh>
i am pretty sure you can run the script from any location, but haven't tested this.  i just ran <./start_camera.sh>
from the ssh terminal and went to the web browser and it worked.  
