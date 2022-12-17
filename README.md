# Directed Networks From Wikipedia Pages

## About this project:
This project is part of the course [Algorithm and Data Structure 2](https://github.com/ivanovitchm/datastructure) from the Federal University of Rio Grande do Norte.
The objective of this work is to generate a network (graph) directed from the links of the Wikipedia pages and perform an analysis applying network concepts. To generate the network initially a Wikipedia page is provided, then the network depth level is limited to 2. Stable diffusion was the seed chosen to generate the network.

## Pipeline:
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/pipeline.png" ></p>

For this project, a pipeline was built to collect data and treat them. Pipeline is a collection of processes that transform raw data into processed data. The pipeline built for this project is available at [Pipeline](https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/notebooks/Pipeline.ipynb)


## Project description:
<p align="center"><img src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/stb.png" ></p>

Stable Diffusion is a deep learning, text-to-image model released in 2022. It is primarily used to generate detailed images conditioned on text descriptions, though it can also be applied to other tasks such as inpainting, outpainting, and generating image-to-image translations guided by a text prompt.

### Metrics:
**Degree Centrality:** Degree centrality is the number of vertices connections 

**Closeness Centrality:** Average distance to all other vertices

**Betweenness Centrality:** Position on the shortest path

**Eigenvector Centrality:** Authority score based on the score of the neighbors

### Analyzes:
**Degree Centrality:**

The image below shows the nodes with degree greater than 300. It is noticed that although the network has more than 2000 nodes (pages), not many have a large number of interactions.
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/dev/images/degree_centrality.png" ></p>

**Closeness Centrality:**

The image shows nodes with closeness centrality between 0.51 and 1. Considering that this metric measures the average distance of a node in relation to the others, it can be seen that most of these nodes in this network are distant, because in the considered interval few nodes appear.
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/dev/images/closeness_centrality.png" ></p>

**Betweenness Centrality:**

The image shows nodes with betweenness centrality between 0.2% and 0.33%(maximum value of the metric for this network). Considering the limits of the intervals, it can be concluded that there are not many nodes that are part of the shortest path between the other nodes in the network.
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/dev/images/betweenness_centrality.png" ></p>

**Eigenvector Centrality:**

This metric shows how important the node is, that is, if it is connected to important neighbors. The image shows nodes with eigenvector eentrality greater than 0.8, so you can see that this network has many "important" nodes.
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/dev/images/eigenvector_centrality.png" ></p>

**Core Decomposition:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/dev/images/k-core_sociopatterns.png" ></p>

**Comparison between metrics:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/all.png" ></p>

**Probability Density Function:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/probability_density_function%20(1).png" ></p>

## Results:
Discussions of the results are then available at [Results](https://www.loom.com/share/1c6300610a394df09d4a64f7db12b057).

To run this project just access [Pipeline](https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/notebooks/Pipeline.ipynb) and execute the steps described in the file.

## Visualization
With the help of tools such as [Gephi](https://gephi.org/), [Retina](https://ouestware.gitlab.io/retina/beta/), and Gephisto, it is possible to have a better view of the networks and the metrics applied to carry out the analysis.

**Gephi**

The .graphml file obtained through the scripts contained in the notebooks was loaded into [Gephi](https://gephi.org/) and colored based on the Modularity Class metric. The Modularity Class is a community detection metric, and in this case 7 were obtained.

<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/gephi_images/full_view.png" ></p>

Through gephi it is possible to perform filtering that can help us to understand the network. For example, in the case of the figure below, only nodes with in-degree above 89 are shown. From this visualization, it can be seen that there is a community (green color) that has the largest number of nodes with high entry degrees, which, in this context, represent a group of web pages that are frequently cited from the seed stable diffusion

<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/gephi_images/net89-max.png" ></p>

It is possible to visualize and interact with this graph [here](https://victorngomes.github.io/Deploy_Network_Visualization/).

## Students participating in the project:
  
  [Victor do Nascimento Gomes](https://github.com/VictorNGomes)
  
  [Claudiano Leonardo da Silva](https://github.com/ClaudianoLeonardo)
  
  [David Willian Pereira Jatobá](https://github.com/DavidWillian7)
  
  ## References:
[Algorithm and Data Structure 2](https://github.com/ivanovitchm/datastructure)

[Wikipedia](https://www.wikipedia.org/)
