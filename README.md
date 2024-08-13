source code taken from https://github.com/nquo/dmd-save-repacker

Death Must Die save repacker, modifed to work with intel macs

step 1 - put the file in the directory you like and switch to it , preferably put your file in desktop and run this command in terminal 

cd /Users/replace/Desktop


replace "replace" with your user


step two - run this command on your terminal 


./dmdsave "/Users/replace/Library/Application Support/com.Realm-Archive.Death-Must-Die/Saves/Slot_0.sav"


replace "replace" with your user

now you should see a result_00.json on your desktop , edit it with text edit 


now edit whatever valued you want like "gold" 


step three - after you after you are done run this command in terminal while being in the same directory



./dmdsave result_00.json


this will dive you a result_00.sav file , rename it manually to Slot_0.sav and put it back in 

/Users/result/Library/Application Support/com.Realm-Archive.Death-Must-Die/Saves/Slot_0.sav 


replace "replace" with your user

and delete the old file 





