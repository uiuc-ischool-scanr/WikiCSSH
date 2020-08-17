# WikiCSSH


If you are using WikiCSSH please cite the following papers:

> Han, Kanyao, Pingjing Yang, Shubhanshu Mishra, and Jana Diesner. 2020. “[WikiCSSH: Extracting Computer Science Subject Headings from Wikipedia](https://skg.kmi.open.ac.uk/SKG2020/papers/HAN_et_al_SKG_2020.pdf).” In Workshop on Scientific Knowledge Graphs (SKG 2020).

> Han, Kanyao; Yang, Pingjin; Mishra, Shubhanshu; Diesner, Jana (2020) WikiCSSH - Computer Science Subject Headings from Wikipedia. University of Illinois at Urbana-Champaign. https://doi.org/10.13012/B2IDB-0424970_V1

Download the WikiCSSH files from: https://doi.org/10.13012/B2IDB-0424970_V1

The data contains the following files:

* WikiCSSH_categories.csv - Categories in WikiCSSH
* WikiCSSH_category_links.csv - Links between categories in WikiCSSH
* Wikicssh_core_categories.csv - Core categories as mentioned in the paper
* WikiCSSH_category_links_all.csv - Links between categories in WikiCSSH (includes a dummy category called <ROOT> which is parent of isolates and top level * categories)
* WikiCSSH_category2page.csv - Links between Wikipedia pages and Wikipedia Categories in WikiCSSH
* WikiCSSH_page2redirect.csv - Links between Wikipedia pages and Wikipedia page redirects in WikiCSSH

Examples of using WikiCSSH can be found in the notebooks folder: 
* [Tagging_using_WikiCSSH.ipynb](./notebooks/Tagging_using_WikiCSSH.ipynb)
* [Visualize_WikiCSSH.ipynb](./notebooks/Visualize_WikiCSSH.ipynb)


## How it was generated

![Algorithm for generating WikiCSSH](https://user-images.githubusercontent.com/112678/90394544-7604ee80-e058-11ea-82c3-14e280aa6905.png)




