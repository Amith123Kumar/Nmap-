# Nmap-
**NMAP results in Excel - (Note : save all the txt file as ".sh" extention and give execution permission to the files)

step 1 : Clone (00.git repo.txt) git project into your linux distro system.

step 2 : Create a script based on  required ports refer (1.nmap_script.txt) , and our script gives the output in xml file .
         Then after we convert xml into excel output using the cloned project.
  
step 3 : use this script(2.converting to excel .txt) to convert our .xml file to .xlsx 

step 4 : To get generated output excel sheet to your customized email address follow this script (3.sending_mail.txt)


**Extra scripts :** 
  
Mentioning the crontab job :

crontab -e 

 step 5 : set cronjob as (cronjob.txt ) 
  
 step 6 : To get email notification when the scanning starts  (0.startscript.txt).
  
 step 7 : To get email notification when the scanning ends ( 4.endscript.txt) 
