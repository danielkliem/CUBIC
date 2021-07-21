## CUBIC - A Sytem Dynamics Model of swiss construction material industries transition towards a circular economy 

The transition towards a circular economy in Switzerland is driven by land-use conflicts between urban development, rural landscape and demand for primary materials. While mineral materials account for almost 50 % of the national metabolism only around 30% of the recycling potential is realized. Recycling of different materials increased in recent years in some regions but remains at low levels in other regions. This results in the paradox situation of companies trying to increase the secondary resource utilization, but at the same time companies increase gravel extraction to create volume for disposal. This model teaches the drivers and barriers of such transitions towards circular consumption and production systems, from the perspective of companies and regional policy makers. However, the chosen dynamic problem also excludes the following processes that are only marginally relevant for the question. 
The goal of the model is (A) to explain the limits to the common misperceptions about drivers to the transitions, (B) enable policy experiments, and (C) explicate institutional decision-making structures. 
(A) Common misperceptions that were identified during the participative modelling workshops and respective learning outcomes:
1.	“If we just recycle all the Waste, we won’t need primary resources” is a common misperception, as without the extraction of primary resources there is not sufficient volume for the disposal of waste available.
2.	If we limit the available gravel quarries in our region, companies will recycle more. While it might be true on the individual level of selected companies, an increase of gravel imports/waste exports will occur. 
3.	Increasing the costs to access resources increases recycling. If introduced locally, financial instruments increases im/-exports. 
(B) The policy experiments are based on the sustainability goals, as defined throughout the participative modeling workshops. 

The goal was not necessarily agreement on the target variables - as an inclusion criterion, it was sufficient that one person involved in the process considered the named target variable to be significant: 
-	Imports of gravel should not be favored over local resources.
-	Local value creation is to be strengthened.
-	Transport routes are to be minimized.
-	Primary gravel resources are to be conserved.

Three questions appeared as relevant and can be consistently answered though simulation experiments. 
1.	How does urban construction activity influence the resource management in rural areas?
2.	What drives the recycling of excavation material?
3.	What limits the uptake of recycled aggregates?

## Get started
- Open Stellar / Install free [Stellar Playeer](https://www.iseesystems.com/softwares/player/iseeplayer.aspx)

- Open the .stmx file.					 # Opens model 

- Set “Initiate urban transition” to 1. 			# Sets historic and current material flows

- Set “Initiate incumbent policies” to 1. 			#  Initiates current set of policies 

--> The model is initialized to recreate historic patterns of behavior. It allows now for policy analysis and testing the original structure of the participative modeling workshops number 3.

How do I initialize the first iteration of the gravel extraction structure (paper 2)? 
Enter the “Extraction” module and set “Switch GMB structure” to 1. You can now observe the changes in behavior between the initial structure and the iterated (final) structure.

How do I recreate the results of the model analysis (paper 3)?
Set the respective values for the fiscal, administrative and soft policies (as described in paper 3). 

Can I test other construction activity regimes? 
Yes, set “Initiate urban transition” to 0. Go to “Customize Material Flows Region A/B” and selected % change of (Gravel, CDW, Excavation material) in both regions.

## Model background

The model covers the time horizon from 2010 to 2085, as 75 years is considered a sufficient time frame to capture the unfolding long term dynamics of the ponderous construction material industry (Suprun et al. 2019), i.e. 75 years is twice the longest adjustment time of the model. The model is developed from a co-evolutionary- socio-technical transitions perspective (Foxon 2011), a rather novel application for quantitative system dynamics modelling (Holtz et al. 2015). Conceptually, it regionalizes the approach of the World 6 model, combining biophysical material flows with market dynamics (Sverdrup, Koca, and Schlyter 2017). This regional perspective on socio-technical transitions uses social dynamics as well as innovation dynamics to understand the trajectory of the industry (Coenen, Benneworth, and Truffer 2012). The biophysical structure is focused on mineral construction material, especially aggregates, excavation material and construction and demolition waste (CDW). The production of aggregates includes extracting primary gravel from gravel quarries, recovering primary gravel that is naturally contained by excavation material and recycling secondary gravel from CDW. 
Existing data from regional material-flow-analysis was complemented with empirical data from a series of group model building workshops and a case study with 8 companies, looking at the consequences of land-use for extraction and disposal on interregional development. Driven by the settlement development in two Regions, the model looks the primary and secondary aggregate market, primary resource extraction and landfill management. 
Region A represents an urban area with little undeveloped area remaining, high population growth and dynamic construction activity. Land scarcity leads to settlement pressure and induces the Phenomena of “Not-in-my-back yard”, which leads to challenges when it comes to licensing new gravel quarries and increases the costs for obtaining such licenses. Region B is a hinterland region (Schiller, Bimesmeier, and Pham 2020) without population growth, constant construction activity and consequently no settlement pressure. 
In this model, sustainable usage of natural resources is key to reduce the demand for land, i.e. extraction of primary resources and disposal of mineral waste. Public policies, ranging from spatial planning, waste management, public procurement and fiscal policies are used to increase the rate of recycling and reduce transports. Material flows and associated transports between the regions are used to understand the consequences of population development and construction activity on the development on Region A and region B. Improving sustainability indicator for both regions can be achieved by introducing various public policies. This simulation helps to understand the effect of policies, showing intended effects and unintended consequences. 


## FAQ
Does the model predict future developments?
No. The goal is to increase general understanding of the dynamics, rather than providing exact predictions.

Can the model be adjusted to different regions?
Yes, most parameters can be adjusted to tailor dynamics ins specific regions. Most relevant adjustment may include the values of stocks in the gravel licensing process, the times to allow landscape adjustments, available disposal volumes. Furthermore, estimations for the current level of experience with recycled aggregates can be made. 

Why is there no third region?
To highlight the relevant interactions between regional developments, it is more effective to assume a closed system. Technically the involvement of a third regions is possible by including a third price to determine the transports between regions. While this adds complexity to the model, the additional insights are insignificant. One may assume that a high increase in the prices in one region will eventually trigger the resource exchange with a third region at increased transport costs. 

Is the model representative of all regional developments?
1)	The model is built on the assumption that the extraction that gravel extraction creates disposal volume. If a region does not follow this policy or has no gravel reserves, this structure is not valid. 
2)	The effect of settlement pressure on regional license costs is a phenomenon that is being observed in an increasing number of regions (under various names). 

