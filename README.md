### 🧮🧬 Alex Diaz-Papkovich, PhD 🧬🧮

I'm a statistician and data scientist. I'm currently at Brown University working as a postdoctoral research associate at the Data Science Institute with [Sohini Ramachandran](https://www.brown.edu/Research/Ramachandran_Lab/research/). My PhD work was at McGill University in [Quantitative Life Sciences](https://www.mcgill.ca/qls/) with [Simon Gravel](https://gravellab.github.io/), where I studied topological data analysis methods for genetic data. You can find my published research on [Google Scholar](https://scholar.google.ca/citations?hl=en&user=CwGsVS0AAAAJ).

I also enjoy collecting data on a variety of topics. Some of my side-projects include [tracking the length of the Rideau Canal skating season](https://github.com/diazale/skateway) and [collecting news stories of traffic violence](https://github.com/diazale/death_by_car).

Some of my academic research:

### Non-linear dimensionality reduction for visualizing population genetic data

UMAP is an efficient method to visualize biobank data. You can find structure in your data (i.e. [population structure](https://en.wikipedia.org/wiki/Population_structure_(genetics))) related to factors like demographic history or biobank sampling methodology. When you colour in the visualizations with other data, like geography or phenotypic measures, you can see lots of patterns and study them further. You can also work in 3D and get creative, doing stuff like converting UMAP's $(x,y,z)$ coordinates to RGB positions to create colour maps.

Paper: [UMAP reveals cryptic population structure and phenotype heterogeneity in large genomic cohorts](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1008432), Diaz-Papkovich et al, PLoS Genetics, 2019.

Related Github repositories:
* [Code for the paper](https://github.com/diazale/gt-dimred)
* [Interactive Python notebook with data from the Thousand Genomes Project](https://github.com/diazale/1KGP_dimred)
* I also have [code](https://github.com/diazale/umap_review/) for a [review paper](https://www.nature.com/articles/s10038-020-00851-4) of UMAP in population genetics

### Stratification of biobank data

Though UMAP tends to generate clusters, it is not a clustering algorithm. To extract clusters from UMAP data, we use a density-based method called HDBSCAN. We can use this for [stratification](https://en.wikipedia.org/wiki/Stratified_sampling) to get a better grasp of the population structure in our data, study how methods like polygenic scores transfer between populations, and do QC on biobank data.

Preprint: [Topological stratification of continuous genetic variation in large biobanks](https://www.biorxiv.org/content/10.1101/2023.07.06.548007v1.abstract), Diaz-Papkovich et al, bioRxiv, 2023.

Related Github repositories:
* [Code and demo scripts using data from the Thousand Genomes Project](https://github.com/diazale/topstrat/)

<!--
**diazale/diazale** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
