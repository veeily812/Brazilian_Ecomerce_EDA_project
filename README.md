# Brazilian E-Commerce Public Dataset by Olist

Welcome! This dataset contains real, anonymized commercial data from Olist, the largest department store in Brazilian marketplaces. It covers over 100,000 orders placed between 2016 and 2018 across multiple Brazilian marketplaces.

## Dataset Overview

The dataset provides a comprehensive view of each order, including:
- **Order Status:** Track the progress of orders from placement to delivery or cancellation.
- **Price & Payment:** Detailed information on item prices, payment types, and transaction values.
- **Freight Performance:** Insights into shipping costs and delivery timelines.
- **Customer Location:** Anonymized customer data with associated Brazilian zip codes and geolocation information (lat/lng).
- **Product Attributes:** Details about product categories, descriptions, and physical characteristics.
- **Customer Reviews:** Survey responses and written feedback, with all company and partner names replaced by Game of Thrones great houses for privacy.

For more information about Olist, visit: [www.olist.com](https://www.olist.com).

## Data Exploration 
- First we doing to load the dataset and remove all NaN values
- Then we going understand the data by visualization
- After that, we gonna do feature engineering for creating new columns which contain valuable insights
- Finally, we make assumptions for our dataset and recommendation. In this dataset, we explored the potentials for logististic department.
## +) Insight 1

<img width="1483" height="784" alt="image" src="https://github.com/user-attachments/assets/7e0ee31f-5254-4ab3-a7c2-3260b53e41bf" />

This section summarizes key findings from the analysis of delivery durations and delays across product categories.

### 1. Product Category Impacts Delivery Performance
Some categories consistently have longer carrier handling times, delivery durations, or delays such as
+ aticos de natal (chirstmas decoration)
+ móveis escritório (furniture designed for office or workspace)
+ fashion calcados (Styled shoes and footwear).

It indicate these products take longer to reach customers.

### 2. Carrier Handling and Delivery Delays Are Not Uniform
- The difference in blue (carrier handling days) and orange (delivery delay days) bars across categories suggests that logistics efficiency and punctuality vary by product type.
- Categories with negative delivery delay days (orange bars below zero) may be delivered earlier than estimated.

### 3. Potential Bottlenecks or Efficiency
- Categories with high carrier handling days might face bottlenecks in shipping or require special handling.
- Categories with low or negative delivery delay days may have more reliable or faster delivery processes.

### 4. Areas for Improvement
- Product categories with consistently high delivery delays or durations could be targeted for process improvements.
- Understanding which categories are most affected can help optimize logistics and customer satisfaction.

## +) Insight 2

<img width="1236" height="1770" alt="image" src="https://github.com/user-attachments/assets/507c417c-972d-4cb1-b854-4ecbd36260f3" />

The "Distribution of Product Categories" pie chart reveals which product categories dominate the marketplace and where strategic focus could yield the greatest results. According to the chart, the categories with the largest segments—and therefore the highest sales volume or product count—are:

- **cama_mesa_banho** (bed, table, and bath items): Includes sheets, towels, bedding, and tablecloths.
- **beleza_saude** (beauty and health): Encompasses skincare, cosmetics, haircare, supplements, and personal care products.
- **esporte_lazer** (sports and leisure): Covers exercise equipment, outdoor gear, and recreational items.
- **moveis_decoracao** (furniture and decoration): Consists of sofas, chairs, tables, lamps, and home decor accessories.
- **informatica_acessorios** (computer accessories): Includes keyboards, mice, monitors, cables, and other tech peripherals.
- **utilidades_domesticas** (household utilities): Features kitchen tools, cleaning supplies, storage solutions, and everyday household items.
- **eletrônicos** (electronics): Comprises smartphones, tablets, computers, televisions, and audio equipment.

Focusing on these high-volume categories can help maximize sales and market share, as they represent the core interests of the customer base. Additionally, monitoring trends in these categories allows for timely inventory adjustments and targeted marketing campaigns. For further growth, consider exploring opportunities in smaller yet emerging segments such as **brinquedos** (toys), **perfumaria** (perfumery), and **bebe** (baby products), which may offer potential for expansion with the right promotional strategies.

By prioritizing these specific product categories, the marketplace can better align its resources with consumer demand and drive sustained business growth.
## +) Insight 3
<img width="870" height="556" alt="image" src="https://github.com/user-attachments/assets/d8d61048-a0da-470c-a53a-ffad99a39bf6" />
<img width="879" height="556" alt="image" src="https://github.com/user-attachments/assets/f5ca5b21-80cc-4849-9b47-13f414b7fa29" />


The "Peak Shopping Hours" bar chart reveals clear patterns in customer purchasing behavior throughout the day. The highest volume of orders occurs during the late afternoon, specifically around 3 PM to 4 PM, with order counts exceeding 7,000 during these hours. This suggests that customers are most active and likely to make purchases in the mid-to-late afternoon, possibly coinciding with breaks from work or daily routines.

Order volume drops significantly during the evening and reaches its lowest point in the early morning hours (midnight to 5 AM), where fewer than 1,000 orders are placed per hour. This pattern indicates that shopping activity is minimal overnight and gradually increases as the day progresses.

**Assumption:**  
Businesses can optimize marketing campaigns, promotions, and customer engagement strategies by targeting peak shopping hours in the afternoon. Additionally, staffing and logistics can be adjusted to accommodate higher order volumes during these times, improving operational efficiency and customer satisfaction.
