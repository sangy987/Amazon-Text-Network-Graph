# Amazon Text Network Graph
This is a Text Network Graph comprising of the words taken from the Amazon dataset. This is very helpful because:

*   Identify the clusters of words that occur together
*   Study the realtionship between words
*   Visualise which words have greater weightage in the dataset


![bokeh_plot(2)](https://user-images.githubusercontent.com/40862259/147098163-000f9970-4b0e-4bee-b753-66dfca0ed342.png)

### Also, we can observe the outliers in the data.
![bokeh_plot(5)](https://user-images.githubusercontent.com/40862259/147187156-e052f4e4-d6dd-45e0-a68b-c22f14ac1679.png)
### The HTML page of the rendered bokeh plot. [https://sangy987.github.io/Amazon-Text-Network-Graph/](https://sangy987.github.io/Amazon-Text-Network-Graph/)

---
# Process



*   I have taken the clean_amazon_file.txt which contains words from the [Amazon Software dataset](http://deepyeti.ucsd.edu/jianmo/amazon/categoryFilesSmall/Software_5.json.gz/) **summary** column. This file contains words that have been cleaned and parsed.
*   Initialised the graph using the networkx module.

*   Then, I have taken the 100 most commonly occuring words and added them as Nodes
*   Next, I have added the 1000 most common bigrams and added them as edges. For both nodes and edges, the weights were the frequency of the data in the graph.





