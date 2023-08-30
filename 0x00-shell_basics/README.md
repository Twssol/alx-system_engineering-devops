- **0-current_working_directory [file]**
 pwd. #print the working directory
- **1-listit [file]**
 ls. #Display the contents list of your current directory
- **2-bring_me_home [file]**
cd. change working directory to user's home directly
- **3-listfiles [file]**
ls -l. #list the current directory contents in longterm
- **4-listmorefiles [file]**
ls -al. #list the current directory contents including hidden files in longterm
- **5-listfilesdigitonly [file]**
ls -al -n. #list the current directory contents including hidden files in longterm using numorical group IDs 
- **6-firstdirectory [file]**
mkdir. #make directory
- **7-movethatfile [file]** 
mv. # move files and directories to new directory.
- **8-firstdelete [file]**
rm. #remove files.
- **9-firstdirdeletion [file]**
rmdir. #remove directory
- **10-back[file]**
cd -. #changes the working directory to the previous one.
- **11-lists [file]**
ls -al . .. /boot  #lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory in long format.
- **12-file_type**
file. #show file type
- **13-symbolic_link [file]**
ln -s target symbolic_name. #Create a symbolic link
- **14-copy_html [file]**
cp -u *.html ..  #copy all html files that doesn't exist in the perent directory from the current directory.
- **100-lets_move [file]**
mv [[:upper:]]*  #moves all files beginning with an uppercase letter to the spesific directory
- **101-clean_emacs**
rm *[[:~:]] # deletes all files in the current working directory

