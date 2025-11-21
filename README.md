# BCG-Dog-Treat-Co
This fictional dog treat company seeks to understand how their 8 different products in stores are performing. Which products should they invest in? What products hold large market shares in the dog industry? Lets find out with this fictional dataset and business analysis tool, the BCG matrix!

### Finished Product: ###
<img width="623" height="261" alt="image" src="https://github.com/user-attachments/assets/1a117473-d897-46ae-aa64-fcfe59607252" />

### Data Source ###
[Dataset](https://www.kaggle.com/datasets/taweilo/store-sales-data-20222023)

### 2025 Notes on the Project ###
I did this project in 2024. I was inspired by the sample questions the Kaggle Dataset Description offered such as Product Insights and Store Insights. I held off on publishing as I was trying to reframe this fictional dataset to be representative of a Holiday (like Halloween). A year later, I reframed it to something more generally applicable and decided to publish it as is since I completed objective 1 — The BCG matrix. This project was certainly an undertaking and exposed me to the business analysis side of things. I also think it stretched Excel’s limits. There are certain things that I’m better at now than I was a year ago, but I think its a good project regardless 😊.  <br>

### Programs Used ###
- Excel

### Objectives ###
1. Product insights: identify the product sales analysis, such as BCG Matrix

### Data Challenges ###
- This dataset had LOTS of data and LOTS of stores! This made cleaning a little challenging.
- To discover the BCG matrix, we needed to sum all the data from all the stores for 1 item.

### Raw Dataset Transformations ###
|Issue|Transformation|Date Completed|
| ------------- | ------------- | ------------- |
|Dates not formatted in correct data type |Changed dates to short date data type.  | 10/5/2024|
|No “sum” column for a single store’s item sales |Added a YTD column | 10/5/2024|
|Blanks in datasets in cases of no sales |Find and replaced with 0’s | 10/5/2024|
| |Added a Sum of sales Table per item for 2022 and 2023 |  10/5/2024|
| |Added a “YTD +/-” Table per item to show sale increase/decrease based on prior year | 10/11/2024|
| |Added a “Total Increase/Decrease in Sales for 2023” Table| 10/11/2024|
| |Created “Sales Trends over Time” Tables by calculating all the sales of the items per month| 10/11/2024|
| |Created an “Item Market Share and Growth Rate” table| 10/11/2024|
| |Created a Scatter Plot BCG Matrix| 10/11/2024|

### Important Formulas ###
=SUMIF($A$2:$A$5394,"A",$Z$2:$Z$5394)
- Checks if an item SKU is A and then add it to Sum <br>

### Data Opportunities ###
As the data is missing 2023’s months 10, 11, and 12, I played around with creating a data forecast for the sales in those months. Unfortunately, I’m not very experienced in that area. I considered imputation of the missing data using median/means but I read that those methods are incredibly inaccurate.  After some research and experimentation, I decided it would be better to just exclude 10, 11, and 12 from both 2022 and 2023 so I can have a direct comparison.

### Item Review ###
|SKU|Item Description|
| ------------- | ------------- |
| A | 12oz Gravy Flavored Dog Biscuits|
| B | 8oz Peanut Butter Dipped Biscuits|
| C | 16oz Chicken Jerky Dog Treats|
| D | 8pc Birthday Cookies |
| E | 20pc Dried Rabbit Ears |
| F | 8oz Dried Chicken feet |
| G | 1pc Cow Hoof |
| H | 1pc Dried Cow Ears |

### BCG Matrix Results ###
<img width="542" height="258" alt="image" src="https://github.com/user-attachments/assets/bced20da-ed7f-44c2-9431-d8eb47bbd2a6" /> <br>

This is my first time creating a BCG Matrix and based on the graph we can draw a few conclusions about our items. To start with, I did not include the growth rate for items F, G or H. This is because we did not begin selling these items until 2023. We need more data to conclude their market share and growth rate.  <br>

As for the items we were able to calculate, A, B, and C are our “cash cows”. These items have a high market share and a low growth rate. They sell consistently and are good for funding investments into our question mark products like item E. Question marks are items that have the potential to turn into stars but need investments and attention to explore getting there. Item D is our dog item. While not performing terribly, this item has little market growth, and we might do well to fade Item D out entirely in the next few years. <br>

### Reflection ###
The BCG matrix uses simple math formulas in combination with analyzing how much market share a product must determine its worth and how to allocate resources towards the different kinds of products. The BCG matrix seems to struggle to consider context and long-term branding strategies. Ivan Muench wrote a linkedin article detailing how companies must consider the impacts any fading products could have on the brand overall. In the digital age, the BCG can become outdated quicker as products tend to “move through the quadrants” quicker than before.  <br>

In the case of dog treats company, I suspect the direction should be to watch trends closely to see how much market share our riskier investments like dried rabbit ears have, while continuing to support and bolster our cash cow dog biscuits and jerky. If rabbit ears become a star, we can re-evaluate the direction of the company and consider moving towards more natural products.   


