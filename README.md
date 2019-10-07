# The Tao Te Ching: An NLP Perspective

This repo contains code for analyzing over 170 translations of the Dao De Jing (Tao Te Ching) using natural language processing tools. It contains some nice visualizations for exploring specific translations in depth (we look at D.C. Lau 1963 and Stephen Mitchell 1988). It also contains code, for comparing hundreds of translations against one another. For example, we use [GloVe](https://nlp.stanford.edu/projects/glove/) embeddings to cluster translations in representative groups. We also identify chapters with controversial translations that vary considerably between authors and others with standrd translations that are consistent among authors.

We hope that this script will inspire similar analysis of other religious and philosophical texts using computational tools.


## Usage
This project does not have any special requirements if you are using Anaconda. If you are interested in reproducing the word frequency plots you need to install the [adjustText](https://github.com/Phlya/adjustText) package. This excellent package allows for overlaying text labels on points without having the labels overlap.

The notebook `scrape.ipynb` contains code for scarping html pages that contain the translations. We get our data from [Terebess Asia Online](https://terebess.hu/english/tao/_index.html), [Bureau of Public Secrets](http://www.bopsecrets.org/gateway/passages/tao-te-ching.htm), and [Side by Side Viewer](https://ttc.tasuki.org/display:Code:gff,sm,jhmd,jc,rh/). The notebook `utils.ipynb` contains some helper functions for cleaning the data and making nice visualizations. The notebook `analysis.ipynb` contains the analysis of the translations.


## Questions?
Feel free to reach out to me if you have any questions. This is [my website](abdulsaleh.github.io) and it has my contact info.
