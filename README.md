# GitHub Tutorial

_by Jeremy Eisner_

---
## Git vs. GitHub

Git and Github are very similar to eachother, but they are two completely different tools.
here is the rundown:

###Git 

* is essentially a snapshot of your code,  

  * is known as version control.




 
###Github

* is an area that stores code online   
or what is known as a cloud 
* It is also used to work on diffent parts of code  with other people.
  
 * The cool part is that you don't have to be on the same computer together  since you can exchange parts of code via internet to partners who can edit, fix, change, or work with the code to make it work





---
## Initial Setup  


###Account setup
To setup an account on github, you need to go to this website  
https://github.com/

Follow these directions to create an account

1. When you arrive at the site, click the green button on the  top right corner that says "sign up"
   * Create a username and password that you will remember and enter you email as well> click Create an Account  
    (the green button at the bottom of the page)
2. Then choose a payment plan that works for you and Press the "Finish sign up button" ( green button at the bottom of the page),   
   *_NOTE_: this tutorial will only use the free account
3  You should see your dashboard, if you did, WELCOME TO GITHUB!!!

###Setting up your SSH keys 

1. On the top right of your dashboard, you should see your profile icon, click it 
  * then click "settings"
2. On the left sidebar, click "SSH Key"
    * click "add SSH Key(top right of page)"  
       * Tyoe in the name of your command line program where it says "Title"
    
3. _Note_: This part assumes you have either nitrous.io or c9.io as your command line
On your command line program, go to your dashboard> click the gear icon on the top right
    * press "SSH Key"
    * double click the the SSH code, then copy and paste it to the box below the "title" box on github.  
4. Go to your command line and type in this line of code: ssh -T git@github.com  

       

---
## Repository Setup

###How to work with git?


####To Make a repo
1.  go to github.com and on your dashboard, you should see a green button on the middle right that says "new Respoisitory"
2.  give it a name , and a description and then create repo 
      *it should now  be on github, but you need it in the command line...
3. go to the repo on github and double click on the SSH Url on the middle right and copy it.
4. Lastly, go to your command line and type git clone (pasted url) and press enter.





1. To start git in your command line, type git init
2. And when you want to save the code, type this line of code FIRST: git add (file name) and press enter
3. THEN, type git commit -m "(short present tense specific action on (file name)" and press enter.
   * your code should be saved to your command line
4. Finally, type in git push to bring it up to your repo.


---
## Workflow & Commands