# Spam classification using decision tree and support vector machine 


## Significance of the problem 

According to Dataprot(1) email spam costs businesses $20.5 billion every year. That is a serious problem - if we keep that in mind while we analyze our models, we will definitely go with the decision tree classifier as it has "low false positive rate".In other words, its True positive and True negative are higher or closer to 1 compared to other classifers.Therefore, it is relaiable model where its accurancy is high in preventing data breaching.

In addition to saving us fortunes of money from potential data breach, using this classifier will protect our personal, customers, and business partners data. It will also cause business interruptions can cost us losing time and money and there is a big chance that our customers/business partners will not trust doing business with us anymore.

If our data is compromised we will not only lose comapny's tangible and untangible assets. We could cost our customers and business partners fortunes as they have to deal with all that comes with their stolen data(identity theft is a major problem). 


(1)https://dataprot.net/statistics/spam-statistics/

(2)https://securityboulevard.com/2020/12/staggering-phishing-statistics-in-2020/#:~:text=The%20Shocking%20Phishing%20Statistics%20of%202020&text=Only%203%25%20of%20the%20users,the%20malicious%20link%20or%20attachment.



## Summary of out solution
We study the spam classification using decision tree and support vector machine. We tested our results on a publically available dataset and we reported the accuracy and the confusion matrices of both classifiers. Our metric for a successfull classsife is "low false positive rate" (false positive means the classifer sees the email as spam whereas the email is legit). Our analysis indicates that false positive in the decision on the our data gives us 0.07 where false postive rate on SVM is 0.15. Hence we recomend utilizing decision tree in the final production. While our analysis here is limited in terms of the number of classifiers and the size of the dataset, decision tree classifeir perform well and can potentially be utilized in applications.

## Conclusion 

From the confusion matrices of the decision tree and the SVM we see that the decision tree has better results for and less false positive and false negative detection of spam emails.



