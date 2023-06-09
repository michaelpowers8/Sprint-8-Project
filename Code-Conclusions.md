<h2>INITIAL TEST CONCLUSION</h2>
<div class="paragraph">
Initial valid f1 scores for both models are right at 0.54. However, both models 
got these scores in opposite ways. The decision tree classifier had high recall score 
and low precision which means it needs higher precision which calls for a need of 
downsampling to increase precision. However, the random forest has low recall and 
high precision. This model would benefit more from upsampling to increase recall. 
I will be experimenting with upsampling and downsampling both models though to 
find all possible model improvements since 0.54 is still not a great score regardless.
</div>

<h2>UPSAMPLING CONCLUSION</h2>
<div class="paragraph">
After completing the upsampling, the Decision Tree Classifier had an f1 test score of 0.536 
which occured with high recall of 0.667 and low precision of 0.448. This means this model is good 
at having fewer false negatives, but has many false positives. The Random Forest Classifier's 
f1 test score was 0.587 with a recall score of 0.546 and a precision score of 0.635. 
This means the random forest has more false negatives, and fewer false positives. 
In final, the decision needs downsampling to improve precision, but the random forest 
would likely need slightly higher upsampling to increase recall.
</div>

<h2>DOWNSAMPLING CONCLUSION</h2>
<div class="paragraph">
After completing the downsampling, the Decision Tree Classifier had an 
f1 test score of 0.582 which occured with high recall of 0.628 and low precision of 0.541. 
This means this model is good at having fewer false negatives, but has more false positives. 
The Random Forest Classifier's f1 test score was 0.576 with a recall score of 0.596 and a precision score of 0.558. 
This means the random forest is more balanced, but is slightly more common to have false positives, 
and fewer false negatives, but not by a lot. 
In final, both models would likely need higher upsampling to increase recall.
</div>
