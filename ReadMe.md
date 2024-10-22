# Historical Network Analysis Workshop 

Author: Dr. Cindarella Petz ([![ORCID](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-6178-7332), [petz@ieg-mainz.de](mailto:petz@ieg-mainz.de))

[![DOI](https://zenodo.org/badge/872853563.svg)](https://doi.org/10.5281/zenodo.13951600)

This tutorial was part of the ["Exploring Connections" - Bring Your Own Data Lab of HERMES](https://hermes-hub.de/events/intern/byodlab20240917.html) hosted at [IEG Mainz](https://www.ieg-mainz.de/forschung/dh-lab) on Oct 17--18, 2024.


## Agenda: 
- Epistemology of network research and introduction to framework of modeling
- Best practices in humanities-based digital / computational research projects
- Conceptualize your network research project with expert- and peer2peer- mentoring exchange
- Historical network analysis with Python and Jupyter Notebooks using [networkX](https://networkx.org/): 
	- hands-on tutorials,
	- show cases based on [Petz, Cindarella and Pfeffer, Jürgen (2021) Configuration to Conviction, and Configuration to Conviction. Network Structures of Political Judiciary in the Austrian Corporate State. Social Networks, vol. 66, July 2021, pp. 185–201. DOI: 10.1016/j.socnet.2021.03.001](https://www.sciencedirect.com/science/article/pii/S037887332100023X?via\%3Dihub) and [Petz, Cindarella and Ghawi, Raji and Pfeﬀer, Jürgen (2022). Tracking the Evolution of Communities in a Social Network of Intellectual Influences. Journal of Historical Network Research 2022, vol. 7, number 1, pp. 114–154. DOI: 10.25517/jhnr.v7i1.146.](https://jhnr.net/articles/10.25517/jhnr.v7i1.146)
	- expert-mentoring on your individual datasets as part of the in-person workshop meeting
	
	[→ Click here for the .ipynb-Tutorial](https://github.com/cprog7/HNR_workshops/blob/main/Petz_2024_HNA-tutorial.ipynb)
 	
  
## Preparation:
- Please install [Anaconda](https://www.anaconda.com/products/individual) (or Miniconda) according to your operating system.  
Anaconda will automatically install Python, Jupyter Notebook, and allows you to use version control of any package you will install.
- Please create a new environment in Anaconda, e.g., "HNA", and install the following packages:
      - [networkX](https://networkx.org/)
      - [pandas](https://pandas.pydata.org/)
      - [matplotlib](https://matplotlib.org/)
      - [numpy](https://numpy.org/)
- You will find an introductory tutorial for Python using Jupyter Notebook here: [Introduction to Jupyter Notebooks with Python.ipynb ](https://github.com/ieg-dhr/ieg_workshops/blob/master/2021_02_networks_python/Introduction_Jupyter_Python.ipynb) and to [Introduction to Data Analysis with Python](https://github.com/ieg-dhr/ieg_workshops/blob/master/2021_02_networks_python/Intro_Data_Analysis_with_Python.ipynb). You have to open these files already using Jupyter Notebook. If you do not know how to do it, check this [documentation](https://docs.anaconda.com/ae-notebooks/user-guide/basic-tasks/apps/jupyter/index.html).


## Further Resources:
- Official networkX-Package Tutorial: [Scellato (2012) NetworkX: Network Analysis with Python](https://www.cl.cam.ac.uk/~cm542/teaching/2011/stna-pdfs/stna-lecture11.pdf) or [here](https://networkx.org/documentation/stable/tutorial.html)
- [Ladd et al (2017) Exploring and Analyzing Network Data with Python](https://programminghistorian.org/en/lessons/exploring-and-analyzing-network-data-with-python)
- [Ladd (n.a.) Network Analysis in Python](https://jrladd.com/networks/intro.html) and [Dynamic networks](https://jrladd.com/networks/special/dynamic.html)
- [Düring (2015) From Hermeneutics to Data to Networks Tutorial](https://programminghistorian.org/en/lessons/creating-network-diagrams-from-historical-sources)
- [Düring (n.a.) From text to data to networks Tutorial](http://martenduering.com/from-text-to-data-to-networks/)
- Course Syllabus with Tutorials: [Zhukov (2015): Structural Analysis and Visualization of Networks](http://www.leonidzhukov.net/hse/2015/networks/)
- Course Syllabus with Tutorials:  [Rossetti et al (n.a.) Complex Network Analysis](https://github.com/sna-unipi) and [Tutorials](https://github.com/sna-unipi/CNA_Tutorials)
- Course Syllabus with Tutorials:  [Keegan (n.a.) Network Science](https://github.com/cuinfoscience/INFO5613-Fall2021)
- Course Tutorials: [Shestakoff (2014) Social Networks](https://github.com/shestakoff/social_ntwks) 
- [Melo & Bernardi (2023) Dynamical Network Analysis](https://dynamical-network-analysis.readthedocs.io/en/latest/index.html) and [Tutorials](https://github.com/melomcr/dynetan_tutorial)
- [Klein (2022) Graph Theory and Graphs in Python](https://python-course.eu/applications-python/graphs-python.php)
- DataCamp: [Graph Optimization](https://www.datacamp.com/tutorial/networkx-python-graph-tutorial)
- Coursera: [Romera (n.a.) Applied Social Network Analysis with Python](https://www.coursera.org/learn/python-social-network-analysis#syllabus)
- [Coleman et al (n.a.) Social and Economic Networks Tutorial](https://datascience.quantecon.org/applications/networks.html)
- [Karna (2022) Network Analysis Tutorial with Python and QGIS](http://www.mrakhilesh.com/myweb/posts/network-analysis-python/)
- [Hagberg et al (2014) NetworkX Tutorial](https://networkx.github.io/documentation/networkx-1.9.1/_downloads/networkx_tutorial.pdf)
- [Zhiyzuo (2019) Network Analysis with Networkx](https://github.com/zhiyzuo/python-tutorial/blob/master/3-Network-Analysis-with-NetworkX.ipynb)

- Further list of ressources [HNR Community](https://historicalnetworkresearch.org/external-resources/), or [Awesome List Network Analysis](https://github.com/briatte/awesome-network-analysis?tab=readme-ov-file#python)

## Network analysis libraries for Python (non-exhaustive):
- Network analysis [networkX](https://networkx.org/)
- Interactive network visualization library [pyvis](https://pyvis.readthedocs.io/en/latest/)
- Network analysis [python-igraph](https://igraph.org/)
- Network analysis [graph-tool](https://graph-tool.skewed.de/)
- Large-scale network analysis [NetworKit](https://networkit.github.io/)
- Complex network analysis [Py3Plex](https://github.com/SkBlaz/py3plex)
- Graph neural networks [PyG](https://www.pyg.org/)
- Deep graph library [DGL](https://www.dgl.ai/)

## Recommended Reading (non-exhaustive):
- SNA & HNA: [Stegbauer, Christian and Häußling, Roger (2025, Eds.) Handbuch Netzwerkforschung. erw. Neuauflage, Springer VS Wiesbaden.](https://doi.org/10.1007/978-3-658-37507-2)
- HNA: [Düring, Martin and Eumann, Ulrich and Stark, Martin and von Keyserlingk, Linda (2016, Eds.) Handbuch Historische Netzwerkforschung: Grundlagen und Anwendungen. Münster: LIT Verlag.](https://lit-verlag.de/isbn/978-3-643-11705-2/)
- **Classical reading**: [Wasserman, Stanley and Faust, Katherine. 1994. Social Network Analysis: Methods and Applications. 1st ed. Structural Analysis in the Social Sciences, 8. New York: Cambridge University Press.](https://www.cambridge.org/core/books/social-network-analysis/90030086891EB3491D096034684EFFB8)
- **Great first introduction**: Jansen, Dorothea. 2006. Einführung in die Netzwerkanalyse. Grundlagen, Methoden,
Forschungsbeispiele. 3. überarbeitete Auflage. VS Verlag für Sozialwissenschaften.
- SNA: [Hennig, Marina and Brandes, Ulrik and Pfeffer, Jürgen and Mergel, Ines. Studying Social Networks: A Guide to Empirical Research. Campus Verlag, 2012.](https://www.campus.de/buecher-campus-verlag/wissenschaft/soziologie/studying_social_networks-4273.html?srsltid=AfmBOoplqKTpwUUqbqBa4ADIea7DyZPCsbenZiqUHiBJJPE2pzsfjJEd)

- **Special Mention**: Recommended reading for robustness evaluation in HNA: [de Valeriola, Sébastien. 2021. Can historians trust centrality? Historical network analysis and centrality metrics robustness. Journal of Historical Network Research 6 (1). https://doi.org/10.
25517/jhnr.v6i1.105.](https://doi.org/10.25517/jhnr.v6i1.105)

- Discover further HNA studies at [Journal of Historical Network Research](https://jhnr.net/)


