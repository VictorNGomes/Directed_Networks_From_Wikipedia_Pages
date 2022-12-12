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
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/degree_centrality.png" ></p>

**Closeness Centrality:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/closeness_centrality.png" ></p>

**Betweenness Centrality:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/betweenness_centrality.png" ></p>

**Eigenvector Centrality:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/eigenvector_centrality.png" ></p>

**Core Decomposition:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/k-core_sociopatterns.png" ></p>

**Comparison between metrics:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/all.png" ></p>

**Probability Density Function:**
<p align="center"><img width="600px" src= "https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/images/probability_density_function%20(1).png" ></p>

## Results:
Discussions of the results are then available at [Results](https://www.loom.com/share/1c6300610a394df09d4a64f7db12b057).

To run this project just access [Pipeline](https://github.com/VictorNGomes/Directed_Networks_From_Wikipedia_Pages/blob/main/notebooks/Pipeline.ipynb) and execute the steps described in the file. 

## Students participating in the project:
  
  [Victor do Nascimento Gomes](https://github.com/VictorNGomes)
  
  [Claudiano Leonardo da Silva](https://github.com/ClaudianoLeonardo)
  
  [David Willian Pereira Jatobá](https://github.com/DavidWillian7)
  
  ## References:
[Algorithm and Data Structure 2](https://github.com/ivanovitchm/datastructure)

[Wikipedia](https://www.wikipedia.org/)
