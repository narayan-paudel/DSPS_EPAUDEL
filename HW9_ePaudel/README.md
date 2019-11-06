The links for my visualization reviews are:
https://github.com/narayan-paudel/DSPS_jFitzgerald/blob/master/HW8/VisReview_ePaudel.md 
and https://github.com/narayan-paudel/DSPS_ejones/blob/master/HW8/VisReview_ePaudel.md.


## READING
actually watching: 

This webinar about how to write decently organized code (i.e. modular etc)

https://www.youtube.com/watch?v=Trar7GZOPl8&feature=youtu.be&utm_medium=email&utm_source=intercom&utm_campaign=modular-code-event


##  HW 1

Higgs Boson search from Kaggle. Work in groups as usual.

1 Download the Higgs boson data from Kaggle (programmatically within the notebook)

2 Split the provided training data into a training and a test set. 

3 Use a Random Forest and a Gradient Boosted Tree *Classifier* model to predict the label of the particles.
For each model calculate and discuss the training and test score results.

4 Produce a confusion matrix for each model and compare them

5 Use a Random Forest and a Gradient Boosted Tree *Regressor* model to predict the weight of the particles.
 
6 Calculate the L1 and L2 metrics of each model and compare them.

7 For the Random Forest classifier, explore the parameter space with the sklearn module sklearn.model_selection.RandomizedSearchCV using only the 4 best features as identified in the plot in step 3.

** this part takes some non trivial computational time! for me it took. If you start at the last minute you will not be able to deliver this part of the homework **

8 Generate an ROC curve plot and discuss it

EC and 667: 
     
   -Download the script provided in the kaggle challenge to validate your model. 

   -Generate an output file as required by this script for your best model
   
   -Report on the result
   
See the [higgsbosonSearch.ipynb](higgsbosonSearch.ipynb) sckeleton notebook



## HW 2

Work on your own.

You will receive an email with 2 names and github handles of classmates. Review their plots according to the things we discussed last lecture. You can discuss your review with others but each of you should submit a review for each of the plots

There will be detailed instructions in the email on how to review, what structure the review should have, what to focus on, etc. Please comply to the instructions. Upload the review on your github DSPS HW9 repo AND ALSO in your classmate's HW8 repo: 
- Fork your classmate's DSPS repo.
- Create a VisReview_\<firstLastname\>.md markdown file (it is important you do include your name or there will be conflicts with the other reviewer!)
- Add your comments on this file in *your fork of their repo* (you can do this on the web browser if you wish)
- Commit the new file to your own fork
- Submit a pull request 
- Add a link to your fork (of each of the 2 repos) in your HW9 readme file

Please note (and pay attention to the numbers): I will grade based on the content of the readme in *your fork of your classmate's repo in the HW8 readme*. Add a link to that file in your own *HW9 repo*. 
Make at least 3 recommandations for improvements and note at least one good feature of the visualization. 

Each review will be reviewed and graded *by me*. (Please take this homework seriously: one sentence generic reviews will be graded 0)

You willl lose 10% of the points if you did not submit a pull request. 
You will lose 10% of the points if you do not *accept the pull requests from your classmates by midnight on Wednesday!*

As soon as you receive the names check that your classmate has delivered a visualization in their HW9! If they did not you will not be able to do the homework. This is your responsibility. 

