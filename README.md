# HelloWorld
My first sample repository on git.
this is the sample repository for people those who don't know how to push your local code to github


Steps to upload your android project to git:

1.Download from this link https://git-scm.com/downloads for windows.

2.Install Git-X.XX.X-64-bit.exe.

3.Open your android studio project and follow these steps

    i.  Goto File->Settings->Version Control->Git->
         in Path to Git executable: give the git.exe path where the installer located
    ii. hit on Test button it will show Git executed successfully.
    iii.select SSH executable as Native click ok.
    iv. Next Step is same Goto File->Settings->Vesrion Control->Github
       keep Host github.com
       enter your git hub mail id
       enter yout git password 
       if you wont able to see email and password sections change Auth type to Password
       Hit on ok
       
       hurray!! now your android studio is connected with your github account
       
    As the same way we need to connect our git desktop to our github account by following steps we can do it.
    
       open yout git bash terminal
       type
       
       $git init
       
       it will initialize your git
       
       $ git config --global user.email "you@example.com"
       
       this command will prompt to login your github account
       
       Atfer that run
       
       To be sure Run:

       $ git config --local -l
       
       now all set. its time to create repository on github
       
       create new repository on github web
       
       Come to android studio, now we need to create local repository For that follow these steps
       
       Goto VCS menu->import into version control->Create git repository->goto your actual project path
       
       example:my project is in this path Users/venky/Desktop/AndroidStudioProjects/HelloWorld
       
       HelloWorld is the project title and main root folder
       
       select your root folder->hit ok
       
       it will create a local repository.
       
       
       Now come to git bash terminal type following commands
       
      Navigate to Project location by following
      
      $cd Users/venky/Desktop/AndroidStudioProjects/HelloWorld
      
      $git add .
      
      $git commit -m "Add existing file"
      
      $ git push origin master
      
  4 Done.more details go through this link ttps://www.londonappdeveloper.com/how-to-use-git-hub-with-android-studio/
 

