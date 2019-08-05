# Modeling Macroeconomic Dynamics with Deep Learning

Notre Dame CSE 60625 Machine Learning (Spring 2019)  

Yuanhao Niu (PhD Student: Economics)  
Cale Harnish (PhD Student: Aerospace and Mechanical Engineering)  

We leverage Artificial Neural Networks (ANN) to approximate partial differential equations (PDEs), which represent macroeconomic dynamics. A temporal difference(TD) learning approach is adopted. We first solve a baseline Neoclassical Growth (NCG) model in one dimension. We compare our solutions from deep learning with existing results from the literature for numerical accuracy. Then, we extend the baseline NCG model with an additional input (productivity shock) and a diffusion process. This algorithm complements traditional numerical techniques (\emph{e.g.} finite difference method) and can be easily scaled to higher dimensions.


### Jupyter Notebook 
Neoclassical Growth Model [w/ Capital](https://github.com/yniu87/ML_Macro/blob/master/NCG_1D.ipynb).  
Neoclassical Growth Model [w/ Capital and TFP shcoks](https://github.com/yniu87/ML_Macro/blob/master/NCG_2D.ipynb).

### Summary Report
[Paper](https://github.com/yniu87/ML_Macro/blob/master/project_paper.pdf).

## References 
[1] Jiequn Han, Arnulf Jentzen, and E Weinan. 2018. Solving high-dimensional partial differential equations using deep learning.Proceedings of the National Academy of Sciences 115, 34 (2018), 8505–8510.  
[2] Yves Achdou, Jiequn Han, Jean-Michel Lasry, Pierre-Louis Lions, and Benjamin Moll. 2017. Income and Wealth Distribution in Macroeconomics: A Continuous-Time Approach. NBER Working Paper 23732.  
[3] Duarte, Victor, Machine Learning for Continuous-Time Economics (April 26, 2018).  
