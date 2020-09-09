# Local uncertainty indexes for Norwegian counties

<a href="https://oskran.github.io/localUncertainty/docs/localUncertainty.html">Guide to creating the indexes</a>

<a href="https://oskran.github.io/localUncertainty/docs/Recipe.pdf">Short summary of calculations</a>

This project seeks to estimate local uncertainty in Norway using textual news data. It is inspired by the [Economic Policy Uncertainty Index](http://www.policyuncertainty.com/index.html) and the [Financial News Index](https://www.retriever-info.com/fni/), in addition to several papers by [Vegard H. Larsen](https://www.bi.edu/about-bi/employees/department-of-economics/vegard-hoghaug-larsen/) and [Leif Anders Thorsrud](https://www.bi.edu/about-bi/employees/department-of-economics/leif-anders-thorsrud/). 

I use the national library of Norway's API to collect data about the use of uncertainty words over time. Because of limitations to the API, this project uses monthly word counts for each paper.


![Local uncertainty 2000:2007](docs/localUncertainty_files/figure-html/local_uncertianty_index_2000_2007-1.png)
![Local uncertainty 2008:2011](docs/localUncertainty_files/figure-html/local_uncertianty_2008_2011-1.png)
