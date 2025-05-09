# Overview

This analysis was created to review the superstore’s operations, providing insight for the purpose of increasing profitability and to avoid bankruptcy.  
The analysis was done in three parts:  (1) Profits & losses (2) Advertisement Strategies (3) Insight on Products Returns.  Data Visualization was performed with Tableau Desktop Public.
We conducted an analysis on the financial performance of a superstore.  We found that based on profit and losses that the store should consider removing several departments and products from their superstore.  Furthermore, we also determined if advertising was being considered that various states would benefit from advertising at different times of the year. Lastly, we explored abnormal returns and its relation to average profits of the superstore.  With all this in mind, we recommend that the superstore seriously consider restructuring departments their business by discontinuing service in different regions as well as stop selling products in certain departments.  


# Key Insights:
- The two biggest profit centers and two biggest loss-makers were identified by combining dimensions such as product category, region, and shipping mode.
- Products that generate significant losses were visualized, helping identify those that the Superstore should consider stopping sales for.
- The analysis of product subcategories revealed which ones should be prioritized and which should be reduced or eliminated.
- We identified important centers of profit and loss for the superstore.  We choose to use profit margin for our analysis because this key metric provides an in-depth perspective on financial performance.  We chose to highlight the relationship between profit, revenue and sales efficiency.  Profit margin shows how efficiently sales were converted into profits.  
- For our analysis, we used three sets of paired dimensions:  (region+subcategory,  shipping mode+product ID, region+state).
- For our analysis of region+subcategory, we determined that in all regions (Central, East, South and West), ‘Paper’ was the top profit center.
- The second biggest profit center was ‘Furnishing’ in the East, South and West, but in the Central region it was ‘Art’.  Consequently, the 2 biggest loss-makers were also identified.   - We found ‘binders’ were the biggest loss makers in the Central, East and South regions.
    - In the West, however, the biggest loss-maker was ‘Bookcases’.  ‘Tables’ were the second biggest loss-maker in the East, South and West, but in the Central Region it was ‘Appliances’.  
- For our analysis of shipping mode+product ID, we determined that standard shipping and second class shipping offered the biggest profit centers; whereas first class and same day delivery were two biggest loss-maker.  
  - Regionally, the data shows that the Central and South Region are the biggest loss-maker and that the West and East Region are the biggest profit-center.

- To identify what products the superstore should stop selling we identified the products based on three analysis strategies: (1) Subcategory Sales Analysis (2) Profit Sales Analysis and (3) Product Sales in the Bottom 20%.
- We chose three methods of sales analysis for determining when to stop selling a product because it provides data-driven insights into the product's performance and profitability.
- First, we determined which categories demonstrated the lowest profit margin.
- Based on our analysis of big loss-makers, we found ‘Binders’, ‘Appliances’, ‘Tables’, ‘Bookcases’ and ‘Machines’ were the top five (5)  loss-makers subcategories for the superstore.  
  - Next, we determine discontinued projects based on sales.  For the subcategory sales analysis we filtered sales in the bottom 20% (2880) and products that had no ($0)profit.   Based on sales analysis, we noticed that Zebra GK420T Direct Thermal/Thermal Transfer Printer, with -3753 profit and low 2818 sales might be a good product to discontinue.  
- Lastly, we used profitability sales analysis to determine products that the superstore should stop selling based on profitability.
- We identified GBC VeloBinder Electric Binding Machine (Profit Margin -11.8, Profit -21,558, Sales 19598) and Cubify Cube X 3D Printer Double Head.  
-Based on our analysis, the Superstore should eliminate 3 departments to maximize profitability, appliances, machines and tables.



### Visualizations:

- **Profit Margin of Sub-Categories by Region**:[https://public.tableau.com/views/ProfitMarginofSub-CategoriesbyRegion/Figure1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
- **Shipping Mode Based on Region**: [(https://public.tableau.com/views/ShippingModeBasedonRegion/Figure2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Profit Margin Based On Subcategory**: [(https://public.tableau.com/views/ProfitMarginBasedOnSubcategory/Figure3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Sales Vs Profit based on Product Name**: [(https://public.tableau.com/views/SalesVsProfitbasedonProductName/Figure4?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Sub-Category Sales Analysis**: [(https://public.tableau.com/views/Sub-CategorySalesAnalysis_17325556003680/Figure5?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Bottom 20% Sales Based on Product Name**: [(https://public.tableau.com/views/Bottom20SalesBasedonProductName/Figure6?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Profit Margin based on Subcategory and Region**: [(https://public.tableau.com/views/ProfitMarginbasedonSubcategoryandRegion/Figure7?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
  

## Part 2: Advertising

### Key Insights:
- The best combinations of states and months for advertising were identified, where advertising could yield the highest return.
- A "Return on Ad Spend" analysis was done, showing which states and months would justify advertising spend.

### Visualizations:

- **Profit Margin based on State**: [(https://public.tableau.com/views/ProfitMarginbasedonState/Figure8?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **3 best combination of states and month**:  [(https://public.tableau.com/views/3bestcombinationofstatesandmonth/Figure9?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Avg Profit of 3 top states by Month**:  [(https://public.tableau.com/views/AvgProfitof3topstatesbyMonth/Figure10?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Advertisement Budget by State and Month**:  [(https://public.tableau.com/views/AdvertisementBudgetbyStateandMonth/Figure11?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]

### Key Insights:

- Products and customers with the highest return rates were identified, helping the Superstore understand which products might need to be reviewed or discontinued.
- A correlation between return rates and profits was analyzed to provide actionable insights on which dimensions (e.g., shipping mode, state) have the highest impact on profitability and return rates.
-Based on our analysis, the months of March, September and August, for California, Washington DC and New York, respectively would be the best month. to launch an advertisement campaign.  We used ⅕ of profits to determine the return on ad spend ratio.
-Returns, we also analyzed what subcategory generated the most returns.
  - We found paper, binders and phones.  However, the superstore shows a profit in phones
  - An abnormal rate of returns on 'paper' should be explored.  

**Recommendations**

- Discontinue:  Tables and Binders from the superstore.   
- Focus on Marketing or Repositioning:
    - Since the return rate is low, customers are not dissatisfied with the product.
    - It’s an indication that, with the right strategy, the product can be sold better.
- Consider revising the product’s marketing strategy, targeting a new audience or positioning the product differently to increase sales.
-Improving Product Offering:
    - The product may need adjustments to appeal to a broader audience.
    - Enhancing its features, packaging, or bundling it with other products could help increase its appeal and profitability.
-Pricing Optimization:
    - Test different pricing strategies to increase profitability without raising the return rate (e.g., discounts, seasonal pricing).

### Visualizations:
- **Returns Based on Product Name**: [https://public.tableau.com/views/ReturnsBasedonProductName/Figure12?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
- **Returns Based on Subcategory**: [(https://public.tableau.com/views/ReturnsBasedonSubcategory/Figure13?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Return Status based on Customer Name**: [(https://public.tableau.com/views/ReturnStatusbasedonCustomerName/Figure14?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
  **Avg Profit Vs Avg Returns**:  [(https://public.tableau.com/views/AvgProfitVsAvgReturns/Figure15?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]


## Installation and Setup

1. Clone or download the repository.
2. Open the `.twb` or `.twbx` file in Tableau Desktop.
3. Make sure that any data connections are correctly set up.

## Data Sources

The data used for this project was sourced from the Superstore dataset. It includes orders, returns, and product information.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Tableau Public Link
You can view the dashboard on Tableau Public here: [Link to Tableau Public Dashboard]
