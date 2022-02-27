# arabic-wordcount
## Using Arabic WordCount on a Dataset in Python

### Main Objective
The repo is dedicated to show how we may utilize 'WordCount' module in Python to represent most repeated words in Arabic datasets & text in general, overcoming errors or problems that may occur as module isn't prepared to directly deal with Arabic. In order to properly use dataset then several steps of preprocessing were used.

### Dataset
This dataset consists of 2386 reviews of products collected mainly in Arabic, with some reviews are written in English or Arabizi. Reviews are classified in 3 categories: Positive, Negative and Neutral.

### Illustration of Steps
1. Needed modules were installed and dataset were imported
2. Dataset were splitted properly as it should be into two columns.
3. The sentences were tokenized into words and added to a list.
4. To avoid intervention of English, Arabizi and special characters, they were removed as a partial cleaning of the dataset.
5. We picked up the first 99 words, then created an instance of WordCount taking Arabic stopwords (imported from get_stop_words module) and Shorooq font as arguments.
6. To be represented properly in the plot, we reshaped the words and reversed their letters adding them to a list and finally converting it to Pandas series.
7. We generate the WordCount using Pandas series and plot the figure.

##### Code could be accessed through Google Colaboratory from [here](https://colab.research.google.com/drive/1o51921Xn0yKz38HZXZZKTwGk5ozZh45X?usp=sharing)
