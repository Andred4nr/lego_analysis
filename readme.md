# Case Study - Lego prices

Note - You'll need to unzip the raw data to repeat the analysis

## Ask phase
Guiding questions<br/>
● What topic are you exploring?<br/>
● What is the problem you are trying to solve?<br/>
● What metrics will you use to measure your data to achieve your objective?<br/>
● Who are the stakeholders?<br/>
● Who is your audience?<br/>
● How can your insights help your client make decisions?<br/>
<br/>

Key points/questions
**1. Identify the business task**<br/>
The objective of this case study is to acess how lego set valuation changes actoss times.<br/>
**2. Determine key stakeholders**<br/>
The key stakeholder is the lego investor. <br/>
**3. Choose a dataset**<br/>
https://www.kaggle.com/datasets/alessiasimone/lego-sets-and-price-1955-2023/<br/>
**4. Questions/wonderings**<br/>
The metrics are:<br/>
Set prices - Are sets priced at consistent or gowing, maybe declining<br/>
Set review scores - Are sets reviewed consistently or there are factors influencing them <br/>
Set review counts - Are the sets gethering more or less reviews (proxy for interest) with time or something else?<br/>

## Prepare phase
Guiding questions<br/>
● Where is your data located?<br/>
● How is the data organized?<br/>
● Are there issues with bias or credibility in this data? Does your data ROCCC?<br/>
● How are you addressing licensing, privacy, security, and accessibility?<br/>
● How did you verify the data’s integrity?<br/>
● How does it help you answer your question?<br/>
● Are there any problems with the data?<br/>

**A description of all data sources used in:** https://www.kaggle.com/datasets/alessiasimone/lego-sets-and-price-1955-2023/

## Process
Guiding questions<br/>
● What tools are you choosing and why?<br/>
● Have you ensured your data’s integrity?<br/>
● What steps have you taken to ensure that your data is clean?<br/>
● How can you verify that your data is clean and ready to analyze?<br/>
● Have you documented your cleaning process so you can review and share those results?<br/>

**Documentation of any cleaning or manipulation of data:**<br/>
Can be found in the notebook prepare.ipynb

## Analyze /Share phase
Guiding questions<br/>
● How should you organize your data to perform analysis on it?<br/>
● Has your data been properly formatted?<br/>
● What surprises did you discover in the data?<br/>
● What trends or relationships did you find in the data?<br/>
● How will these insights help answer your business questions?<br/>

### Analysis Summary:
* After 2005 lego has started to make more medium/high value (> 200 Euros) sets<br/>
* The amount of medium and high value sets has grown over the years, especially since 2005 <br/>
* There is a positive correlation between the higher value sets and the engagement (review count) of buyers so the high value sets are good point for expansion<br/>
* Despite the growth in high and medium value sets, most of the sets have a low price (< 100 Euros)<br/>
* When there is a high review count (high engagement) we see a positive correlation between price and review score, meaning people get involved for low prices and bad quality or high prices and high quality. <br/>

**Share pahse in the notebook analyze.ipynb**

## Act
Guiding questions
* What is your final conclusion based on your analysis?
* How could your team and business apply your insights?
* What next steps would you or your stakeholders take based on your findings?
* Is there additional data you could use to expand on your findings

### Top high-level insights based on your analysis<br/>
- Medium and high value sets create more engagement with users so increasing the output of these is crutial<br/>
- On low value sets be careful to not cut cost at the expense of quality, people will go to the reviews if they feel they didn't get their money's worth<br/>
- The high quality on high quality sets creates brand promoters so investing time to create a great high value set will have marketing as well as financial returns<br/>


### Additional deliverables you think would be helpful to include for further exploration<br/>
- Amount of sales per set (acess contributionm of high, medium and low value sets to total)
- Age category for the sets (I suspect that the 18+ category has big impact on value of sets)
- Separate the sets that are licences vs not (is there a good incentive to licence IPs from other companies)
