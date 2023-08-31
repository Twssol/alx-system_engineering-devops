- **0-iam_beety [file]**
su. 
#switch user
- **1-who_am_i [file]**
id -u -n . 
#id -u show the effective user
#id -n show only username instead of id 
- **2-groups [file]**
groups 
#prints all the groups the current user is part of
- **3-new_owner [file]**
sudo shown. 
#change file owner
- **4-empty [file]**
touch 
#create an empty file
- **5-execute [file]**
chmod 700 file_name 
#add execute permetion to the owner
- **6-6-multiple_permissions [file]**
chmod 554 file_name 
#r+x permission to the owner user and group, read only for others
