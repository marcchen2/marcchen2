### Hello! I'm Marc Chen. 

- I'm currently a visiting ML researcher at the University of Waterloo, where I support the computational finance research of Profs. [Yuying Li](https://cs.uwaterloo.ca/~yuying/) and [Peter Forsyth](https://cs.uwaterloo.ca/~paforsyt/).
- I recently graduated from uWaterloo with a Master of Mathematics in Data Science, and completed my thesis, titled ["A Robust NN Approach to Optimal Decumulation and Factor Investing"](https://uwspace.uwaterloo.ca/handle/10012/19874).
- My co-authored ML finance research has been submitted for journal publication, and is available [as a pre-print](https://arxiv.org/abs/2306.10582). 
- On this personal Github, I share select projects from my research experiences and independent side projects.

### Highlighted Projects:

#### [Market Data Bootstrapper](https://github.com/marcchen2/market_data_bootstrap/)  


<p>
    <img src="block_bootstrap.png" width="300"  /><br> 
    <em > Diagram credit to
<a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0131111">El Anbari, Abeer, and Ptitsyn (2015)</a>
</em>
</p>

A common problem facing the ML finance research community is the availability of asset return data. The single realized historical path is insufficient for robust training of ML investment recommendation models. There are several approaches to generating additional time series data with similar statistical properties as real assets' return paths. One of the most widely accepted to be the gold standard by finance practioners is stationary block bootstrapping (Patton et al., 2009) of historical return data. This working repo implements the methodology in Python and Numpy (PyTorch version forthcoming). I developed this as part of a larger ML framework to create optimal portfolio management strategies, which uses this tool as one of two data sources for training and testing optimal investment strategies.
