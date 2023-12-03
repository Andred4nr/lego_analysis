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
1. Identify the business task<br/>
The objective of this case study is to acess how lego set valuation changes actoss times.<br/>
2. Determine key stakeholders<br/>
The key stakeholder is the lego investor. <br/>
3. Choose a dataset<br/>
https://www.kaggle.com/datasets/alessiasimone/lego-sets-and-price-1955-2023/<br/>
4. Establish metrics.<br/>
The 2 metrics are:<br/>
Set prices - Are sets priced at consistent or gowing prices<br/>
Set review scores - Are sets reviewed consistently or improving/degrading <br/>
Set review counts - Are the sets gethering more or less reviews (proxy for interest) with time<br/>

## Prepare phase
Guiding questions<br/>
● Where is your data located?<br/>
● How is the data organized?<br/>
● Are there issues with bias or credibility in this data? Does your data ROCCC?<br/>
● How are you addressing licensing, privacy, security, and accessibility?<br/>
● How did you verify the data’s integrity?<br/>
● How does it help you answer your question?<br/>
● Are there any problems with the data?<br/>

Key points<br/>
● Download data and store it appropriately.<br/>
● Identify how it’s organized.<br/>
● Sort and filter the data.<br/>
● Determine the credibility of the data.<br/>

Deliverable<br/>
A description of all data sources used in: https://www.kaggle.com/datasets/alessiasimone/lego-sets-and-price-1955-2023/

## Process
Guiding questions<br/>
● What tools are you choosing and why?<br/>
● Have you ensured your data’s integrity?<br/>
● What steps have you taken to ensure that your data is clean?<br/>
● How can you verify that your data is clean and ready to analyze?<br/>
● Have you documented your cleaning process so you can review and share those results?<br/>

Key tasks<br/>
● Check the data for errors.<br/>
● Choose your tools.<br/>
● Transform the data so you can work with it eectively.<br/>
● Document the cleaning process.<br/>
<br/>
Deliverable<br/>
Documentation of any cleaning or manipulation of data:<br/>
**Can be found in the notebook prepare.ipynb**

## Analyze /Share phase
Guiding questions<br/>
● How should you organize your data to perform analysis on it?<br/>
● Has your data been properly formatted?<br/>
● What surprises did you discover in the data?<br/>
● What trends or relationships did you find in the data?<br/>
● How will these insights help answer your business questions?<br/>

Key tasks<br/>
● Aggregate your data so it’s useful and accessible.<br/>
● Organize and format your data.<br/>
● Perform calculations.<br/>
● Document your calculations to keep track of your analysis steps.<br/>
● Identify trends and relationships.<br/>

Analysis Summary:<br/>
* After 2005 lego has started to make more medium/high value (> 200 Euros) sets<br/>
* The amount of medium and high value sets has grown over the years, especially since 2005 <br/>
* There is a positive correlation between the higher value sets and the engagement (review count) of buyers so the high value sets are good point for expansion<br/>
* Despite the growth in high and medium value sets, most of the sets have a low price (< 100 Euros)<br/>
* When there is a high review count (high engagement) we see a positive correlation between price and review score, meaning people get involved for low prices and bad quality or high prices and high quality. <br/>

**Share pahse in the notebook analyze.ipynb**

## Act
Now that you have finished creating your visualizations, act on your findings. Organize the deliverables you created, including your top high-level insights based on your analysis. Use the following Case Study Roadmap as a guide:

Guiding questions
* What is your final conclusion based on your analysis?
* How could your team and business apply your insights?
* What next steps would you or your stakeholders take based on your findings?
* Is there additional data you could use to expand on your findings

Key tasks
* Create your portfolio.
* Add your case study.
* Practice presenting your case study to a friend or family member.

Deliverables<br/>
**Your top high-level insights based on your analysis**<br/>
- Medium and high value sets create more engagement with users so increasing the output of these is crutial<br/>
- On low value sets be careful to not cut cost at the expense of quality, people will go to the reviews if they feel they didn't get their money's worth<br/>
- The high quality on high quality sets creates brand promoters so investing time to create a great high value set will have marketing as well as financial returns<br/>


**Based on what you discover, a list of additional deliverables you think would be helpful to include for further exploration**<br/>
- Amount of sales per set (acess contributionm of high, medium and low value sets to total)
- Age category for the sets (I suspect that the 18+ category has big impact on value of sets)
- Separate the sets that are licences vs not (is there a good incentive to licence IPs from other companies)
