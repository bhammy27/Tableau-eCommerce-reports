# Munchy Sales and Shipping Analysis
Munchy, an eCommerce pet supply company based in Los Angeles, has experienced significant growth in the Eastern United States. The welcomed sales increase created extremely high shipping costs. Building a new fulfillment center will reduce shipping rates although it will take 5 years until the center opens. In the meantime, Munchy would like to gain a better understanding of the top selling products as well as gain a further understanding of the shipping cost of each product and create ways to increase the quantity of goods shipped per invoice. Data Analysts at Munchy created the following Tableau dashboard, found [here](https://public.tableau.com/app/profile/bryan.hamilton27/viz/EcommerceSalesShippingAnalysis/SalesSummary).

**This analysis aims to provide solutions by better understanding the following questions:**
1. Which products generate the most sales?
2. How much does shipping each product cost?
3. How could Munchy increase the quantity of items shipped per invoice?
4. What location in the Eastern United States would reduce customer shipping distances to within 1,000 miles?

## Product Sales Report 

![Screenshot (151)](https://github.com/bhammy27/eCommerce-Munchy/assets/154477061/a9e90176-d83c-4574-89ed-5134abde359c)

The Product Sales Report provides the following information:
- Taste of the Wild dry dog food sales double that of the second highest selling product
    - The **40-pound bag raises concern** regarding shipping costs
    - 3 other products have a higher Profit percent
        - All 3 products appear to have less weight and seem to have a cheaper shipping cost
            - Of the 3 items, Chom Chom Pet hair remover generates over 63% profit
- The home state of California leads all sales followed by Florida then Texas
    - California and Florida account for the highest total Taste of the Wild dog food sales
    - **Taste of the Wild dog food sales account for 20% of all sales in Florida**
        - Consideration should be made to build the new fulfillment center in Florida

## Product Shipping Cost Report

![Screenshot (153)](https://github.com/bhammy27/eCommerce-Munchy/assets/154477061/5a99e8d7-2cb2-40cf-8dba-ec1e61570946)

The Product Shipping Cost report provides valuable shipping information. The standard shipping rate considers a shipping radius of 1,000 miles. Rates increase every 500 miles after that. As the quantity of items per invoice increases, the shipping cost decreases by a percentage.  The cost of shipping a second item decreases by 20% while shipping 7 items reduces shipping cost by 50% per item. Comparing the **Baseline** shipping cost of one item with a **What-If** cost of shipping x number items provides insight into ways to reduce shipping cost. Adjusting the shipping quantity in this report identifies cost savings.
- Adjusting the shipping quantity shows that cost savings begin when shipping **3 or more** items
- Shipping **10 items** reaches the maximum savings discount
- Florida and Texas have high shipping costs followed by Illinois and New York

## Market Basket Report

![Screenshot (152)](https://github.com/bhammy27/eCommerce-Munchy/assets/154477061/b65188b6-f90f-4840-a971-52dd5c8625bd)


As we have determined, shipping rates decrease as the quantity of products increases.  Applying a Cross Selling strategy at the point of checkout can increase the number of purchased items, lowering shipping costs.  Utilizing a Market Basket chart identifies correlations between products commonly purchased together.  This would also be a great time to apply upselling techniques by suggesting more profitable items.  
- Suggest selling **ChomChom Reusable Hair Remover with purchases of Taste of the Wild dog food**
    - These items have a good correlation value of 0.63
        - **ChomChom also has the highest profit margin at 63.85%**
- Sheba Perfect Portions cat food as a profit margin 8.23% higher than Canned Cat food
    - Both products have high correlation values with Pet Odor Eliminator
        - Canned cat food correlation value is 0.77
        - Sheba cat food correlation value is 0.99
    - **When customers purchase Canned cat food Upsell Sheba cat food**, especially if Pet Odor Eliminators are also purchased

## New Fulfillment Center

Munchy already identified the need for a new fulfillment center in the Eastern United States. We have also identified that shipping rates increase every 500 miles over 1,000 miles.  The ideal location for the new center would be in a city that places as many customers as possible within a 1,000-mile radius.  Based on the Sales and Shipping reports, Florida would be an ideal location.  Florida has the highest number of customers, highest sales, and highest shipping expenses outside of California. Jacksonville would be an ideal Florida city given its access to I-95 and a large airport. Because of Jacksonville's location in northern Florida, the distance to New York would be reduced vs locating the fulfillment center in South Florida. The dashboard below suggests otherwise.

![Screenshot (154)](https://github.com/bhammy27/eCommerce-Munchy/assets/154477061/e5d613bd-4f5a-4235-b5d4-88d4cda41531)

- **Jacksonville** does place all Texas and New York customers within 1,000 miles
    - The Great Plains states and northern Mid West states remain over 1,000 miles away
    - **10.6%** of sales in the continental United Stats remain outside of the 1,000-mile radius
- **Dayton Ohio** provides the perfect location
    - **100%** of the customers within the continental United States have a shipping distance under 1,000 miles
    - Dayton's location at the **intersection of I-75 and I-70** provides perfect opportunities for shipping via trucking
    - Dayton has a mid-size **airport perfect for commercial shipping**
    - Dayton has **cheaper real estate rates**
    - Only disadvantage from Florida is Florida has no state taxes
      

