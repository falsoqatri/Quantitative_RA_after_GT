<h1>Quantitative Risk Assessment program - University of Essex</h1>



<h2>1.	Quantitative risk modelling approach</h2>
This code reads the asset values and threat levels from two text files (asset_values.txt and threat_levels.txt) that contain comma-separated values for each asset and threat. It then defines two functions (calculate_ale and interpret_ale) that work as in the previous example. Finally, it uses the read asset values and threat levels to calculate the annualized loss expectancy for a given asset and threat, and interprets the result based on the same scoring system as before.
<br />


<h2>2.	Internal supply chain risks include risk events caused by (Shahram, et al., 2013)</h2>

- <b>Disruptions of internal operations</b> 
- <b>Price Increases: Rising prices are caused by changes in supply or demand, currency instability, and customs tariffs.</b>
- <b>Shortages: These can arise from lacking a component, material, or part needed to produce a finished product</b> 
- <b>Supplier Relationships</b> 
- <b>Quality Failures: Quality failures occur when shipments of certain parts don’t meet the specifications.</b> 
- <b>Delivery Failures: Carrier and logistical issues can result in late deliveries, damaged packages, or lost shipments.</b> 
- <b>Supply Shocks: Sudden worldwide or industry-wide drop in supply.</b> 

The calculation is done using the formula:  Expected Monetary Value (EMV) = Probability * Impact (Wagner & Shiraji , 2019)
<br />
 Where :
 <br />
 
Impact: the impact is the amount you will spend if a given identified risk occurs.
<br />
Probability: probability is the likelihood that any event will occur. 
<br />
The following table performs the calculation needed using data from similar supply chain risk.
<br />
| Id  | Risk | Probability | Impact ($) | EVM ($) |
| --- | --- | --- | --- | --- |
| 1	| Disruptions of internal operations	| 35%	| 5000	| 1750 |
| 2	| Price Increases	 | 25%	| 10000	| 2500 |
| 3	| Shortages	| 20%	| 3000	| 600 |
| 4	| Supplier Relationships	| 5%	| 2000	 | 100 |
| 5	| Quality failure	| 15%	| 5000	 | 750 |
| 6	| Delivery Failures	| 10%	| 4000	 | 400 |
| 7	| Supply Shocks	| 8%	| 3000	| 240 |

The quantitative risk analysis resulted in the the following list of risk as shown by the following graph
<br />

![EVM](https://github.com/falsoqatri/qualitative_risk_assessment_LAB/assets/134807849/16826796-4c48-4438-b56b-90cee52337df)

<h2>References </h2>

<br />
- Shahram, G., Hosein, G. & Mahdi , k. (2013). Difference between Internal and External Supply Chain Risks on its Performance.. Singaporean Journal of Business , Economics and Management Studies.
<br />
- Tuomas, M. (2022). Application of decision tree analysis and expected monetary value technique in quantitative risk management: Evaluation of less risky investment strategy. School of Technology and Innovations.
<br />
- Wagner, D. & Shiraji , K. (2019). Calculating project risk contingency Expected Monetary Value (EMV) vs Monte Carlo Analysis. Synergy.

