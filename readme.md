This is the basic doc for Git with CLI understanding 

A. Get any remote directory to local derectory
      1. git clone <https link>

B. Push changes frm local to remote repo
       1. git add <file name>  or git add . {it will add all changes at a time}
       2. git commit -m "<meaningfull message>"
       3. git push origin main or git push 

C. To check staus of file 
       1. git status

D. Add new project from local to remote 
       1. Add new project to remote repo <try to keep same name> Note: do not add readme file it will initiate project may face further issue 
       2. change current directory to working directory
       3. git init 
       4. git remote add origin <shh url>
       5. git add .
       6. git commit -m "<meaningfull message>"
       7. git remote -v (to verify remote) ==>optional
       8. git branch    (to check branch ) ==>optional
       9. git branch -M main   (to rename branch) ==>optional
       10. git push -u origin main

E. Pull Remote repo changes to local repo
     1. git branch -vva
     2. git fetch origin <branch name>
     3. git branch -vva
     4. git checkout <branch name>
     5. git pull 
     
      
