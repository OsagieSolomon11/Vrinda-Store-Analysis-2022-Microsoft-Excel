# Vrinda-Store-Analysis-2022-Microsoft-Excel


INTRODUCTION

What can the store do better to make more sales and through what means? The task is to create an analysis and derive insights from the 2022 store sales and share them with stakeholders, so we can plan better for 2023.

This dataset is gotten from kaggle. After loading the data set into an Excel worksheet, the following metrics were what I had written out to help me get those insights.

Tool used:

Microsoft Excel

Compare the sales and orders using a single chart.
• Which month got the highest sales and orders?
• Who purchased more — men or women in 2022?
• What is the different order status in 2022?
• List the top 5 states that contribute to the sales.
• Relation between age and gender based on a number of orders.
• Which channel is contributing to maximum sales?


<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*sgxQbVf6Sqxk5eM3.jpeg">

Data cleansing starts now. The original data should be copied to a new worksheet, which will serve as our working sheet. Numerous disruptive elements may be found in the dataset. Verify that the header rows’ spelling is correct.

P.S. You may also color-fill the header rows to make a noticeable distinction.

Applying filters to all of the cells is the best and first approach to handle them. We can quickly observe which data items exist in each row thanks to the filters that have been set up.

Men and women have different spellings in the Gender column, as can be seen. The home tab’s search and replace button makes it simple to fix this.


<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*DEDixtwucwv_aaUL.png">

The outcome:

<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*twwQOi5XWFSqWnpb.png">


The Quantity column would be another place to search, and the same find and replace tool would be used to fix this.

<img src="https://miro.medium.com/v2/resize:fit:614/format:webp/0*1n_DhTdHlNz5PWXI.jpeg">

We would need to make two new columns based on two questions in our analysis report in order to do this. An “age group” would be the first, allowing us to quickly identify the groups of individuals in our database. Using the method below, the three groups “Senior, Adult, and Young” would be represented.


 <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/0*Ub3jfYfra8iEFFx9.jpeg">
 

 The following would be the actual sales months. A simple formula may be used to resolve this.

 
 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*y3acMlLoj8aVJm-o.jpeg">

 My data cleaning is now finished and ready for analysis. It is significant to notice that the dataset did not have a revenue column, making it difficult to produce a few graphs and figures.


 DASHBOARD VISUALIZATION

We can now combine all of our tables and charts after they have been prepared. To do this, we make a new sheet and give it the name “Dashboard.” In this sheet, put all of our charts. I’ll provide the stakeholders with this project’s final appearance. In order to make it easier to navigate and display stats for each subcategory (Month, Channel, Category), I have created 3 slicers. This is the finished appearance after connecting the slicers to the dashboard.


 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*Qh5uBI3oRn3CWwOR.png">



