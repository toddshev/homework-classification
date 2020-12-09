# Homework - Classification

### Resampling:
#### Which model had the best balanced accuracy score?
Naiive Random Oversampling had the highest score at .67, though 3 of the 4 scores were very close, with undersampling (3) being the lowest

#### Which model had the best recall score?
SMOTE Oversampling was by far the winner on recall, which is the minimization of false negatives.  A distant second was Naiive Random Oversampling

#### Which model had the best geometric mean score?
Naiive Random Oversampling wins again at .67.  But once again, the scores were very close with undersampling coming in last again.
It is not surprising that NROS had the highest GMS since it scored high previously.

### Ensemble:
#### Which model had the best balanced accuracy score?
Easy Ensemble had an extremely high score of .92.  Though the Balanced Random Forest had a very respectable .79.

#### Which model had the best recall score?
Easy Ensemble won by a nose, once again.  Though very close with the scores of .90 and .87, respectively.

#### Which model had the best geometric mean score?
The winner again, not surprisingly, is Easy Ensemble.
However, with scores this high the model is suspect.  There were extremely few false positives and false negatives, which seems unlikely. As a Lending Club investor, I can assure you they are not that good at predicting loan risk.

There may be a condition of "over-fitting" by using the Easy Ensemble model.  In practice, BRF is very common and with respectable scores, may be just as useful as EE.

_Both models should be considered when performing analysis._

#### What are the top three features?
* Total Receipt of Principle
* Total Payment
* Total Payment Invoiced/Investment (not clear what inv stands for) 
