#Git milk??
## Intro to understanding Git
### May 27

**Have you ever made a shopping list?**
If your answer to this question is "yes" then you are more than half way to understanding what **version control** is! If you have never made a grocery shopping list, we are going to make one right now using git. 

Step 1. 
You take a blank piece of paper = You are initiating your first **git repository** 
(command prompt > git init)

Step 2. List your groceries:

*pasta*

*tomato sauce*

*salad mix*

You know that you need to get something else but cannot quite remember what it is... But what you have right now is already good enough for **the first version of your shopping list**!

(command prompt> git add shopping_list.txt
command prompt> git commit -m "create a shopping list" )

Then you realized that you forgot to add the most important item - CHOCOLATE! 

Version 2:

*pasta*

*tomato sauce*

*salad mix*

**chocolate**

(command prompt> git add shopping_list.txt
command prompt> git commit -m "add desert" )

Throughout the day you keep adding more and more items to this list and each time you make a new version, and it is a little bit longer than the previous one... unless you realize that you already have plenty of cholocate and decide to cross it out. But everyone knows that there is never too much chocolate. Git keeps track not only of your Additions but also items you Delete. 

The technical term for the chronological chain of versions of your shopping list is **branch**, your main branch is called **master branch**

Imagine now that you are making a shopping list for the upcoming trip with your friends and you are the one to **finalize** the shopping list and go to a grocery store. Each one of your friends adds something to the list, but they are not going to message you the items one by one, right? they will send you a list that is based on what you have already written + things they need. The latter is very important: let's say your friend Katherine ue follows gluten free diet and wants to add a few things. (In her mind) she will 'copy' your list and create her own adding things she needs, thus creating a new branch! she can add as many things to it throughourt the day as she wants

Master (your list):

*pasta*

*tomato sauce*

*salad mix*

Your friend Katherine list (she is on gluten free diet):

*pasta*

*tomato sauce*

*salad mix*

*gluten free pasta*

*rice crackers*

Your friend George's list(he is vegan):

*pasta*

*tomato sauce*

*salad mix*

*tofu*

*cashew cheese

Each one of your friend's lists is a separate branch, that develops parallel to the main list. Eventually all these lists, the very final versions of Katherine's and George's shopping lists will be **merged** into the master branch for you to go to purchase all these things. 

(this is not the only way to merge!)
How the merge is done: 
take your list 
command prompt> git checkout master

add Katherine's list
command prompt> git merge katherineslist


