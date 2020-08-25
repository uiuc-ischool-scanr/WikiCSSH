# WikiCSSH

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/uiuc-ischool-scanr/WikiCSSH/master?filepath=notebooks%2FDemo.ipynb)

If you are using WikiCSSH please cite the following papers:

> Han, Kanyao; Yang, Pingjing; Mishra, Shubhanshu; Diesner, Jana. 2020. “[WikiCSSH: Extracting Computer Science Subject Headings from Wikipedia](https://skg.kmi.open.ac.uk/SKG2020/papers/HAN_et_al_SKG_2020.pdf).” In Workshop on Scientific Knowledge Graphs (SKG 2020).

> Han, Kanyao; Yang, Pingjing; Mishra, Shubhanshu; Diesner, Jana. 2020. "[WikiCSSH - Computer Science Subject Headings from Wikipedia](https://doi.org/10.13012/B2IDB-0424970_V1)." University of Illinois at Urbana-Champaign. [https://doi.org/10.13012/B2IDB-0424970_V1](https://doi.org/10.13012/B2IDB-0424970_V1)

Download the WikiCSSH files from: [https://doi.org/10.13012/B2IDB-0424970_V1](https://doi.org/10.13012/B2IDB-0424970_V1) or from the *[data/v1](./data/v1)* folder.

The data contains the following files:

* `WikiCSSH_categories.csv` - Categories in WikiCSSH
* `WikiCSSH_category_links.csv` - Links between categories in WikiCSSH
* `Wikicssh_core_categories.csv` - Core categories as mentioned in the paper
* `WikiCSSH_category_links_all.csv` - Links between categories in WikiCSSH (includes a dummy category called <ROOT> which is parent of isolates and top level categories)
* `WikiCSSH_category2page.csv` - Links between Wikipedia pages and Wikipedia Categories in WikiCSSH
* `WikiCSSH_page2redirect.csv` - Links between Wikipedia pages and Wikipedia page redirects in WikiCSSH

Examples of using WikiCSSH can be found in the notebooks folder: 
* [Tagging_using_WikiCSSH.ipynb](./notebooks/Tagging_using_WikiCSSH.ipynb)
* [Visualize_WikiCSSH.ipynb](./notebooks/Visualize_WikiCSSH.ipynb)


## How it was generated

![Algorithm for generating WikiCSSH](https://user-images.githubusercontent.com/112678/90394544-7604ee80-e058-11ea-82c3-14e280aa6905.png)