Why is the gravel price (Stock/ Hill-climbing) modelled different from the disposal price (Auxiliary variable)?
The management of disposal volume is subject to tight regulations, regarding the location, quality of material and associated costs for the disposal process (from disposal to re-naturalization). Without these regulations, “wild” disposal sites are likely to result (as observed in 1960/70s). As an auxiliary variable, the disposal price is less sensitive to market dynamics. This decision is further supported by the existence of landscape adjustments, as a non-market mechanism to create further volumes and thereby influencing the disposal price. Thereby, the disposal price reflects a regional scarcity that is governed by local authorities. On the other hand, the gravel price is market driven because gravel needs to be extracted be physically available. There are no direct influences on the gravel price from the governing authorities.  

The model shows initially the actual material flows for a region, why does the simulation not show the same material flows in the policy analysis? What is real world and what is conceptual in the model? 
The point of the initial representation of the material flows is to highlight the ratio between the different material flows. Within the analysis, its is more user friendly to assess the behaviour with “all else being equal”. Because the actual data has some fluctuations, the model exerts dynamic behaviour that can not be clearly attributed to a specific cause by the average user. 

Why is the indicator for the gravel price not normalized via supply and demand (as in Sterman ,2000)?
Based on the insights from the GMB workshops, it is clear the local aggregate demand is always satisfied (unless there is not enough gravel available in both regions). Hence, the «shipping rate» of the local market is not an adequate representation of a local shortage. Therefore, the formulation via a Gap is more useful in this instance. 
Why are CDW and excavation material disposed in the same volume?
In reality, different disposal volumes for excavation material and CDW are required. This model only uses one volume for two reasons. 1)Disposal volume for CDW is even more regulated than the volume for excavation material, because CDW potentially contains more non-natural (and hazardous) waste than excavation material. In addition to the regulations, CDW landfills are kept to a minimum to incentivize recycling. This explains why the recycled aggregate production in this model is solely concerned with the relative attractiveness of prices instead of local landfill shortages. 2) Due to the significantly higher volumes excavation material, the gains from the recovery of aggregates are very high in terms of volume demand for disposal. Therefore, the focus of this model is to highlight the interaction between the extraction of gravel and management of disposal volumes. 

Why is the Policy “Increasing the energy costs for transport” so ineffective?
At mentioned in the description, the energy costs are only a fraction (1/16) of the total transport costs per ton of material. The effect is visible (reduces the average transport distance) if the energy costs are increased > tenfold. In addition, this cost increased is passed on to the consumer (raises the prices) and thereby only have a marginal effect on the profitability of ex/-imports. 

