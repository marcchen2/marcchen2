### Hello! I'm Marc Chen. 

- I'm currently a visiting ML researcher at the University of Waterloo, where I support the computational finance research of Profs. [Yuying Li](https://cs.uwaterloo.ca/~yuying/) and [Peter Forsyth](https://cs.uwaterloo.ca/~paforsyt/).
- I recently graduated from uWaterloo with a Master of Mathematics in Data Science, and completed my thesis, titled ["A Robust NN Approach to Optimal Decumulation and Factor Investing"](https://uwspace.uwaterloo.ca/handle/10012/19874).
- My co-authored ML finance research has been submitted to the Journal of Applied Mathematics and Computation, and is available [as a pre-print](https://arxiv.org/abs/2306.10582). 
- On this personal Github, I share select projects from my research experiences and independent side projects.

### Highlighted Projects:

#### [Market Data Bootstrapper](https://github.com/marcchen2/market_data_bootstrap/)  


<p>
    <img src="block_bootstrap.png" width="300"  /><br> 
    <em > Diagram credit to
<a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0131111">El Anbari, Abeer, and Ptitsyn (2015)</a>
</em>
</p>

A common problem in ML finance research is the availability of asset return data. The single realized historical path is insufficient for robust training of ML investment recommendation models. It is therefore necessary to generate additional time series data with similar statistical properties as real assets' return paths. One of the methods most widely accepted to be the gold standard by finance practioners is stationary block bootstrapping (Patton et al., 2009) of historical return data. This repo implements the method in Python and Numpy (PyTorch version forthcoming). This tool was implemented as part of a larger ML pipeline I implemented to create optimal portfolio management strategies for my Masters research.


#### De-noising genomic sequencing data with Residual Networks
- Consulting for a startup genomics imaging company: Creating custom implementation of the [AtacWorks](https://github.com/NVIDIA-Genomics-Research/AtacWorks) deep learning package into the company's workflow to de-noise genomic sequencing data, increasing the robustness of the company's imaging products. (In progress since November 2023).

#### Mapping transit accessibilty for the Nashville Metro Planning Authority 
-  For my undergraduate economics thesis, I consulted for the Nashville MPO to help them understand the impact of transit access on labor market participation in the Nashville region. I leveraged the Bing Maps API to create an index of transit accessibility in urban areas. I built a segmented regression to analyze this index's impact on labor force participation rates within disparate income groups. [Thesis](https://ir.vanderbilt.edu/handle/1803/10359). [Vanderbilt News Article](https://news.vanderbilt.edu/2017/04/28/class-of-2017-marc-chen/).
