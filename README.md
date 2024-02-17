# AtliQ Mart Diwali and Sankranti Promotion Analysis

As I embarked on my second official data analysis project, I felt an exhilarating blend of curiosity and anticipation. As I delved into AtliQ Mart’s Diwali and Sankranti promotions, I uncovered insights that would shape not only their strategies but also the retail landscape itself. Join me on this analytical journey!

# Executive Summary

AtliQ Mart's Diwali and Sankranti promotions showcased impressive reach and impact in driving sales and revenue growth. The promotional activities, combined with strategic engagement with specific product categories and store locations, resulted in substantial revenue generation, enhanced customer engagement, and critical insights for future promotional strategies. The analysis highlights the success of different promotion types, the performance of individual products, and the influence of various store locations on sales. The documentation emphasizes the effectiveness of different promotion types, identifies top-performing products through incremental revenue, and provides actionable insights for enhancing future promotional strategies.

## Project Overview

AtliQ Mart, a retail giant with over 50 supermarkets in the southern region of India, conducted extensive promotional activities during the Diwali 2023 and Sankranti 2024 festive periods. The project involved analyzing and understanding the impact of these promotions on product sales, revenue generation, and incremental sales units to derive actionable insights for strategic decision-making.

### Data Sources

Data was sourced from [CODE BASICS](https://codebasics.io/challenge/codebasics-resume-project-challenge) resume project challenge #9. The project utilized transaction and sales data from AtliQ Mart's massive promotion during the Diwali 2023 and Sankranti 2024 campaigns. The data encompassed detailed transaction records, product category information, promotion type details, and store-specific performance metrics.

### Tool Used

[SQL](https://github.com/leonardiz/AtliQ-Mart-Promotional-Analysis-/blob/main/Atliq.sql) for data transformation and analysis.

[Tableau](https://lnkd.in/dUaBKUfu) for data visualization.

### Cleaning and Transformation

The dataset was obtained, and it was in a clean state upon acquisition. Subsequently, the data underwent standardization and transformation processes to ensure uniform analysis. The transformation process facilitated the calculation of actionable metrics such as incremental sold unit percentages (ISU%) and incremental revenue percentages (IR%) for each product category and promotion type during the campaigns.

## Data Analysis and Actionable Insights:

### KEY BUSINESS REQUESTS TO ANSWER

### Provide a list of products with a base price greater than ₹500 and
are featured in the promo type ‘BOGOF’ (Buy One, Get One Free)

The insights from the provided information about products with a base price greater than ₹*500* and featured in the ‘*BOGOF*’ (Buy One Get One Free) promotion types are as follows:

**Products Meeting Criteria:** Two products, namely “*Atliq_Double_Bedsheet_set* with promo code (*P08*)” and “*Atliq_waterproof_Immersion_Rod* with promo code (*P14*),” satisfies the specified criteria. Both of these products have a base price exceeding ₹500, making them eligible for consideration in the context of the promotional type ‘*BOGOF*.’

![“*Atliq_Double_Bedsheet_set* with promo code (*P08*)” and “*Atliq_waterproof_Immersion_Rod* with promo code (*P14*),”](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/a9a633d0-6615-4774-bbf2-892b3aea0bb2/Screenshot_2024-02-15_104815.png)

“*Atliq_Double_Bedsheet_set* with promo code (*P08*)” and “*Atliq_waterproof_Immersion_Rod* with promo code (*P14*),”

**Promotion Type ‘BOGOF’:** The ‘*BOGOF*’ (Buy One, Get One Free) promotion type is a strategy where customers receive an additional product for free when they purchase one at the regular price. In this case, the specified products, the double bedsheet set, and the waterproof immersion rod are part of this promotion, indicating a marketing strategy aimed at incentivizing customers to make purchases.

**Base Price Threshold**: The criterion of a base price greater than ₹500 indicates a focus on higher-priced products for this particular promotion. This pricing strategy may be intended to enhance the perceived value for customers, making the offer more attractive and encouraging them to engage in the promotion.

**Strategic Considerations:** Identifying products that meet these criteria provides valuable insights into the pricing and promotion strategy of the business. The inclusion of higher-priced products in the ‘*BOGOF*’ promotion suggests a strategic approach to boost sales of premium items, potentially attracting customers looking for greater value and savings on more expensive purchases.

**Customer Engagement:** Products with a higher base price and featured ‘*BOGOF*’ promotions have the potential to capture customer attention and drive increased engagement. Customers may perceive the opportunity to receive a free product with their higher-value purchase as a compelling incentive, influencing their buying decisions and contributing to increased sales.

### Generate a report that provides an overview of the number of stores in each city.

**Bengaluru:** Bengaluru emerges as the city with the highest concentration of stores, signifying its prominence as a key retail hub. The substantial number of stores suggests a robust market demand and business opportunities in the city.

**Chennai:** Chennai follows closely with eight stores, indicating a strong retail presence in the region. The city’s significant number of stores suggests a thriving market and consumer base.

![Screenshot 2024-02-15 105434.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/e2eef364-775c-49c1-814f-67193870e076/Screenshot_2024-02-15_105434.png)

**Hyderabad:** Hyderabad maintains a notable retail footprint with seven stores. The city’s substantial store count indicates a vibrant retail environment, potentially driven by consumer demand and market dynamics.

**Visakhapatnam:** Visakhapatnam boasts a considerable presence with five stores. The city’s retail landscape appears to be well-established, catering to the local population and contributing to the economic activity in the region.

**Coimbatore:** Coimbatore shares a similar store count with Visakhapatnam, suggesting a balanced retail market. The presence of five stores reflects the city’s role as a significant retail center in the region.

**Madurai:** Madurai features four stores, indicating a moderate yet stable retail environment. The city’s store distribution aligns with the local market dynamics and consumer needs.

**Mysuru:** Mysuru, with four stores, showcases a notable retail presence. The city’s store count reflects its importance as a retail destination, potentially driven by local demand and economic factors.

**Mangalore:**  Mangalore maintains a presence with three stores, suggesting a moderate but steady retail market.

**Trivandrum:**  Trivandrum features two stores, indicating a smaller but still significant retail presence. The city’s store distribution aligns with the local market dynamics and consumer demand.

**Vijayawada:** Vijayawada, with two stores, reflects a modest retail environment.

*With ten stores, “Bengaluru” is the city with the highest number of stores. On the other hand, with only two stores each, “Trivandrum” and “Vijayawada” has the fewest.*

### Generate a report that displays each campaign along with the total revenue generated before and after the campaign.

**Diwali Campaign Impact:**

The Diwali campaign had a substantial impact on total revenue generation. Before the campaign, the total revenue stood at *₹82,573,759*. However, after the campaign, there was a significant increase and the total revenue surged to *₹207,456,209*. This indicates that the Diwali campaign was highly successful in driving sales and revenue growth, showcasing its effectiveness in capturing consumer attention and boosting overall business performance.

**Sankranti Campaign Impact:**

Similarly, the Sankranti campaign also demonstrated a positive impact on total revenue. Before the Sankranti campaign, the total revenue was *₹58,127,429*. After the campaign, there was a notable increase, and the total revenue reached *₹140,403,941*. The Sankranti campaign contributed to a significant uplift in revenue, reflecting its effectiveness in engaging customers and driving sales during the promotional period.

![Screenshot 2024-02-15 111451.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/01ecd519-5fa9-4759-9170-ca62de99b4c3/Screenshot_2024-02-15_111451.png)

**Comparative Analysis:**

Comparing the two campaigns, it is evident that both the *Diwali* and *Sankranti* campaigns had a positive impact on revenue generation. The *Diwali* campaign, with a higher total revenue before and after, indicates a larger overall impact and potentially a higher level of customer participation and spending during this festive period. The *Sankranti* campaign, while also successful, had a comparatively lower total revenue before and after, suggesting a slightly less pronounced impact compared to the *Diwali* campaign.

**Strategic Considerations:**

The success of both campaigns underscores the importance of well-executed and targeted promotional activities. Understanding the revenue impact of each campaign provides valuable insights for future planning, allowing for strategic decisions on resource allocation, campaign timing, and promotional strategies to maximize revenue growth.

### Produce a report that calculates the incremental sold quantity (ISU%) for each category during the Diwali campaign.

The *ISU* percentages for each category during the Diwali campaign are as follows: *Combo1* (152.37%), *Home Appliances* (86.81%), *Home Care* (53.69%), *Personal Care* (20.67%) while *Grocery & Staples* (8.26%) *Combo1* has the highest ISU% of 152.37%, while *Grocery* & *Staples* ranks fifth with 8.26%.

**Combo1 Dominance:**

Combo1 emerged as the top-performing category during the Diwali campaign, boasting the highest Incremental Sold Quantity Percentage (ISU%) of *152.37%*. This indicates that Combo1 experienced a substantial increase in sold quantity during the Diwali campaign, showcasing its popularity and effectiveness in driving consumer engagement.

![Screenshot 2024-02-15 112351.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/52ecac15-6721-416b-85ed-b6c63f447f96/Screenshot_2024-02-15_112351.png)

**Performance Variation Across Categories:**

*Home Appliances* achieved a notable ISU% of *86.81%*, positioning it as the second-highest performing category. The strong performance suggests that Home Appliances had a significant impact on sales during the Diwali campaign. *Home Care* and *Personal Care* follow with ISU% values of *53.69%* and *20.67%*, respectively. While Home Care performed well, Personal Care experienced a more modest increase in sold quantity during the campaign. *Grocery* & *Staples*, with an ISU% of *8.26%*, ranks fifth among the categories, indicating a comparatively lower impact on sold quantity during the Diwali promotional period.

**Strategic Considerations:**

Understanding the varying performance across categories allows for strategic considerations in future campaigns. The exceptional performance of *Combo1* suggests that similar bundled or combo offers could be explored in other promotions to replicate success. *Home Appliances*, with a strong ISU%, present an opportunity for continued focus and potential expansion of product offerings in this category. While *Grocery* & *Staples* had a more modest ISU%, there could be potential for optimization or targeted promotions to enhance its performance in future campaigns.

### Create a report featuring the top 5 products, ranked by incremental revenue percentage (IR%) across all campaigns.

**Here are the top five products ranked by incremental revenue
percentage (IR%):**

**Atliq Waterproof Immersion Rod (IR%: 266.19%):**

The Atliq Waterproof Immersion Rod has demonstrated exceptional performance with a staggering IR% of 266.19%. Capitalize on the success of this product by exploring opportunities to cross-promote it with related items or bundle it with complementary products to maximize overall sales.

![Screenshot 2024-02-15 112915.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/c7edbf12-8b18-4d68-8a56-62b66d93a0cd/Screenshot_2024-02-15_112915.png)

**Atliq_High_Glo_15W_LED_Bulb (IR%: 262.98%):**

The Atliq_High_Glo_15W_LED_Bulb ranks second with a remarkable IR% of 262.98%. Leverage the popularity of this LED bulb by running targeted marketing campaigns, emphasizing its energy efficiency, and consider offering promotions or discounts to further boost sales.

**Atliq_Double_Bedsheet_set (IR%: 258.27%):**

The Atliq_Double_Bedsheet_set exhibits strong performance with an IR% of 258.27%. Consider introducing bundle deals or exclusive promotions for the Double Bedsheet set to maintain its momentum and entice customers with attractive offers.

**Atliq_Curtains (IR%: 255.34%):**

Atliq_Curtains secured a position in the top 5 with a noteworthy IR% of 255.34%. Focus on creating visually appealing displays and marketing materials for Curtains to enhance customer engagement. Consider introducing themed promotions or collaborations to increase the product’s visibility.

**Atliq_Home_Essential_8_Product_Combo (IR%: 183.33%):**

While slightly lower in IR%, the Atliq_Home_Essential_8_Product_Combo maintains a solid performance at 183.33%. 

*Explore avenues to upsell or cross-sell additional items within the Home Essential Combo, providing customers with a comprehensive solution and potentially increasing the average transaction value.*

### What is the total revenue generated by all
Atliq stores? What is the total revenue generated by all Atliq stores?

The total revenue generated by all Atliq stores reached an impressive *₹488,561,338*, showcasing the substantial financial impact and overall success of Atliq stores during the specified period.

**Impressive Financial Impact:**

The total revenue generated by all Atliq stores stands at a remarkable *₹488,561,338*. This figure signifies the collective financial performance of Atliq stores during the specified period.

![Screenshot 2024-02-15 113538.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/e79dccab-8f1e-4e5a-980b-72c8e83a598c/Screenshot_2024-02-15_113538.png)

**Overall Success Indicator:**

The substantial revenue figure suggests that Atliq stores have achieved a high level of success in generating sales across their various locations. Success in revenue generation is a key indicator of the effectiveness of business strategies, marketing efforts, and customer engagement.

**Market Presence and Performance:**

The cumulative revenue reflects the combined sales performance of Atliq stores and showcases their market presence and effectiveness in meeting customer demands. A higher total revenue implies that Atliq has successfully positioned itself as a significant player in the market, catering to the needs and preferences of a diverse customer base.

**Strategic Business Impact:**

The substantial financial impact underscores the effectiveness of the business strategies employed by Atliq stores. Strategic decisions related to product offerings, pricing, promotions, and customer experience likely contributed to the positive financial outcomes reflected in the total revenue figure.

**Benchmarks for Success:**

The *₹488,561,338* revenue figure serves as a benchmark for assessing the success and growth of Atliq stores during the specified period. It provides valuable insights for stakeholders, investors, and decision-makers to gauge the overall health and competitiveness of Atliq in the market.

### What is the total revenue generated by all Atliq stores before and
after promotion and the percentage increase/decrease in revenue?

The combined total revenue generated by all Atliq stores experienced a substantial increase during the promotional period. The total revenue before promotions amounted to *₹140,701,188*, and after the promotions, it significantly rose to *₹347,860,150*. This reflects an impressive percentage increase of *247.23%*, emphasizing the effectiveness of the promotional strategies in driving overall sales growth across Atliq stores.

![Screenshot 2024-02-15 114125.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/c6b09b67-063e-4fdb-9b6d-f77e55d15421/Screenshot_2024-02-15_114125.png)

### How many stores does Atliq Mart own?

Number of Atliq Mart Stores: Atliq Mart owns a total of 50 stores
distributed across various cities in the country.

![Screenshot 2024-02-15 114533.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/e9f8368b-d042-4ccc-b179-10db213ec50b/Screenshot_2024-02-15_114533.png)

Atliq Mart’s expansive retail presence, with 50 stores, signifies a substantial and widespread footprint in different cities. This broad geographical coverage suggests a strategic approach to catering to diverse consumer markets and tapping into various regional opportunities. The scale of operations across multiple locations positions Atliq Mart as a significant player in the retail sector, contributing to its overall market influence and potential for widespread consumer reach.

### What is the Total quantity sold by Atliq Mart (before and after
promo)?

**Total Quantity Sold:** The overall total quantity sold by Atliq Mart is
*644,523* units.

**Total Quantity Sold Before Promo:** Before the promotional campaigns,
Atliq Mart sold a total of *209,050* units.

**Total Quantity Sold After Promo:** After the promotional campaigns, the
quantity sold significantly increased to *435,473* units.

**Percentage Increase:** The percentage increase in quantity sold after
the promo compared to before is *108.31%.*

![Screenshot 2024-02-15 115143.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/7add4617-bb6d-4dca-af1e-484625231488/Screenshot_2024-02-15_115143.png)

The promotional campaigns had a substantial impact on sales,
contributing to a significant increase in the total quantity sold. The
percentage increase of *108.31%* highlights the effectiveness of the
promotional strategies in driving consumer engagement and boosting
overall sales for Atliq Mart.

## KEY FINDINGS AND INSIGHTS

### STORE PERFORMANCE ANALYSIS

### Which are the top 10 stores in terms of incremental revenue (IR)
generated from promotions?

The following stores rank in the *top ten* for incremental revenue (IR) generated by promotions:

**STMYS-1** generated an additional revenue of *₹6,446,961.*

**STCHE-4** generated an additional revenue of *₹6,317,711*.

**STBLR-0** generated an additional revenue of ₹*6,158,906.*

**STBLR-7** generated incremental revenue of ₹*6,124,481.*

**STBLR-6** generated an incremental revenue of ₹*6,008,349*.

**STCHE-7** generated *₹5,999,008* in incremental revenue.

**STMYS-3** generated *₹5,721,938* in additional revenue.

**STCHE-3** generated an additional revenue of ₹*5,707,253*.

**STCHE-6** generated *₹5,324,877* in additional revenue.

**STBLR-3** generated an incremental revenue of *₹5,209,263.*

![Screenshot 2024-02-15 123534.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/362780f9-bf4f-4f74-a6ce-816f6647a7a9/Screenshot_2024-02-15_123534.png)

**Diverse Store Contributions:** The *top 10* stores, including *STMYS-1*, *STCHE-4*, and *STBLR-0*, showcase a diverse range of locations contributing significantly to incremental revenue. This diversity suggests that the promotional strategies were effective across various store types and locations.

**Significant Incremental Gains**: Each store in the top 10 has generated substantial incremental revenue, with values ranging from *₹5,209,263* to *₹6,446,961*. The magnitude of these additional revenues underscores the success of promotional activities in driving increased sales and customer engagement.

**Consistent Performance**: Stores like *STBLR-7*, *STBLR-6*, and *STCHE-7* have consistently performed well in generating incremental revenue. Consistency across multiple stores implies the effectiveness of promotional strategies being applied consistently or tailored to specific store contexts.

**Strategic Impact of Promotions:** The notable revenue increases indicate the strategic impact of promotions in boosting sales and driving customer spending. The stores’ ability to leverage promotions for revenue growth highlights the importance of well-executed marketing initiatives.

These stores stand out for making significant contributions to incremental revenue from promotional activities.

### Which are the bottom 10 stores when it comes to incremental sold
units (ISU) during the promotional period?

The following stores are positioned in the bottom ten based on incremental sold units (ISU):

**STMLR-0:** 1,952 units

**STVSK-3:** 2,209 units

**STVSK-4:** 2,469 units

**STTRV-1:** 2,604 units

**STMLR-2:** 2,664 units

**STTRV-0:** 2,733 units

**STVJD-1:** 2,763 units

**STMLR-1:** 2,784 units

**STCBE-4:** 2,927 units

**STVJD-0:** 3,046 units

![Screenshot 2024-02-15 125607.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/86682fae-a5c9-4526-83af-6fe0d321b6f8/Screenshot_2024-02-15_125607.png)

**Challenges in Incremental Sales:** Stores such as *STMLR-0, STVSK-3*, and *STVSK-4 f*ace challenges in generating significant incremental sold units during the promotional period. The lower ISU figures indicate potential difficulties in capturing the attention of customers or effectively converting promotional interest into sales.

**Varied Incremental Performance:** The bottom 10 stores exhibit varying degrees of incremental performance, with unit increments ranging from 1,952 to 3,046 units. This variance suggests that the factors influencing incremental sold units may vary across stores, requiring tailored strategies for improvement.

**Potential for Improvement:** Stores like *STCBE-4* and *STVJD-0*, while in the bottom 10, have comparatively higher incremental sales units, indicating potential for improvement with targeted efforts. Focusing on enhancing the performance of these stores may yield positive results in terms of incremental sales.

**Insights for Strategic Planning:** The data on bottom-performing stores offers insights for strategic planning, enabling stakeholders to allocate resources effectively and address specific challenges hindering incremental sales.

**Store-Specific Considerations:** Each store’s position in the bottom 10 suggests the existence of store-specific factors influencing incremental sold units. Analyzing these factors, such as local market dynamics or customer preferences can guide the development of targeted solutions for improvement.

*These stores are ranked towards the bottom in terms of incremental
sold units, reflecting their comparatively lower performance in this
metric.*

### How does performance by stores vary by city? Are there common
characteristics among top-performing stores that could be leveraged
across other stores?

### –What are the 10 stores that generated the
highest revenue during the Diwali campaign, and in which cities are they
situated?

Here are the top 10 stores that generated the highest revenue
during the Diwali campaign:

**STCHE-4**, City: **Chennai**, Revenue: *₹8,265,934*

**STMYS-1**, City: **Mysuru**, Revenue: ₹7,986,655

**STBLR-0,** City: **Bengaluru**, Revenue: ₹7,970,547

**STBLR-7**, City: **Bengaluru**, Revenue: ₹7,566,279

**STMYS-3**, City: **Mysuru**, Revenue: ₹7,527,696

**STCHE-7**, City: **Chennai,** Revenue: ₹7,447,971

**STBLR-3**, City: **Bengaluru**, Revenue: ₹7,437,204

**STCHE-6**, City: **Chennai**, Revenue: ₹7,396,184

**STBLR-6**, City: **Bengaluru**, Revenue: ₹7,387,109

**STBLR-8,** City: **Bengaluru**, Revenue: ₹7,376,144

![Screenshot 2024-02-15 142143.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/fb345640-2ae5-483c-9b5c-c538f6526d69/Screenshot_2024-02-15_142143.png)

**Top Revenue Stores:** The Diwali campaign saw remarkable revenue generation, with the top 10 stores contributing significantly to the overall success.

**Geographic Distribution:** The cities with the highest revenue-generating stores during the Diwali campaign are primarily Chennai, Mysuru, and Bengaluru.

**Chennai Dominance:** Chennai emerges as a key contributor, hosting *three* of the top 10 revenue-generating stores, with STCHE-4 leading at ₹8,265,934.

**Bengaluru's Strong Presence:** Bengaluru also demonstrates a strong presence, hosting *six* stores within the top 10, showcasing the city's economic importance during the Diwali period.

### –What are the 10 stores that generated the highest revenue
during the Sankranti campaign, and in which cities are they situated?

Here are the top 10 stores that generated the highest revenue during the
Sankranti campaign:

1. **STMYS-1,** City: **Mysuru**, Revenue: *₹5,538,872*
2. **STBLR-6,** City: **Bengaluru**, Revenue: *₹5,429,264*
3. **STBLR-7,** City: **Bengaluru**, Revenue: *₹5,268,674*
4. **STCHE-4,** City: **Chennai**, Revenue: *₹5,165,497*
5. **STBLR-5,** City: **Bengaluru**, Revenue: *₹5,112,159*
6. **STCHE-7,** City: **Chennai**, Revenue: *₹5,066,907*
7. **STCHE-6,** City: **Chennai**, Revenue: *₹5,064,667*
8. **STBLR-0,** City: **Bengaluru**, Revenue: *₹4,990,489*
9. **STCHE-3,** City: **Chennai**, Revenue: *₹4,943,048*
10. **STHYD-2,** City: **Hyderabad**, Revenue: *₹4,895,896*

![Screenshot 2024-02-15 143149.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/f67e9bdb-c47d-4abe-a83e-ac6e3d6c6cc0/Screenshot_2024-02-15_143149.png)

**Store Performance during the Diwali Campaign:**

The best-performing stores during the Diwali campaign were primarily in *Chennai* and *Bengaluru*. *Chennai* had three of the top ten stores (STCHE-4, STCHE-7, and STCHE-6), while *Bengaluru* had six (STBLR-0, STBLR-7, STBLR-3, STCHE-6, STBLR-6, and STBLR-8). During the Diwali campaign, one store in Mysuru (STMYS-1) made the top ten.

**Store Performance during the Sankranti Campaign:**

Similar to the Diwali campaign, *Bengaluru* and *Chennai* were key cities with high-performing stores during the Sankranti campaign. *Bengaluru* had six stores in the top ten (*STBLR-6, STBLR-7, STBLR-5, STBLR-0, STBLR-3, and STBLR-8*), whereas *Chennai* had three. During the Sankranti campaign, both *Mysuru* and *Hyderabad* had one store (*STMYS-1 and STHYD-2*) in the top ten.

**Common Characteristics of Top-Performing Stores:**

Both campaigns showed *Bengaluru* and *Chennai* stores dominating the top rankings, indicating that these cities consistently perform well. Despite only having one store in the top ten, the revenue generated by *Mysuru* stores during both campaigns suggests a significant contribution to overall performance. *Bengaluru* consistently had more top-performing stores than other cities in both campaigns.

These findings indicate that the cities of *Bengaluru* and *Chennai* are critical for revenue generation and that there may be common characteristics or strategies used by stores in these cities that contribute to their consistently high performance. Exploring and leveraging these commonalities may improve the performance of stores in other locations.

## PROMOTION TYPE ANALYSIS

### What are the top 2 promotion types that resulted in the highest
incremental revenue?

The promotion types that contributed the most to incremental revenue were *Cashback*, generating ₹122,643,000, and *BOGOF*, generating ₹69,316,990 in incremental revenue. *Cashback* promotions significantly drove incremental revenue, suggesting that such promotions resonate well with customers and encourage higher spending. *BOGOF* promotions also played a crucial role in revenue generation, indicating the effectiveness of buy-one-get-one-free offers.

![Screenshot 2024-02-15 143343.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/100e4408-076e-411f-aab4-8f008bb07736/Screenshot_2024-02-15_143343.png)

Cashback and BOGOF were the top 2 promo types with the highest incremental revenue.

### What are the bottom 2 promotion types in terms of their impact on incremental sold units (ISU)?

Examining the impact on incremental sold units (ISU), the two promotion types with the least influence were: 25% OFF, showing a decrease of 5,717 units. 50% OFF, indicating a modest increase of 6,931 units.

![Screenshot 2024-02-15 144430.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/1a7c9e23-1eb0-4a99-b237-2839ea1bb635/Screenshot_2024-02-15_144430.png)

Promotions like 25% OFF hurt incremental sold units, possibly indicating a reduced interest or effectiveness in terms of driving sales, While 50% OFF promotions showed a modest increase in sold units, the impact was relatively lower compared to the top-performing promotion types. Consideration may be given to refining the strategy for this promotion type or exploring alternatives with higher impact.

### Is there a significant difference in the performance of discount-based
promotions versus BOGOF (Buy One Get One Free) or cash-back promotions?

The distribution of incremental revenue percentages associated with various promotion types is as follows:

**BOGOF:** Achieved an impressive incremental revenue percentage of
*267.35%.* 

**500 Cashback:** Demonstrated substantial growth with an
incremental revenue percentage of *183.33%.* 

**33% OFF:** Contributed positively with an incremental revenue percentage of *42.87%.* 

**50% OFF:** Showed moderate growth, generating an incremental revenue percentage of
*32.81%.* 

**25% OFF:** Experienced a decline, resulting in a negative
incremental revenue percentage of *-12.81%.*

![Screenshot 2024-02-15 144829.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/e1f754f0-8f49-42d3-9107-ee4d3e4ba7ee/Screenshot_2024-02-15_144829.png)

*BOGOF* and *500 Cashback* promotions significantly outperformed others, indicating their effectiveness in driving revenue. *33% OFF* and *50% OFF* promotions also contributed positively, though at a relatively lower rate. The *25% OFF* promotion, however, resulted in a negative impact,
suggesting potential drawbacks or challenges associated with this particular offer.

### Which promotions strike the best balance between incremental sold
units (ISU) and maintaining healthy margins?

**BOGOF (Buy One Get One Free):** Impressive with *157,073 units,* indicating strong customer engagement. 

**Revenue Percentage:** High at *267.35%*, reflecting substantial revenue growth. BOGOF successfully combines a high volume of sales with a significant revenue boost, making it a well-balanced and lucrative promotion.

**500 Cashback:** Respectable at *40,881 units,* suggesting customer interest.
**Revenue Percentage:** Healthy at *183.33%,* demonstrating effective margin management. 500 Cashback strikes a good balance between driving sales and maintaining a favorable revenue percentage, making it a strategic choice.

**33% OFF:** Moderate at *27,255 units*, indicating a reasonable sales impact.
**Revenue Percentage:** Positive at *42.87%*, ensuring a healthy profit margin. 33% OFF maintains a balance between attracting customers and preserving profit margins, making it a viable promotional strategy.

**50% OFF:** Relatively lower at *6,931 units*, suggesting a focused customer
base. 

**Revenue Percentage:** Positive at *32.81%*, indicating a cautious approach to discounting. 50% OFF, while generating fewer sales, maintains a favorable revenue percentage, indicating a careful balance
between volume and profitability.

**25% OFF:** Negative at *-5,717 units*, signaling a decrease in sales. 

**Revenue Percentage:** Negative at *-12.81%*, indicating potential margin erosion. 25% OFF shows a negative impact on both ISU and revenue percentage, suggesting a need for reassessment or optimization to align with business goals.

![Screenshot 2024-02-15 151009.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/031e9fca-9d34-48c5-80bd-eab0811713ed/Screenshot_2024-02-15_151009.png)

*BOGOF* and *500 Cashback* promotions stand out as effective strategies for striking a balance between incremental sales and healthy profit margins.

## PRODUCT AND CATEGORY ANALYSIS

### Produce a report that calculates the incremental revenue percentage
(IR%) for each category during the Diwali and Sankranti campaigns.

The report calculates each product category’s Incremental Revenue Percentage
(IR%) during the Diwali and Sankranti campaigns. Here are the findings
from the data:

**Home Appliances:** Incremental Revenue Percentage (IR%) during *Diwali was 82.01% while* Incremental Revenue Percentage (IR%) during *Sankranti* was *183.20%.* Home Appliances experienced a significant boost in revenue during both Diwali and Sankranti, with a remarkable surge during the Sankranti campaign.

**Home Care:** Incremental Revenue Percentage (IR%) during *Diwali* was  *88.43% while* Incremental Revenue Percentage (IR%) during *Sankranti* was  *93.20%* Home Care maintained a strong performance, showing a consistent increase in revenue during both Diwali and Sankranti campaigns.

**Grocery & Staples:** Incremental Revenue Percentage (IR%) during *Diwali* was *12.89%* while Incremental Revenue Percentage (IR%) during *Sankranti* was *67.54%* Grocery & Staples saw a notable rise in revenue during the Sankranti campaign compared to Diwali, indicating a stronger impact on sales during Sankranti.

![Screenshot 2024-02-15 151402.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/c9082357-8331-48df-b69d-c652ea67d711/Screenshot_2024-02-15_151402.png)

**Combo1:** Incremental Revenue Percentage (IR%) during *Diwali* was *152.37% while* Incremental Revenue Percentage (IR%) during *Sankranti* was  *30.96%.* Combo1 witnessed a substantial surge in revenue during Diwali, but the impact was relatively lower during the Sankranti campaign.

**Personal Care:** Incremental Revenue Percentage (IR%) during *Diwali* was *20.50% while* Incremental Revenue Percentage (IR%) during Sankranti was  *5.96%.* Personal Care products experienced a moderate increase in revenue during Diwali, but the growth was minimal during the Sankranti campaign.

Overall, these findings provide a comparative analysis of how various product categories fared in terms of incremental revenue during the Diwali and Sankranti campaigns. The different percentages reflect the various effects of the promotional strategies on each category.

### Which product categories saw the most significant lift in sales from
the promotions?

The data provided demonstrates how promotional campaigns increased sales in specific product categories:

**Combo1:** With Sales of ****₹189,540,000 Combo1 experienced the most substantial lift in sales among the listed categories, indicating that the promotional strategies significantly boosted sales for this product grouping.

**Grocery & Staples:**  With Sales of **₹**95,615,960 Grocery & Staples also witnessed a considerable increase in sales, reflecting the effectiveness of promotions in driving consumer engagement and purchases within this category.

![Screenshot 2024-02-15 152456.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/a09614af-057d-4dc7-9a01-c2f049218945/Screenshot_2024-02-15_152456.png)

**Home Appliances:** With sales of ₹34,633,500 Home Appliances showed a notable lift in sales, suggesting that promotional activities positively influenced consumer interest and contributed to increased purchases within this category.

**Home Care:** With sales of ₹24,944,175 Home Care products experienced a significant lift in sales, indicating that promotional campaigns played a key role in driving consumer demand for items in this category.

**Personal Care:** with Sales of ₹3,126,515 While Personal Care saw a lift in sales, the increase was comparatively smaller than other categories. This suggests that promotional efforts had a moderate impact on driving sales within this product category.

*Combo1*, *Grocery & Staples,* and *Home Appliances* emerged as the top-performing categories with substantial lifts in sales, showcasing the effectiveness of promotional campaigns in driving
consumer engagement and boosting purchases for these product categories.

### Are there specific products that respond exceptionally well or
poorly to promotions?

The following are the product rankings based on revenue generated
after promotions:

**Atliq_Home_Essential_8_Product_Combo:**  with revenue after promotions at *₹189,540,000*, the  Atliq_Home_Essential_8_Product_Combo stands out as the top performer in revenue generation post-promotions, showcasing its strong resonance with consumers and effectiveness in driving sales during promotional periods.

**Atliq_Sonamasuri_Rice (10KG):** with revenue after promotions at *₹45,782,100* Atliq_Sonamasuri_Rice (10KG) secures a significant position in revenue, indicating its popularity and positive response to promotional activities, making it a noteworthy product within the lineup.

![Screenshot 2024-02-15 154558.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/8408ed92-5c57-4d26-92e6-e9f5b9cdb8bd/Screenshot_2024-02-15_154558.png)

**Atliq_Farm_Chakki_Atta (1KG):** with revenue after promotions at *₹29,100,500,* Atliq_Farm_Chakki_Atta (1KG) demonstrates robust performance in revenue generation post-promotions, emphasizing its appeal and consumer preference during promotional periods.

**Atliq_waterproof_Immersion_Rod:** with revenue after promotions at  *₹24,158,700*
The Atliq_waterproof_Immersion_Rod exhibits solid revenue figures after promotions, highlighting its effectiveness in capturing consumer attention and driving sales during promotional campaigns.

**Atliq_Double_Bedsheet_set:** with revenue after promotions at *₹17,919,020* Atliq_Double_Bedsheet_set performs well in revenue after promotions, indicating its popularity and success in enticing consumers during promotional events.

**Atliq_Suflower_Oil (1L):** with revenue after promotions at  *₹14,310,708* Atliq_Suflower_Oil (1L) shows strong revenue performance post-promotions, suggesting its appeal to consumers and effectiveness in capitalizing on promotional opportunities.

**Atliq_High_Glo_15W_LED_Bulb:** with revenue after promotions at  *₹10,474,800* Atliq_High_Glo_15W_LED_Bulb contributes significantly to post-promotion revenue, indicating its success in attracting consumers and driving sales during promotional periods.

**Atliq_Masoor_Dal (1KG):** with revenue after promotions at  *₹6,422,652* Atliq_Masoor_Dal (1KG) demonstrates respectable revenue after promotions, showcasing its appeal and ability to leverage promotional activities to boost sales.

**Atliq_Curtains:** with revenue after promotions at  *₹4,895,100* Atliq_Curtains secures notable revenue after promotions, indicating consumer interest and positive response to promotional efforts within this product category.

**Atliq_Fusion_Container_Set_of_3:** with revenue after promotions at *₹1,855,880* Atliq_Fusion_Container_Set_of_3, while lower in revenue compared to other products still showcases a positive response to promotions, contributing to post-promotion revenue.

**Atliq_Doodh_Kesar_Body_Lotion (200ML):** with revenue after promotions at *₹1,334,180* Atliq_Doodh_Kesar_Body_Lotion (200ML) contributes to post-promotion revenue, indicating consumer interest and success in leveraging promotional activities for increased sales.

**Atliq_Body_Milk_Nourishing_Lotion (120ML):** with revenue after promotions at  *₹671,830* Atliq_Body_Milk_Nourishing_Lotion (120ML) demonstrates a positive response to promotions, contributing to post-promotion revenue within its product category.

**Atliq_Lime_Cool_Bathing_Bar (125GM):** with revenue after promotions at  *₹637,360* Atliq_Lime_Cool_Bathing_Bar (125GM) contributes to post-promotion revenue, reflecting consumer engagement and successful promotional strategies.

**Atliq_Cream_Beauty_Bathing_Soap (125GM):** with revenue after promotions at  *₹483,145* Atliq_Cream_Beauty_Bathing_Soap (125GM) shows a positive response to promotions, contributing to post-promotion revenue and indicating consumer interest.

**Atliq_Scrub_Sponge_For_Dishwash:** with revenue after promotions at  *₹274,175* Atliq_Scrub_Sponge_For_Dishwash, while lower in revenue, still demonstrates a response to promotions, contributing to post-promotion revenue within its product category.

*The top-performing products can serve as benchmarks for success, while those with room for improvement present opportunities for targeted adjustments to enhance their effectiveness in driving sales.*

### What is the correlation between product category and promotion type
effectiveness?

The relationship between product category and promotion type effectiveness shows interesting patterns in both incremental sold unit percentages (ISU%) and incremental revenue percentages (IR%).

**Home Appliances:**

With an ISU Percentage of  *264.39%* and  IR Percentage of *265.21%*, Home Appliances exhibit a remarkably high correlation between the incremental sold unit percentage and incremental revenue percentage, suggesting that promotions have a consistently strong impact on both sales volume and revenue for this category.

**Combo1:**

With an ISU Percentage of *183.33%* and 

 Percentage of *183.33%,*  Combo1 demonstrates a
strong correlation between incremental sold units and revenue percentages, indicating that promotional strategies effectively drive both sales volume and revenue within this product grouping.

![Screenshot 2024-02-15 155540.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/7b5efc85-d7a9-495e-b47c-a9ed7030bd1e/Screenshot_2024-02-15_155540.png)

**Home Care:**

With an ISU Percentage of *106.60%* and IR Percentage of *181.63%,* Home Care products show a positive correlation between ISU and IR percentages. While there is a substantial increase in revenue, the sold unit percentage suggests that promotional efforts also contribute to boosting sales volume in this category.

**Grocery & Staples:**

With an ISU Percentage of *94.02%* and IR Percentage of *80.44%,* Grocery & Staples demonstrate a positive but less pronounced correlation between ISU and IR percentages. The incremental sold units show a slightly stronger response to promotions compared to the revenue percentage, indicating potential areas for optimizing promotional strategies.

**Personal Care:**

With an ISU Percentage of *24.50%* and an IR Percentage of *26.46%*, Personal Care products
exhibit a relatively lower correlation between ISU and IR percentages.
While promotions have a positive impact on both sales volume and
revenue, the correlation suggests moderate effectiveness compared to
other categories.

## Data Visualization

After much insight, it was time to visualize the data using TABLEAU. The dashboards also display key metrics and indicators, such as the total revenue, the percentage increase in revenue after promotions, and the promotion effectiveness. The dashboards help you to understand the trends and patterns in the data, and to identify the best-performing and worst-performing promotions.

![ATLIQ MART DIWALI AND SANKRANTI PROMOTION ANALYSIS 2 (1).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/f37639a9-5d71-43ac-aaac-10c99288e874/ATLIQ_MART_DIWALI_AND_SANKRANTI_PROMOTION_ANALYSIS_3_(1).png)

![ATLIQ MART DIWALI AND SANKRANTI PROMOTION ANALYSIS 2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/bbbca9f9-c9f4-49b0-8a7f-73cd617b26da/ATLIQ_MART_DIWALI_AND_SANKRANTI_PROMOTION_ANALYSIS_2.png)

![ATLIQ MART DIWALI AND SANKRANTI PROMOTION ANALYSIS (1).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/ca95aa82-c3b0-4ab4-8ed7-d756d9ee0439/ATLIQ_MART_DIWALI_AND_SANKRANTI_PROMOTION_ANALYSIS_(1).png)

![ATLIQ MART DIWALI AND SANKRANTI PROMOTION ANALYSIS 4 (1).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e80b3a97-f22f-4adb-98b3-f0293b86258e/ec4eb4f5-6266-46a4-8ba1-510389acde9a/ATLIQ_MART_DIWALI_AND_SANKRANTI_PROMOTION_ANALYSIS_4_(1).png)

## Recommendations:

**Store Optimization:** Leverage successful strategies from Bengaluru and Chennai stores for potential expansion. 

Conduct detailed analysis of underperforming stores to identify improvement opportunities.

**Promotion Strategy Refinement:** Focus on promotion types such as 'BOGOF' and 'Cashback,' which demonstrated significant revenue growth and positive impact on incremental sold units. -Reassess and potentially modify 25% OFF promotions for better effectiveness.

**Category-specific Strategies:** Continue emphasizing Home Appliances and Combo1 due to their strong correlation between ISU% and IR%. -Optimize promotional approaches for Grocery & Staples to align with consumer preferences.

**Product-specific Enhancements:** Leverage the success of top-performing products to tailor future promotional campaigns and explore cross-promotional opportunities -Implement targeted adjustments for products with room for improvement.

The AtliQ Mart Promotional Analysis offers actionable insights to optimize store performance, refine promotion strategies, and enhance the effectiveness of product categories and individual products. Implementing these recommendations can drive sustained growth and solidify AtliQ Mart's position as a retail leader in the Southern region of India.
