A detailed analysis on the reserch paper name as  "Gender, Topic, and Audience Response: An Analysis of User-Generated Content on Facebook" to answer the following questions:



1. The authors used Facebook posts for their analysis, but also, they also collected additional features about the posts, what are these features? 

Solution: 

In addition to the Facebook posts the authors included metadata that incorporates the number of views, post times, text content of the post, number of comments and likes within three days for each status update. Besides, they use demographic information about the post such as age, gender, days of registration, etc. These features offered understanding and contextual information/ use characteristics related to Facebook posts. 

 

2. List the pre-processing steps that the dataset of posts and other features went through.

Solution: 

The dataset of posts and other features underwent multiple pre-processing steps. The data was cleaned before proceeding with the topic models.

 First and foremost, the text content was tokenized utilizing the Openly toolkit, stemmed with a Porter stemmer, and lowercase. 

The experimenters removed the punctuation by replacing URLs, email addresses, and numbers were replaced with tags. 

Next, the posts were represented as unigrams (single words) and bigrams (word pairs). Thereafter, high and low-frequency unigrams and bigrams were pruned to minimize noise and vocabulary size. A stop-word list was applied to exclude common words. 

Finally, the topic models were built from the remaining posts.



  

3. Describe how they selected the number of topics and how many associated keywords they used for each topic in their topics modeling procedure. 



Solution:

The authors selected the number of topics by using LDA (Latent Dirichlet Allocation) to the dataset for the topic modeling procedure. They experimented with various numbers of topics and discovered that using 50 latent topics produced models that were more interpretable to human judges. For each of the 50 topics, the authors generated dictionaries incorporating the 500 terms that were mostly associated with each topic. 

For instance, the authors found nearly 50% of the status updates had less than eight n-grams after pruning. 

Experts familiar with social networking site content manually labeled each dictionary to present insights into the topics recognized by the model. The dictionary-based approach was preferred because of its scalability and adaptability. 

 

4. In the results and discussion section, the authors showed three figures 

1.a, a.b, and 1.c. 

Write a summary of 2-3 sentences about each one of these plots.

 

Solution:

 

Figure 1(a) presents the distribution of topics in the status updates, specifying the percentage of updates related to each topic. It also exhibits that Facebook users frequently disclose personal information, discuss holidays and family events, and engage in philosophical discussions. Some of the topics for this section include thankfulness, birthday, sleep, work, house, food, sports, and many more. 

 

Figure 1(b) illustrates the distinction in topic distributions between the adult male and female aged 25 and older. It highlights that women's posts primarily focus on relationships and personal details such as family fun, birthday, father’s day, etc. . 

On the other hand , men are more inclined to discuss sports and abstract concepts including politics, christianity, and more.

 

Figure 1(c) indicates the topic distributions between teenagers (girls and boys) aged between 13 to 17. It discovers that there are fewer gender differences among teens. Both girls and boys are being more aligned in their popular topics, such as complaining, relationships, and slang usage. This can be because teens spend most time in school together and are under peer influence.

Nevertheless, some patterns for adults and teens were similar such as teen boys less talk about family events, while teen girls talke limited about sports on social network sites. 

 

5.What are the author's findings about their research questions listed below.

 

a. Are there gender differences in topics on SNS? 

Solution:

The authors found major gender differences in topics on SNS (Social Network Sites). Women were more likely to discuss personal issues and family-related events that include love, birthday, thankfulness, and many more. 

On the contrary, men were more inclined to post about sports, politics and philosophical topics. 

Moreover, the author also concluded that the women are more likely to catch attention on SSN withstanding gender expectations. 

 

b. Which topics are associated with greater audience responsiveness?

Solution:

This article indicates that there are certain topics that are associated with greater audience responsiveness. For example, SNS posts about asking for support or prayers tended to receive more comments, while topics like sleep or Christianity received lesser comments. 

The study also showed nuances in audience responsiveness concerning likes versus comments for different topics. Also, they concluded that the individuals who focus on content may enhance their experience on SNS. 

 

6: Use the Sentiment Analysis and Opinion Mining and define Unigram and Bigram.

Solution:

Unigram is an individual word (i.e, good, nice) which is amongst the most common features used in traditional topic-based text classification. Unigram presents a basic unit of analysis. A unigram model considers each word independently without considering the relationship between words in the language modeling context. 

For instance, if the sentence is “the paper is informative”, each word in the sentence (“the”, “paper”, “is”, “informative”) is considered as unigram. 

A bigram is a sequence of two adjacent words or tokens in a text. Bigram considers pairs of consecutive words in a sentence. They help capture contextual information by considering the relationship between adjoining words. 

For example, if the sentence is “the paper is informative”, bigrams are “the paper”, “paper is”, “is informative”. 

 

7.Describe in one paragraph only how part-of-speech tagging might be impacting sentiment analysis (15 Points). 

 

Solution:

Part-of-speech tagging plays a pivotal role in sentiment analysis. It provides insights into the grammatical structure and context of words within a sentence. The identification of parts of speech such as nouns, verbs, adjectives helps sentiment analysis models to better understand the relationships between words and their roles in communicating sentiment. 

 

Part-of-speech tagging allows distinguishing among positive and negative adjectives, permitting sentiment analysis models to weigh the emotional tone more accurately. 

 

It also contributes significantly to the nuanced interpretation of sentiment in natural language, improving the effectiveness of sentiment analysis.
