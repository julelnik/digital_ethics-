# Digital Ethics concepts mapping

### Research question
How the concept space of the Digital Ethics research looks like?
###
Aim of the research: to identify the range of the topics around Digital Ethics studies.

#### Main tasks:
1. Data collection: articles for each topic connected with Digital Ethics studies: AI, Robotics, Open Government, Open Source, Accessibility.
Articles were collected through Google Scholar, all texts were publicly available and free of charge. For each category, 10 of the most recent articles were collected, which included an ethical framework for study of Tech.

2. Data preparation: transforming pdf to text files, merging texts.
The final text file *all_texts.txt*

3. Cleaning the text data: lower case, identify and remove the stopwords, noise and punctuation.

4. Creating the dataframe for the network analysis based on the words appearance 2-grams.
The final dataframe file *data_for_network.csv*

5. Creating the network: setting the nodes and edges size, calculating centrality and assigning communities.
The Gephi file *ethics.gephi*

6. Additional analysis of the network: community detection and clustering.

#### Exploration of the Digital Ethics discourse using the TOP 20 most frequent words and bigrams
![TOP20 words](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/top20_words.png)

![TOP20 bigrams](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/top20_bigrams.png)

#### Discourse space visualization with Wordcloud of TOP 100 frequent words 
![Wordcloud](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/wordcloud.png)

#### Final Network
![Ethics network](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/ethics%20network.png)


