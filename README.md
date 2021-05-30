# Calculating Rasmussen Hirschman Backward and Forward Linkage Indexes

<p align="center">
  <img width="100%" height="100%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/linkages.png"> 
</p> 
Cara Ewing/Minneapolis Fed

### Project outline, objectives and key takeaways

Still in progress ..

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

### Generating visualizations of interest 

#### Looking at the entire data set
It is now time to visually explore if there are interesting correlations between the calculated backward and forward linkage indexes and other variables of interest, such as GDP per capita. The project's main question is whether manufacturing matters for economic development. To assess this, I try to find if there is a correlation between high backward and forward linkages and and elevated GDP per capita. I look at the scores for selected sectors from the commodities, manufacturing and services sector. 

Through the visualizations below, I try to spot multiple equilibria, which in the visualisations can be understood as the presence of two or more darker dots, in which more unique points (combinations of the calculated index and the gdp per capita level for a year) are clustered. The visual inspection of the graphs suggests that there is not much evidence, with the exception of some sectors, that there is generalized correlation between higher gdp per capita and higher scores in the manucaturing sector. Before proceding to the interpretation for why this is so, let's take a look at some graphs. 

The following graph, which relates the backward linkage indexes of the C28 sector ("Manufacture of machinery and equipment n.e.c." in the ISIC classification) with the countries' GDP per capita, for the 2000-2014 period, confirms my working hypothesis. The graph tells us that there are two equilibria. One, in which countries have a low gdp per capita and a low weighted backward linkage, and another in which the gdp per capita is high and the weighted backward linkage is slightly higher. Its reading suggests that manufacturing does matter for economic growth and development! 

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/Herunterladen.png"> 
</p> 

The same holds for "C27", which refers to "Manufacture of computer, electronic and optical products". Observe how a majority of countries/points are clustered at a relatively low level of GDP per capita and weighted backward linkage, but that there is also a higher equilibrium, albeit a much smaller one.

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/Herunterladen_(7).png"> 
</p> 

The following graph, which plots the results from "B" ("Mining and quarrying") permits an analogous interpretation. Countries with a higher GDP per capita tend to have a lower weighted backward linkage in an activity whose value-added is considerably lower, at it is not a manufacturing sector.  

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/Herunterladen_(4).png"> 
</p> 

Now let's take a look of some of the results found for Weighted Forward Linkages. Recall that a Forward Linkage index tell us how much of a given sector's production is demanded by others as an input. What this graph is telling us (it refers to "Manufacture of chemicals and chemical products") is that countries with a high GDP per capita demand a lot of chemicals and chemicals products to unfold their productive processes. 

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/HerunterladenF3.png"> 
</p> 

What about IT and computer programming? This here refers to the Weighted Forward Backward Linkage of "Computer programming, consultancy and related activities; information service activities". The graph tells us that there is indeed an equilibrium (albeit a small one) in which developed countries (in terms of GDP per capita) have a high demand for goods and services from that sector. Think about a country like Germany, where the demand for IT services is blooming! 

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/HerunterladenF10.png"> 
</p> 

Unfortunately (at least from the point of view of the confirmation of my hypothesis), many graphs look like this. Both countries with high and low GDP per capita tend to have a similar level of Weighted Backward Linkage Index for "Manufacture of computer, electronic and optical products". In other words, in both types of countries this sector demands a comparable amount of inputs from other sectors.

<p align="center">
  <img width="50%" height="50%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/Herunterladen_(5).png"> 
</p> 

While analysing the results of the calculation of Backward and Forward Linkages by plotting them with GDP per capita has proven insightful, there are some limitations. The largest one is that the calculation of indexes does not account for the relative size of the sectors in the economy. Because the linkage indexes are calculated in relation to the average, the relative importance is underestimated. The introduction of weights is a promising attempt to correct this problem, but it also has its limitations. 

#### Looking only at the case of Brazil

Now I turn to the case of Brazil, which I have been studying for a long time, particulary is the object of my doctoral thesis. In the following graphs the average Backward and Forward linkages (and ranges) of three different macrosectors (commodities, manufacturing and services) are computed, using Seaborn's lineplot. This tool comes as handy because it permits to unite, in a single graph, the lines for the 56 sectors of the economy, while maintaining its informative content. If each single line where plotted, it wouldn't be a readable visualization. While the first sets of graphs does the exercise for simple backward linkages, the second focuses on forward linkages. 

The main takeway of the first graph is that the demand for goods and services parting from the commodities sector , which includes, among others agricultue and mining, oscillates more strongly than the one from the two other sectors. This suggests that there might be a stronger cyclical component in the former's business cycle than in the former's. It is known that Brazil's economy is passing through a strong deindusitrialization process, in which commodities are growingly having a larger economic role. What this finding suggests, then, is that the deindustrialization process also subjects the economy to more stronger upswings in demand for goods and services, producing more uncertainties in the entire goods and services supplier chains.  

<p align="center"> Backward linkages vs time </p> 
<p align="center">
  <img width="75%" height="75%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/4x4_3.png"> 
</p> 

For forward linkages the reading is analogous. Brazil mostly exports the commodities it produces. Therefore their impact on other sectors of the economy as an input (in terms of employment and productive growth) is not very large as those from manufactured goods and from services, which are chiefly consumed domestically. The fact that there have been much stronger oscillation in commodities' forward linkages suggests that this effect is magnified. While the country does export a large percentage of the commodities it produces, it also consumes it domestically. However, commodities are generally priced abroad. Above all in the 2000-2010 period, there has been a global "commodities supercycle", in which demand for those goods, and, consequently, prices, grew impressively, also in the domestic market. While strong forward linkages generally express a virtuous relationship between a sector and the others that demand its goods, the strong oscillations, which may habe been explained by strong price oscillations, may have been turned into a disturbing factor. This suggests that commodities may not be a reliable driver of growth.

<p align="center"> Forward linkages vs time </p>
<p align="center">
  <img width="75%" height="75%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/4x4_5.png"> 
</p> 


