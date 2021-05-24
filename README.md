# Rasmussen_Hirschman_Linkages

### Theoretical foundations

According to Hirschman (1977, p. 73) an industry's linkage effect may be seen as forces that facilitate investments decision through input-output relations. While backward linkages refer to these forces in input-supplying sectors, forward linkages refer to the investments that facilitated in industries that use that input, which are located upstream to it. Hirschman devised the linkages framework to challenge the worldview that also in economies that are scarcely supplied by factors of production and entrepreneurship, the market is the best coordinating institution of the process of economic development, for it does the best job in allocating the economy’s resources. 
Hirschman believed that for economic development, "finding optimal combinations for given resources for given resources and factors of production” and “enlisting for development purposes resources and abilities that are hidden, scattered, or badly utilized” was of secondary importance (Hirschman, 1992, pp. 56-7). 

He proposed an unbalanced growth strategy in which investment decisions - chiefly those taken by governments regarding large infraastructural projects - are relevant not only because they have short-term effects, through multiypliying relations, but also because of their effect on future investment decisions because that owed to these construcetd linkages (ibid). In this context, A project’s unintended consequences and broader economic and political complementarities also contribute to another sector's flourishing. Sometimes a project's unintended consequences may be fundamental for its sucess or it can have much larger developmental consequences than the project itself (Hirschman, 1967, pp. 161-5; Grabel, 2017, p. 37). In this context, particularly in developing economies, taking into account a project's or prospective industry's possible backward and forward linkages are fundamental criteria for choosing among contending alternatives, which permits to rank “economic activities in accordance with their igniting potential” (Hirschman, 1967, p. 177-8, 183). 

### The model

Rasmussen Hirschman Linkages indexes are based on Leontief's pioneer input-output model (1951). In his model, the economy's total production (X) is the product of sum of the production that is devoted to  intermediate consumption of the economy's different sectors (Z)  and of demand (Y),  which computes how much sector  j  used the goods that are  produced  by  sector  i  total production. As can be seen in the equation below, A is the technical coefficients matrix any Y the vector that represents final demand. 

<p align="center">
  <img width="15%" height="15%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/equation2.png"> 
</p> 

X also can be calculated as follows, where I is the identity matrix and the second term Leontief's inverse matrix:

<p align="center">
  <img width="15%" height="15%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/matrixinv.png"> 
</p> 


After Rasmussen's (1958) and Hirschman's (1958) seminal works, linkages can be also defined as measures of interrelationships between economy's sectors and each sector's capacity in defining ties (or linkages) with others sectors. What has been defined as Hirschman-Rasmussen backward linkage (BL) index is a measure of how much  sector j demands  from  all sectors. By their turn, forward  linkages  (FL) are measures how sector j's production is demanded  by  the others. To  estimate the Hirschman-Rasmussen indexes, it is necessary to one calculate the matrix of technical coeffcients A, then take its average.  The indexes, then, are calculated in relation to their total average, as can be seen in equation below:

<p align="center">
  <img width="20%" height="20%" src="https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/images/elements.png"> 
</p> 

where Uj is the sector's backward linkage index, Xj the sum of a given line, n the number of sectors, X* the total sum of coefficient, Un the sector's forward linkage index, and Xi the sum of a given column. If the index is higher than one, its contribution to the economy is above average. After Cuello et al ( ), it is also possible to 



- [Jupyter Notebook with code for the calculation of Rasmussen-Hirschman indexes.](https://github.com/ebelingbarros/Rasmussen_Hirschman_Linkages/blob/main/notebooks/Getting%20data.ipynb)
