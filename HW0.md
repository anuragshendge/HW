#CSC 791 Homework\#0#  

#Part 1: Git basics  

##Introduction Sequence
####***Level 1: Introduction to Git Commits***  
>     git commit   
>     git commit

####***Level 2: Branching in Git***    
>     git branch bugFix  
>     git checkout bugFix  

####***Level 3: Merging in Git***  
>     git branch bugFix
>     git checkout bugFIx
>     git commit
>     git checkout master
>     git commit
>     git merge bugFix

####***Level 4: Rebase Introduction***   
>     git branch bugFix
>     git checkout bugFix
>     git commit
>     git checkout master
>     git commit
>     git checkout bugFix
>     git rebase master  

##Ramping up (Bonus Levels)  

####***Level 1: Detach yo' HEAD***    
>     git checkout C4  

####***Level 2: Relative Refs (^)***     
>     git checkout bugFix^  

####***Level 3: Relative Refs #2 (~)***    
>     git branch -f master C6
>     git checkout C1
>     git branch -f bugFix HEAD^  

####***Level 4: Reversing Changes in Git***     
>     git reset HEAD^
>     git checkout pushed
>     git revert pushed  

##Screenshots for the completed levels
###***Level 1***
![images](https://raw.githubusercontent.com/anuragshendge/HW/master/screenshots/row_1.png)
###***Level 2***
![images](https://raw.githubusercontent.com/anuragshendge/HW/master/screenshots/row_2.png)
###***Completion progress***
![images](https://raw.githubusercontent.com/anuragshendge/HW/master/screenshots/Learn%20Git%20Branching.png)


#Part 2: Hooks

##Post-commit content
```shell  
#!/bin/bash  
xdg-open http://www.ncsu.edu
```

##Screencast for the post-commit hook invocation

###Kindly Click on the image below for the screencast [you will be redirected to YouTube]
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/RUEj2Edu_Qk/0.jpg)](http://www.youtube.com/watch?v=RUEj2Edu_Qk)







