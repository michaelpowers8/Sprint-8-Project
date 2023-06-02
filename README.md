<h1>Project description</h1><div class="paragraph">
Beta Bank customers are leaving: little by little, chipping away every month. 
The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
</div>
<div class="paragraph">We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.</div><div class="paragraph">Build a model with the maximum possible <em>F1</em> score. To pass the project, you need an <em>F1</em> score of at least 0.59. Check the <em>F1</em> for the test set.</div><div class="paragraph">Additionally, measure the <em>AUC-ROC</em> metric and compare it with the <em>F1</em>.</div><h3>Project instructions</h3><ol start="1"><li>Download and prepare the data. Explain the procedure.</li><li>Examine the balance of classes. Train the model without taking into account the imbalance. Briefly describe your findings.</li><li>Improve the quality of the model. Make sure you use at least two approaches to fixing class imbalance. Use the training set to pick the best parameters. Train different models on training and validation sets. Find the best one. Briefly describe your findings.</li><li>Perform the final testing.</li></ol><h3>Data description</h3><div class="paragraph">The data can be found in <code class="code-inline code-inline_theme_light">/datasets/Churn.csv</code> file. <a href="https://practicum-content.s3.us-west-1.amazonaws.com/datasets/Churn.csv">Download the dataset.</a></div><div class="paragraph paragraph_has-one-child"><strong>Features</strong></div><ul><li><em>RowNumber</em> — data string index</li><li><em>CustomerId</em> — unique customer identifier</li><li><em>Surname</em> — surname</li><li><em>CreditScore</em> — credit score</li><li><em>Geography</em> — country of residence</li><li><em>Gender</em> — gender</li><li><em>Age</em> — age</li><li><em>Tenure</em> — period of maturation for a customer’s fixed deposit (years)</li><li><em>Balance</em> — account balance</li><li><em>NumOfProducts</em> — number of banking products used by the customer</li><li><em>HasCrCard</em> — customer has a credit card</li><li><em>IsActiveMember</em> — customer’s activeness</li><li><em>EstimatedSalary</em> — estimated salary</li></ul><div class="paragraph paragraph_has-one-child"><strong>Target</strong></div><ul><li><em>Exited</em> — сustomer has left</li></ul><h1>Project evaluation</h1><div class="paragraph">We’ve put together the evaluation criteria for the project. Read this carefully before moving on to the task.</div><div class="paragraph">Here’s what the reviewers will look at when reviewing your project:</div><ul><li>How did you prepare the data for training? Have you processed all of the feature types?</li><li>Have you explained the preprocessing steps well enough?</li><li>How did you investigate the balance of classes?</li><li>Did you study the model without taking into account the imbalance of classes?</li><li>What are your findings about the task research?</li><li>Have you correctly split the data into sets?</li><li>How have you worked with the imbalance of classes?</li><li>Did you use at least two techniques for imbalance fixing?</li><li>Have you performed the model training, validation, and final testing correctly?</li><li>How high is your <em>F1</em> score?</li><li>Did you examine the <em>AUC-ROC</em> values?</li><li>Have you kept to the project structure and kept the code neat?</li></ul><div class="paragraph">You have your takeaway sheets and chapter summaries, so you are ready to proceed to the project.</div><div class="paragraph">Good luck!</div></div>
