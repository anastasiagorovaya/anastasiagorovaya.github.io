# Git Intro: Have you ever made a Shopping List?
#### git milk?
#### May 27

Paragraph 1 If your answer to this question is "yes" then you are more than half way to understanding what **version control** is! If you have never made a grocery shopping list, we are going to make one right now using git. 

Step 1. You take a blank piece of paper = Your first **git repository**
(command > git init)

Step 2. List your groceries:
Version 1:

*pasta*
*tomato sauce*
*salad mix*

You know that you need to get something else but cannot quite remeber what it is. What you have right now is good enough for **the first version of your shopping list**!
(command > git add shopping_list.txt
command > git commit -m "create a shopping list" )

Then you realized that you forgot to add the most important item - CHOCOLATE! 

Version 2:

*pasta*
*tomato sauce*
*salad mix*
**chocolate**

(command > git add shopping_list.txt
command > git commit -m "add desert" )

Throughout the day you keep adding more and more items to this list and each time you make a new version which is a little bit longer than the previous one, unless you realize that you already have plenty of cholocate and decide to cross it out. But everyone knows that there is never too much chocolate. Git keeps track not only of your Additions but also items you Delete. 

The technical term for the chronological chain of the versions of your shopping list is **branch**, your main branch is called **master branch**

Imagine now that you are making a shopping list for the upcoming trip with your friends and you are the one to **finalize** the shopping list and go to a grocery store. Each one of your friends adds something to the list, but they are not going to message you the items one by one, right? they will send you a list that is based on what you have already written + things they need. The latter is very important: let's say your friend Suzy follows gluten free diet and wants to add a few things, she will copy your list and create her own to add things she needs, thus creating a new branch! she can add as many things to it throughourt the day as she wants

Master (your list):

*pasta*
*tomato sauce*
*salad mix*

Your friend Katherine's list (she is on gluten free diet):

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

