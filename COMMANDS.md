You can type commands in uppercase or lowercase which doesn't actually matter
#SO, the first session will be on the very basics of ms-dos commands where we will do the following things as listed below

#Command to check the version of the OS or version of other commands
type ver and hit enter

#to view the contents of a directory
type dir command 

$$some important point to remember over here
<DIR> beside them have directories you can see alist of the files in another directory by changing to that directory and then using the dir command again.
  in this case you will change to the DOS directory
  
 So before starting the session make sure that you get into the root directory , which is like C:/>
 so the easied way to get in it is by
  hit cd.. for as many times until you get C:/> 
  or directly hit Cd\
  

#changing directories 
   Now if you like to view the directories in the windows directory then 
  first get into the DOS directory then hit
  cd.. as multiple times ot hit cd\
  then type cd windows 
 
#To read the contents of a directory one screen at a time 
  Type
  dir /p
  anoher command is /w switch
  The switch indicates that MS-DOS should show a wide version of directory list
  
#To view the diectory in wide format type
  dir /w
 
 #if the directory contains more files than will fit on screen, you can combine the /p and /w switches as follows 
  dir /w/p
 
  
  #Create a directory 
  type md space directoryname
  
  To confirm that you have created the new directory type
  dir
  if the directory is present then you have successfully created the directory
  
  #To change into the new directory tyoe the following at the command prompt 
  cd newdirectoryname
  
  #Now when you be into the directory, you can create as much directory as you want by hitting 
  md directoryname
 
  
  ///////////////////        /////////////////////
  //////////////////         ////////////////////
  //////////////////         ////////////////////
  /////////////////          ////////////////////
  ////////////////           ////////////////////
////////////////////
  
  
  
  
  
  For instance,
      if I want to create a folder name School and inside the school folder If I want to create class one then I will create in the following ways
  md School
  dir
  cd School
  md ClassOne
  cd ClassOne
  dir
 >>you have successfully created the School directory
  
  
  #deleting a directory
    rules:
      You cannot be in the directory that you are
      if you are then type cd..
  Now type dir to view all the directory then
  type rd space directoryname
  
  #Changing the drives
  type drivename: enter
  for instance 
     type a: enter
  
  #copying fuikes 
  type
  copy directoryname foldername
  
  For instance,
  copy notepad.exe folder_directory
  
  
  #Renaming files
  Type,
    ren oldname newname
  ren notepad.exe padnote.exe
  
  
  #Deleting files
  Type,
   del foldername
  for instance,
  del notepad.exe
 
  #View all the files that ends with extension old
  dir *.old
  
  In the same way if you want to delete all the directory with the extension old 
  then type 
  del *.old
