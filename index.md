## Project Background

FreshGoGo is the first ever Chinese online grocery and authentic Asian food shopping and delivery service in North America supported by advanced technical platform. FreshGoGo provides customers with fresh and high-quality of Fresh Vegetables, Poultry & Meat, Fish & Seafood, Pantry, Dry Goods, Frozen Items, Refrigerated Items, Snacks, Drinks, as well as gourmet Asian food from local famous stores and restaurants at competitive prices. FreshGoGo customers can not only choose grocery items and process an order through multiple devices (smart phone, tablet and PC), but also track the order/delivery status in real time from the point of order creation to the delivery, such as exact time when the order is loaded to the truck and when the order arrives. FreshGoGo offers nearby pickup locations and home delivery service. FreshGoGo makes grocery and food shopping & delivery fast and easy. In this project, I used the dataset for predictive data analytics purpose and developing customized reports and analysis to provide business insights that aid in driving growth, expansion and finalizing critical business decisions.


## Data Description
After communicating with the operation team, I am provided with historical two months sales data for Fresh GoGo stores located in different regions. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. Predicitve and sale data analytics methods are easy to apply with this dataset. Each documents contains number of customer ID and products infomations, and I am tasked with with predicting the department-wide sales and need to solve the following problem: use existing data, divide different customer types, brake can understand that the customer is a high-quality supermarket customer, and provide it to the marketing team opinion. 1. Best Product Analysis 2. Sales time point analysis 3. Customer order volume analysis

In addition, Fresh GoGo runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this project is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.


## The main python libraries used are：pandas、numpy、matplotlib、seaborn 
## Datasets 


Order+data+20200629-20200712.csv Order+data+20200713-20200726.csv 
This file contains anonymized information about the 45 stores, indicating the type and size of store.

xiaoshouliushui20200629-0712.xlsx xiaoshouliushui20200713-0726.xlsx

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales -  sales for the given department in the given store
IsHoliday - whether the week is a special holiday week
test.csv

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week


Some basic data of existing supermarket shopping mall customers, such as Customer ID, Consumption amount, Order amount, order time. 
1. Python model and data import 
2. Two data format merging and data processing 
3. Need to solve the problem: use existing data, divide different customer types, brake can understand that the customer is a high-quality supermarket customer, and provide it to the marketing team opinion. Best product analysis analysis 
4. Sales time point analysis 
5. Customer order volume analysis

You can use the [editor on GitHub](https://github.com/AnnetteChiu/Project_Display/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
[Link](url) and ![Image](src)
[Link](https://octodex.github.com/images/yaktocat.png) and ![Image](src)
![](https://octodex.github.com/images/yaktocat.png)

```
![](https://octodex.github.com/images/yaktocat.png)


![](https://github.com/Geoffrey0107/Geoffrey-Duan/blob/gh-pages/Screen%20Shot%202020-09-07%20at%2011.34.29%20PM.png)

#[Link](https://octodex.github.com/images/yaktocat.png) and ![Image](src)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AnnetteChiu/Project_Display/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
