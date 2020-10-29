# NLP-FakeNewsClassification
## Natural Language Processing
### from Cornell University CS4740/5740 2020Fall

Work by Yuanhong Cao (yc2668@cornell.edu), Zeyu Chen (zc436@cornell.edu)

Link to raw data: https://drive.google.com/drive/folders/1Gm6Ky7IHB8YEo9UShq_vtU-8SJeBjPAa?usp=sharing 

In this project we will build an n-gram-based language model for fake news classification. We will also investigate a feature-based Naive Bayes model. The task we are faced with is to decide whether a news article is fake or real. While some fake articles are so absurd and nonsensical that one can clearly guess they are fake, most fake news is actually quite hard to detect. Various studies have shown that most people can have an error rate up to 50% depending on the theme of the article.

To help us approach this problem, we will use NLP techniques covered thus far to frame this as a (supervised) binary classification task, where each article will have a label  𝑦∈{0,1} , where 0 indicates a fake article and 1 indicates a real one. You will train and validate your two different models and then run them on a test data set with hidden  𝑦  labels. You will then submit the results on the test data set to Kaggle to participate in our class-wide competition!

The project is divided into six parts:

1. Dataset loading and preprocessing
2. Unsmoothed n-gram language model (LM): build the unsmoothed n-gram language model using our Fake News corpus.
3. Smoothed n-gram language model: build a smoothed version of the model from part 2.
4. Perplexity: compute perplexity for both the unsmoothed and smoothed model
5. Putting everything together and submitting the first model to Kaggle
6. Naive Bayes: build a feature-based Naive Bayes model to perform the same classification task. Compare the LM with Naive Bayes and identify the pros and cons of each.

Logistics: You should work in groups of 2 students. Students in the same group will get the same grade. Thus, you should make sure that everyone in your group contributes to the project.

Remember to form groups on BOTH CMS and Gradescope or not all group members will receive grades. You can use the Teammate Search option on Piazza to find a partner for this project.
Advice: Please complete the written parts of this notebook in a clear and informative way. This is where you get to show us that you understand not only what you are doing but also why and how you are doing it. So be clear, organized and concise; avoid vagueness and excess verbiage. Spend time doing error analysis for the models. This is how you understand the advantages and drawbacks of the systems you build.

It's also useful to think about how the theory of n-grams/Naive Bayes bridges with the real world application we are building. Think about what you expect from these models based on your current understanding, and then see if your expectation aligns with empirical results that you'll get.
