# Calculating Rasmussen Hirschman Backward and Forward Linkage Indexes

<p align="center">
  <img width="100%" height="100%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/linkages.png"> 
</p> 
Cara Ewing/Minneapolis Fed

### Theoretical foundations

An industry's linkage effect may be seen as **forces that facilitate investments decision through input-output relations** [(Hirschman, 1977, p. 73)](https://www.degruyter.com/document/doi/10.1515/9781400848409-008/html). While backward linkages refer to these forces in **input-supplying** sectors, forward linkages refer to the investments that are facilitated in industries that **use that input**, which are located upstream to it. They can be also defined as measures of interrelationships between economy's sectors and each sector's capacity in defining ties (or linkages) with others sectors. 

Hirschman devised the linkages framework to challenge the worldview that in economies that are scarcely supplied by factors of production and entrepreneurship, the market is the best coordinating institution of the process of economic development. Hirschman believed that for economic development, "finding optimal combinations for given resources for given resources and factors of production” was of secondary importance [(Hirschman, 1992, pp. 56-7)](https://books.google.de/books?id=CTPh1DI71R0C&printsec=frontcover&dq=%22Rival+views+of+market+society+and+other+recent+essays%22&hl=pt-PT&sa=X&redir_esc=y#v=onepage&q=%22Rival%20views%20of%20market%20society%20and%20other%20recent%20essays%22&f=false). 

He proposed an unbalanced growth strategy in which investment decisions - chiefly those taken by governments regarding large infraastructural projects - are relevant not only because they have short-term effects, through multiypliying relations, but also because of their effect on future investment decisions, through the formed linkages. A project’s **unintended consequences** and broader economic and political complementarities also contribute to another sector's flourishing. Sometimes a project's unintended consequences may be fundamental for its sucess or it can have much larger developmental consequences than the project itself ([Hirschman, 1967, pp. 161-5](https://books.google.de/books?hl=pt-PT&lr=&id=oz8PBAAAQBAJ&oi=fnd&pg=PP1&dq=%22Development+projects+observed%22&ots=zFL9NYp3RB&sig=_P61dDN0noblS6k8HmPKKVjsSrc&redir_esc=y#v=onepage&q=%22Development%20projects%20observed%22&f=false); [Grabel, 2017, p. 37)](https://books.google.de/books?id=ZPpFDwAAQBAJ&printsec=frontcover&dq=ilene+grabel+when+things&hl=pt-PT&sa=X&redir_esc=y#v=onepage&q=ilene%20grabel%20when%20things&f=false). In this context, particularly in developing economies, taking into account a project's or prospective industry's possible backward and forward linkages are fundamental criteria for choosing among contending alternatives, which permits to rank “economic activities in accordance with their igniting potential” [(Hirschman, 1967, p. 177-8, 183)](https://books.google.de/books?hl=pt-PT&lr=&id=oz8PBAAAQBAJ&oi=fnd&pg=PP1&dq=%22Development+projects+observed%22&ots=zFL9NYp3RB&sig=_P61dDN0noblS6k8HmPKKVjsSrc&redir_esc=y#v=onepage&q=%22Development%20projects%20observed%22&f=false). 

### The model

Rasmussen Hirschman Linkages indexes are based on Wassily Leontief's pioneer input-output model [(Leontief, 1951)](https://books.google.de/books?id=HH6bAAAAIAAJ&q=The+structure+of+American+economy,+1919-1939+:+an+empirical+application+of+equilibrium+analysis.&dq=The+structure+of+American+economy,+1919-1939+:+an+empirical+application+of+equilibrium+analysis.&hl=pt-PT&sa=X&redir_esc=y). In his model, the economy's total production (X) is the sum of the total production that is devoted to  intermediate consumption of the economy's different sectors (Z) or (AY) and that of demand (Y). Here is how an input output table looks like:

<p align="center">
  <img width="97%" height="97%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/inputoutput.png"> 
</p> 

As can be seen in the equation below, A is the technical coefficients matrix any Y the vector that represents final demand. 

<p align="center">
  <img width="17%" height="17%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/equation2.png"> 
</p> 

X also can be calculated as follows, where I is an identity matrix and (I - A)-1 Leontief's inverse matrix:

<p align="center">
  <img width="15%" height="15%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/matrixinv.png"> 
</p> 

After [Rasmussen's (1956)](https://books.google.de/books?id=RGfNQwAACAAJ&dq=%22Studies+in+intersectoral+relations.%22&hl=pt-PT&sa=X&redir_esc=y) and [Hirschman's (1958)](https://books.google.de/books?id=foREAAAAYAAJ&q=%22The+Strategy+of+Economic+Development%22+hirschman&dq=%22The+Strategy+of+Economic+Development%22+hirschman&hl=pt-PT&sa=X&ved=2ahUKEwi0zNP6uuTwAhUYtqQKHTHBDewQ6AEwBHoECAUQAg) seminal works, what has been defined as Rasmussen-Hirschman backward linkage (BL) index is a measure of how much  sector j demands  from  all sectors. By their turn, forward  linkages  (FL) are measures how sector j's production is demanded  by  the others. To  estimate the Hirschman-Rasmussen indexes, it is necessary to calculate the matrix of technical coeffcients A, and then take its average. The indexes are calculated in relation to their total average, as can be seen in equation below:

<p align="center">
  <img width="20%" height="20%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/elements.png"> 
</p> 

where Uj is the sector's backward linkage index, Xj the sum of a given line, n the number of sectors, X* the total sum of coefficient, Un the sector's forward linkage index, and Xi the sum of a given column. If the index is higher than one, its contribution to the economy is above average. 

After [Cuello et al's (1992)](https://www.tandfonline.com/doi/abs/10.1080/09535319200000027) contribution, it is also possible to use weighted backward and forward linkage indexes. This is particularly recommendable when a large share of the sector's demand is in the form of exports, which may have the effect of underestimating the sector's importance for the economy. The weight is calculated by adding up the entire economy's final output and by dividing a sector's final output by that total. With the weights w, here is how the the backward and forward linkages are now calculated:

<p align="center">
  <img width="20%" height="20%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/withweights.png"> 
</p> 

### Using Python to calculate the indexes

Most of the code to calculate Rasmussen-Hirschman indexes with Python in its most basic version (without weights) can be found **[here](https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/notebooks/Getting%20data.ipynb)**. Because I tackled this project in the very beginning in my trajectory of transitioning from Excel to Python, there are some preprocessing steps that I did in Excel, such as calculating the technical coefficients matrix. I also compiled the results on Excel, which I then reimported to a new Juypter Notebook in which I did the analysis of the results. 

 **[Jupyter Notebook](https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/notebooks/Getting%20data.ipynb)**
 
 **[Here](https://peter-puszko.medium.com/solving-leontiefs-input-output-model-in-python-a0a29455b2d8)** is an useful resource to understand how to solve Leontief’s Input-Output model using Python.

### Extracting visualizations of interest 
