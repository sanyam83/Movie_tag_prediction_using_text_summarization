# Movie_tag_prediction_using_text_summarization
## Movie Tag prediction from plot and reviews using Extractive neural Text summarization. Also Prediction of Genome scores prediction from Movie Lens dataset
First Part of notebook is prediction of Movie Tags using Extractive Text summarization. In this Pre trained 100D Glove embedding and Bi-LSTM is used .
Training Dataset Link Given below.

Second Part of Notebook is Prediction of Genome scores of Genome tags given in [Movie Lens 20M ](http://files.grouplens.org/datasets/movielens/ml-20m.zip )Dataset.
It takes Movie Plot and Reviews as input and predicts Genome Scores of all genome tags.

In Dataset of Movie Lens Genome Tags and Scores are features which contains how strongly movies exhibit particular properties represented by tags (atmospheric, thought-provoking, realistic, etc.).
I have used 100D Glove embedding and Bi-LSTM RNN and Dense Layer for prediction of 1128 tags.

Architecture of Model 

- ![ac](https://github.com/sanyam83/Movie_tag_prediction_using_text_summarization/blob/main/download.png?raw=true)

Longest length sentence is more than 2000 words but I have used max length of sentence  = 50 and can be taken till 1000 but more than that memory will run out or LSTM layer will be needed to reduce.

## Dataset src: 

[Movie Lens 20M ](http://files.grouplens.org/datasets/movielens/ml-20m.zip )

[plot data](https://www.kaggle.com/jrobischon/wikipedia-movie-plots)

[reviews dataset](https://www.kaggle.com/miazhx/metacritic-movie-reviews?select=metacritic_reviews.csv)

### Text summarization dataset:

[Text summarization dataset](https://drive.google.com/file/d/1JwO8I_IPMoPXfH9QVgirLiuLR9C3xWo7/view?usp=sharing)
