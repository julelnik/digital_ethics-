# Digital Ethics concepts mapping

### Research question
How the concept space of the Digital Ethics research looks like?

The aim of the research is to identify the range of the topics around Digital Ethics studies.

### Code and data
<code>notebook.ipynb</code>: Python code with preprocessing and cleaning the text, visualisation of the discourse and creation of the dataframe for network analysis

The data consists of two files:
<li><code>all_texts.txt</code>: the final text file with 50 articles merged
<li><code>data_for_network.csv</code>: the dataframe file with 500 bigrams and their nodes weight 

<code>ethics.gephi</code>: the output Gephi network file

# Steps
### Data collection
Articles for each topic connected with Digital Ethics studies: AI, Robotics, Open Government, Open Source, Accessibility.
Articles were collected through Google Scholar, all texts were publicly available and free of charge. For each category, 10 of the most recent articles were collected, which included an ethical framework for study of Tech.

### Data preparation
Transforming pdf to text files, merging texts.

### Cleaning the text data
Lower case, identify and remove the stopwords, noise and punctuation.

### Creating the dataframe for the network analysis 
Dataframe based on the words appearance 2-grams and their nodes weight

### Creating the network 
Setting the nodes and edges size, calculating centrality and assigning communities.

### Additional analysis of the network
Community detection and clustering.

# Visualisation 

![alt-text-1](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/top20_words.png) ![alt-text-2](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/top20_bigrams.png)

### Exploration of the Digital Ethics discourse
![TOP20 words](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/top20_words.png) 

![TOP20 bigrams](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/top20_bigrams.png)

![Wordcloud](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/wordcloud.png)

# Final Result
![Ethics network](https://github.com/yuliianikolaenko/Data_Science_network_analysis/blob/main/images/ethics%20network.png)