Why does the introduction of a disposal fee and extraction levy not lead to a recycling quota of 100%?
First, companies invest in the acquisition of gravel quarries. If the coverage of the available reserves increases, eventually companies will need to extract for 2 reasons. First, even if all material recycled, 70 % of the excavation material still needs to be disposed. Secondly, because companies can pass the costs on to the consumer, their profitability is only marginally affected.  

Why can the prices decrease to 0, even if there are costs associated (e.g. gravel price can be 0 CHF/t even though the policy “extraction levy” is > 0 CHF/t)? 
Following the previous questions, we know that companies pass costs on to the consumer. This question highlights the connection between gravel extraction and the creation of disposal volume. If either price approaches 0 CHF/t, the other price will even increase more because companies are able to adjust the regionally available gravel and indirectly influence the available disposal volume. 

Why do companies not receive revenue from landscape adjustments?
Landscape adjustments can foreclose disposal volume (if coverage > desired coverage) or create additional disposal coverage (if coverage < desired coverage). The creation of additional volume is not necessarily tied to existing gravel quarries, and thereby does not automatically contribute to the revenue of companies. For example, this additional landscape adjustment can be on agricultural space, or noise barriers next to highways.

# References

Coenen, Lars, Paul Benneworth, and Bernhard Truffer. 2012. “Toward a Spatial Perspective on Sustainability Transitions.” Research Policy 41 (6): 968–79. https://doi.org/10.1016/j.respol.2012.02.014.

Foxon, Timothy J. 2011. “A Coevolutionary Framework for Analysing a Transition to a Sustainable Low Carbon Economy.” Ecological Economics 70 (12): 2258–67. https://doi.org/10.1016/j.ecolecon.2011.07.014.

Holtz, Georg, Floortje Alkemade, Fjalar De Haan, Jonathan Köhler, Evelina Trutnevyte, Tobias Luthe, Johannes Halbe, et al. 2015. “Prospects of Modelling Societal Transitions: Position Paper of an Emerging Community.” Environmental Innovation and Societal Transitions 17: 41–58. https://doi.org/10.1016/j.eist.2015.05.006.

Kytzia, Susanne. 2000. “Modelling the Transformation of the Residential Building Stock – a Case Study for the City of St . Gall Short Summary.”

Meglin, R., D. Kliem, A. Scheidegger, and S. Kytzia. 2019. “Business-Models of Gravel, Cement and Concrete Producers in Switzerland and Their Relevance for Resource Management and Economic Development on Regional a Scale.” IOP Conference Series: Earth and Environmental Science 323 (1). https://doi.org/10.1088/1755-1315/323/1/012170.

Rubli, Stefan, and Martin Schneider. 2018. “KAR-Modell - Modellierung Der Kies-, Rückbau- Und Aushubmaterialflüsse : Modellerweiterung Und Nachführung 2016.” Zurich. http://www.kar-modell.ch/uploads/KAR-Modell_Ueberregional_2016.pdf.

Schiller, Georg, Tamara Bimesmeier, and Anh T.V. Pham. 2020. “Method for Quantifying Supply and Demand of Construction Minerals in Urban Regions-A Case Study of Hanoi and Its Hinterland.” Sustainability (Switzerland) 12 (11). https://doi.org/10.3390/su12114358.

Schwaninger, Markus, and Stefan Groesser. 2018. “System Dynamics Modeling: Validation for Quality Assurance.” Encyclopedia of Complexity and Systems Science, 1–20. https://doi.org/10.1007/978-3-642-27737-5_540-4.

Sterman, John D. 2000. Systems Thinking and Modeling for a Complex World. Management. Vol. 6. https://doi.org/10.1108/13673270210417646.

Suprun, Emiliya, Oz Sahin, Rodney Anthony Stewart, and Kriengsak Panuwatwanich. 2019. “Examining Transition Pathways to Construction Innovation in Russia: A System Dynamics Approach.” International Journal of Construction Management 0 (0): 1–23. https://doi.org/10.1080/15623599.2019.1637628.

Sverdrup, Harald U., Deniz Koca, and Peter Schlyter. 2017. “A Simple System Dynamics Model for the Global Production Rate of Sand, Gravel, Crushed Rock and Stone, Market Prices and Long-Term Supply Embedded into the WORLD6 Model.” BioPhysical Economics and Resource Quality 2 (2): 8. https://doi.org/10.1007/s41247-017-0023-2.
 

