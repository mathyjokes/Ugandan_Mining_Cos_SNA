# Social network analysis of companies with Ugandan Mining Concessions

Uganda borders several countries known for using conflict minerals to finance violence and terrorism. 
Because of this, a recent boom in Uganda mining has been accompanied by allegations of corruption, collusion, and smuggling. 
Recent news reports have focused on highlighting on specific companies and their ties to either Ugandan officials or regional unrest. 
As a network of organizations with varying degrees of connection to the governing bodies of Uganda, however, the Ugandan mining sector has not been well examined. 

Drawing from reports released by the Ugandan Ministry of Energy and Mineral Development, 
it is possible to build a network of mining organizations through shared features such as the identification number of the 
licensed concession, the address, or even the type of material to be extracted. 

Past research on organizational structures has focused either on the intra-organizational networks of co-workers or the inter-organization flows of money or information. 
Network analysis methods traditionally applied to understanding business structures or financial flows can be applied to the Ugandan mining sector to understand the network, 
especially in relation to the companies that have been identified in news reports as related to corruption. 
From this, it may be possible to draw conclusions on how frequently companies may come into contact in general, 
which companies have the closest relationship to those known to be engaged in unethical practices, 
and how these corruption-influenced organizations affect the network structure overall.

### Data Collection

Data regarding the mining companies in Uganda was gathered from the annual Statistical Abstracts 
that the Uganda Ministry of Energy and Development releases available online from 2011- 2015. 
Information on whether these companies have been accused of corruption was gathered from the companies named in the Global Witness report “Undermined,” 
released in July 2017. After cleaning and initial analysis, this resulted in a set of 372 companies, with 46 of these considered “corrupt.”

### Data Limitations 

The data was limited in two main respects. 
The Uganda Ministry of Energy and Mineral Development had different reporting requirements over the years, resulting in companies with few or no attributes. 
No missing links were inferred, meaning that the lack of a tie could mean that there is no tie or there is no data. 
Additionally, and as a result of the inherently illicit nature of corruption, 
it is likely that the companies in the Global Witness report do not encompass the entirety of corrupt companies operating in Uganda. 
Here, too, lack of accurate data, especially in such a sparsely connected network, could skew results.


### Results

The Figure below shows a Company x Multiple Attributes network. 
Companies are represented as green squares, and their attributes, “concession number,” “address,” “contact name,” “mineral,” and “district” are represented in the other colors. 
Centrality analysis identified several attributes of corrupt companies that play important roles in the network.
Expecting the network to be relatively sparse, these high degree attributes were anomalies and warranted further investigation. 
Of the “Contact Name” attributes, 3 of the top 7 were associated with corrupt companies. 
A Louvain community detection algorithm also identified subgroups of highly connected corrupt companies. 
In one group with 11 members, 6 were corrupt.

![company_atts](https://github.com/mathyjokes/Ugandan_Mining_Cos_SNA/blob/master/company%20x%20multiple%20attributes%20network.png)
