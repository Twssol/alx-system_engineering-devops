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
#-rwx------ permission
- **6-multiple_permissions [file]**
chmod 554 file_name 
#-r-xr-xr-- permission
- **7-everybody [file]**
chmod ugo+x file_name
#-rwxr-x--x permissin
- **8-james_bond[file]**
chmod 007 file_name
#-------rwx permission
- **9-John_Doe [fille]**
chmod 753 file_name
#-rwxr-x-wx permission
- **10-mirror_permissions[file]**
chmod --reference 
#give same permissions to another file
- **11-Directories_permissions [file]**
chmod ugo+x directory_name 
#gives execute permission of the directory to user,group and others
