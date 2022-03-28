# sentiment-analysis

We have ten files from coders who annotated verses from the 1st book of Iliad (no names shared). In each file there are the following columns: polarity (the sentiment the reader felt while reading the verse), emotions, hero (Homer narrating or 
a hero talking). The goal of this repository is to build Machine Learning for automated sentiment annotation. 

1. In the first part we perform some cleaning on our data

2. In the second part we perform some preprocessing and visualize some interesting aspects of our data.

3. In the third part we perform classification, but we treat the problem as a regression problem, because we have a lot of annotators and we extract the mean polarity of all. So the models return continuous values and afterwards we perform the classification using an appropriate thresshold.

4. In the final part we scrapt an other translation of the same book, and we want to evaluate our best model on this.

