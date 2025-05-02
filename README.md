# mist4610project2
## group 8
## crn61608 


# Team Members:
1. Peng, Kimberly @[KimmyPenguin](https://github.com/KimmyPenguin)
2. Sivakumar, Srujana @[sruj-siva](https://github.com/sruj-siva)
4. Asgari, Neema @[Neemajoon](https://github.com/Neemajoon)
5. Modi, Maleeka @[m-modi](https://github.com/m-modi)
6. Palacherla, Asha @[ashapalacherla](https://github.com/ashapalacherla)

# Describing your dataset and what data it contains:
This dataset comes from CA Safe Cosmetics Program in the California Department of Public Health (CDPH) and focuses on collecting information on chemicals suspected to cause cancer, birth defects, or other developmental or reproductive harm. The rows display a certain product with a matching chemical found in the product. Allows users to see which companies are using which ingredients and differences. Allows us to see specific trends within the industry as the data uses specific details : Usage, names, CAS numbers, and specific dates!

![Image 4-27-25 at 4 55 PM](https://github.com/sruj-siva/mist4610project2/blob/main/Screenshot%202025-04-27%20165506.png)

# Question 1 and why it’s so interesting:
## What are the top 10 cosmetic companies by chemical count:
Understanding the number and type of chemicals in cosmetic products is crucial for several reasons:
1. Safety: A higher number of ingredients can increase the risk of allergic reactions or sensitivities.​
2. Regulatory Compliance: Companies must ensure all ingredients are approved and safe for use in cosmetics.​
3. Consumer Choice: Knowledge of ingredient lists empowers consumers to make informed decisions, especially those with specific concerns like allergies or preferences for natural products.​
4. Sustainability: Companies are increasingly focusing on reducing the number of harmful chemicals and opting for sustainable, eco-friendly ingredients.

## The manipulations applied to the dataset as part of the analysis
To address our research question, we placed the average chemical count in the columns and the company name in the rows. Here we filtered our results by chemical name, applying our focus to the ten companies with the highest average amount of chemicals in their cosmetics.  

## Analysis and Results:

![image](https://github.com/user-attachments/assets/f3053139-95d2-4827-9f0d-696c57ae2f79)

### Who’s at the top?
Leading the list with the highest average of approximately 4.8 harmful chemicals per product is Regis Corporation, based on a total of 807 identified harmful chemicals across their 168 products. Closely following in second place is Cosmopharm, averaging around 4.5 harmful chemicals per product, derived from 58 harmful chemicals found in their 12 products. Ranking third is Vitamin World, Inc., with an average of 3.3 harmful chemicals per product, stemming from 109 harmful chemicals across 33 products. Chrome Hearts LLC takes the fourth spot, averaging 3.2 harmful chemicals per product, with 71 harmful chemicals identified in their 22 products. Good ‘N Natural ranks fifth, averaging exactly 3 harmful chemicals per product, based on 45 harmful chemicals in their 15 products. Coming in sixth is Puritan’s Pride, averaging 2.9 harmful chemicals per product, with 160 harmful chemicals spanning 54 products. Dermaquest, Inc. holds the seventh position, averaging 2.6 harmful chemicals per product from 39 harmful chemicals in their 15 products. Palladio Beauty Group ranks eighth with an average of 2.58 harmful chemicals per product, originating from a substantial 4,022 harmful chemicals across 1,557 products, followed very closely by Exclusive Fragrances & Cosmetics, at ninth, averaging 2.51 harmful chemicals per product from 161 harmful chemicals in their 64 products. Finally, Charlotte Tilbury Beauty Ltd appears at tenth, averaging 2.4 harmful chemicals per product, with a notable 6,716 harmful chemicals identified across their 2,770 products.

### Negative viewpoint: 
This dataset highlights companies with a notable average of chemicals in their cosmetic products which are suspected to cause cancer, birth defects, or other developmental or reproductive harm. A higher average number of such chemicals per product could potentially increase the likelihood of exposure to these adverse effects. Given the frequent use of many cosmetic products, and the potential for cumulative exposure when using multiple products at the same time,California , particularly those with pre-existing health conditions, may want to exercise caution when selecting products from companies with higher average chemical counts.

### Positive viewpoint:
The transparency of the companies included in this dataset, in reporting their chemical information, is a noteworthy positive aspect. Even though the data may underestimate the total prevalence of potentially harmful chemicals in the broader market due to incomplete reporting from all companies, the willingness of these top 10 to disclose this information offers consumers a degree of knowledge and allows for more informed purchasing decisions. This reporting could also indicate a potential commitment from these companies to future reformulation efforts or even product discontinuation if safety concerns warrant such actions.

### Important considerations: 
This data specifically reflects cosmetic products sold in California, and the ranking of companies by average chemical count might differ in other regions of the United States. While the information provides valuable insights for Californian consumers, individuals nationwide should remain mindful of cosmetic ingredient safety. Furthermore, the reported averages are calculated across all products of a company. Individual products may contain significantly more or fewer chemicals than the company average. Therefore, consumers are encouraged to conduct their own research on the specific ingredients of the products they use to make informed choices based on their individual needs and concerns.

# Question 2 and why it’s so interesting:
## What are the top 5 chemicals removed from cosmetic products?
The removal of these chemicals from cosmetic products is crucial for several reasons:​
1. Health Protection: Reducing exposure to harmful substances lowers the risk of chronic health issues, including cancer and hormone-related disorders.​
2. Consumer Demand: There is a growing preference for clean, natural, and non-toxic beauty products.​
3. Regulatory Compliance: Adhering to stricter regulations in regions like the EU can open up international markets and enhance brand reputation.​
As consumers become more informed, the demand for safer cosmetic products continues to rise, prompting the industry to phase out these harmful chemicals.

## The manipulations applied to the dataset as part of the analysis:
To construct this pie chart, the marks were changed to a pie chart. Chemical names were dragged to the color mark, segmenting the pie based on each distinct chemical. To determine the size of each chemical segment, the count of chemical removals was applied to the size mark. This count was derived by applying a measure to the chemical removal dates, totaling the instances each chemical was removed from a product. To focus on the most frequently removed chemicals, a filter was implemented to display only the top 5 based on their removal count across all products. Chemical names and their corresponding removal counts were then added to the label mark, providing clear identification and justification for the size of each pie segment.
The donut shape of the pie chart was achieved by creating a calculated field labeled "placeholder," which was added to the rows column and duplicated. The second instance of the pie chart was then edited to be entirely white and reduced in size. Applying a dual axis combined these two pie charts, resulting in the white, smaller pie overlaying the larger, colored pie, thus creating the central hole characteristic of a donut chart. 
Finally, for enhanced readability and organization, the chemical names were sorted in descending order according to their chemical removal count.

## Analysis and Results: 

![image](https://github.com/user-attachments/assets/7f5aa91b-5348-4504-98f0-c6fdbea53a2e)

### Titanium dioxide is the number one chemical removed:
Titanium dioxide (TiO₂) is a widely used ingredient in cosmetics—especially in sunscreens, foundations, and powders—for its ability to reflect UV light and provide coverage. However, it's become a topic of concern in recent years, especially in certain forms. It can be very dangerous when inhaled so it needs to be removed, especially for safety of workers and consumers who could inhale it.

### Cocamide diethanolamine is the number 2 chemical removed:
Cocamide DEA (Cocamide Diethanolamine) is another chemical ingredient that has raised red flags, especially in shampoos, body washes, and facial cleansers.The International Agency for Research on Cancer (IARC) classifies Cocamide DEA as "possibly carcinogenic to humans”. The risk stems from nitrosamines, which can form when Cocamide DEA reacts with certain preservatives or contaminants. These are potentially cancer-causing.

### Further analysis:
We could look at what exact products these chemicals are found in and make further implications on what specific products may be harmful for or use. While the FDA regulates cosmetic products and has banned certain chemicals from being used in cosmetic products or mandated a chemical to be removed from cosmetic products, this does not happen very often in the grade scheme of the vast number of chemicals used in cosmetics. Thus, consumers should be on the look-out for these chemicals in their products

# Tableau Packaged Workbook
link to workbook: https://github.com/sruj-siva/mist4610project2/blob/main/MIST%204610%20Project%202%20Tableau%20Graphs.twbx










