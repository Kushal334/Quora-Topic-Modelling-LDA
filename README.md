# Quora Topic Modelling using Latent Dirichlet Allocation(LDA) and NMF

In this project, I have used Quora questions dataset to implement Latent Dirichlet Allocation (LDA) on and assign a topic to out of 10 
unsupervised modelled topics

# Data
The data consists of 404,289 Quora questions.Following is a snapshot of the data:
<br/>
![Image1](https://github.com/Aishwarya4823/Quora-Topic-Modelling-LDA-and-NMF/blob/master/Images/Questions_image.PNG)

# Method
1) First, we create a TF-IDF matrix from the given questions
2) Second, we use the LatentDirichletAllocation from sklearn.decomposition to create a LDA model that will assign highest probability words from our vocabulary (which consists of unique words taken from all the questions in our dataset) 
3)Eventually we select the topic which shows highest probability for each question for that particular question
4) We perform a similar approach for Non-Negative Matrix Factorization --><br/> We divide the TF-IDF matrix into two matrices : <br/>
1st) Topics Vs words and 2nd) words Vs question

# Result
![Image2](https://github.com/Aishwarya4823/Quora-Topic-Modelling-LDA-and-NMF/blob/master/Images/results_image.PNG)
<br/>
#0 --> **Technical/Books/Movies** related questions<br/>
#1 --> **Looks** related questions<br/>
#2 --> **QnA** related questions<br/>
#3 --> **Social Media** related questions<br/>
#4 --> **Life** related questions<br/>
#5 --> **People/Nationality** related questions<br/>
#6 --> **Language/Programming** related questions<br/>
#7 --> **Politics** related questions<br/>
#8 --> **Finance** related questions<br/>
#9 --> **Daily time** related questions<br/>
