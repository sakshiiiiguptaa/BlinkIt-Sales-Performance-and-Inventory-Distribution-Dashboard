# BlinkIt-Sales-Performance-and-Inventory-Distribution-Dashboard

ᴘᴏᴡᴇʀ ʙɪ ᴘʀᴏᴊᴇᴄᴛ ꜱʜᴏᴡᴄᴀꜱɪɴɢ "ʙʟɪɴᴋɪᴛ ꜱᴀʟᴇꜱ ᴘᴇʀꜰᴏʀᴍᴀɴᴄᴇ ᴀɴᴅ ɪɴᴠᴇɴᴛᴏʀʏ ᴅɪꜱᴛʀɪʙᴜᴛɪᴏɴ"

👉𝗢𝗯𝗷𝗲𝗰𝘁𝗶𝘃𝗲:

To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

👉𝗦𝘁𝗲𝗽𝘀 𝗶𝗻 𝗣𝗿𝗼𝗷𝗲𝗰𝘁

✓ Requirement Gathering/ Business Requirements

✓ Data Walkthrough

✓ Data Connection

✓ Data Cleaning / Quality Check

✓ Data Modeling

✓ Data Processing

✓ DAX Calculations

✓ Dashboard Lay outing

✓ Charts Development and Formatting

✓ Dashboard / Report Development

✓ Insights Generation

👉𝗕𝘂𝘀𝗶𝗻𝗲𝘀𝘀 𝗥𝗲𝗾𝘂𝗶𝗿𝗲𝗺𝗲𝗻𝘁

𝐊𝐏𝐈'𝐬 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

1. Total Sales: The overall revenue generated from all items sold.

2. Average Sales: The average revenue per sale.

3. Number of Items: The total count of different items sold.

4. Average Rating: The average customer rating for items sold.


𝗖𝗵𝗮𝗿𝘁'𝘀 𝗥𝗲𝗾𝘂𝗶𝗿𝗲𝗺𝗲𝗻𝘁𝘀

 💡 Total Sales by Fat Content:

- Objective: Analyze the impact of fat content on total sales.

- Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.

- Chart Type: Donut Chart.

 💡 Total Sales by Item Type:

- Objective: Identify the performance of different item types in terms of total sales.

- Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.

- Chart Type: Bar Chart.

 💡 Fat Content by Outlet for Total Sales:

- Objective: Compare total sales across different outlets segmented by fat content.

- Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.

- Chart Type: Stacked Bar Chart.

 💡 Total Sales by Outlet Establishment:

- Objective: Evaluate how the age or type of outlet establishment influences total sales.

- Chart Type: Line Chart.

 💡 Sales by Outlet Size:

- Objective: Analyze the correlation between outlet size and total sales.

- Chart Type: Donut/ Pie Chart.

 💡 Sales by Outlet Location:

- Objective: Assess the geographic distribution of sales across different locations.

- Chart Type: Funnel Map.

 💡 All Metrics by Outlet Type:

- Objective: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average Rating) broken down by different outlet types.

- Chart Type: Matrix Card.

👉𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄

This Power BI dashboard provides a comprehensive analysis of BlinkIt's sales performance, customer satisfaction, and inventory distribution. It is designed to help BlinkIt identify key insights and opportunities for optimization using various KPIs and visualizations. The dashboard leverages data from different outlet locations, sizes, and item types to present a detailed view of the business performance.

👉𝗙𝗼𝗹𝗹𝗼𝘄𝗶𝗻𝗴 𝗠𝗲𝗮𝘀𝘂𝗿𝗲𝘀 𝘄𝗲𝗿𝗲 𝗰𝗿𝗲𝗮𝘁𝗲𝗱 𝘂𝘀𝗶𝗻𝗴 𝗗𝗔𝗫

Total Sales = SUM('BlinkIT Grocery Data'[Sales])

Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

No of Items = COUNTROWS('BlinkIT Grocery Data')

Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])

👉𝗣𝗮𝗿𝗮𝗺𝗲𝘁𝗲𝗿𝘀 𝗖𝗿𝗲𝗮𝘁𝗲𝗱

A Field parameter, Metrics was created so that people can use Slicers to see the different outcomes based on Total Sales, Average Sales, Number of Items, Average Rating.

👉𝗗𝗮𝘀𝗵𝗯𝗼𝗮𝗿𝗱 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀

 🔷   𝑺𝒂𝒍𝒆𝒔 𝑷𝒆𝒓𝒇𝒐𝒓𝒎𝒂𝒏𝒄𝒆 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔:
        Total Sales: Displays the overall sales amount.
        
        Average Sales: Shows the average sales.
        
        Number of Items: Indicates the total number of items sold.
        
        Average Rating: Reflects the average customer rating.

 🔷    𝑺𝒂𝒍𝒆𝒔 𝑻𝒓𝒆𝒏𝒅𝒔:
        Outlet Establishment: A line chart displaying the trend of total sales over time, highlighting key milestones and growth periods.

 🔷    𝑺𝒂𝒍𝒆𝒔 𝑩𝒓𝒆𝒂𝒌𝒅𝒐𝒘𝒏:
        Fat Content: Donut chart showing the sales distribution between low fat and regular items.
        
        Item Type: Bar chart illustrating sales performance across various item categories, such as fruits, snacks, household items, and more.
        
        Fat by Outlet: Stacked Bar chart breaking down sales by outlet and fat content.

 🔷    𝑰𝒏𝒗𝒆𝒏𝒕𝒐𝒓𝒚 𝑫𝒊𝒔𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏:
        Outlet Size: Donut chart depicting the distribution of inventory across small, medium, and large outlets.
        
        Outlet Location: Funnel chart showing the sales distribution across different outlet tiers (Tier 1, Tier 2, Tier 3).

 🔷    𝑪𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝑺𝒂𝒕𝒊𝒔𝒇𝒂𝒄𝒕𝒊𝒐𝒏:
        Outlet Type: Table summarizing total sales, number of items, average sales, average rating, and item visibility for different outlet types (e.g., Supermarket Type1, Grocery Store).

👉𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻𝘀

The dashboard includes the following visualizations to present data effectively:

  🔷   Cards for key metrics (Total Sales, Average Sales, Number of Items, Average Rating).
  
  🔷   Line chart for sales trends over time.
  
  🔷   Donut chart for sales distribution by fat content.
  
  🔷   Bar charts for item type performance and sales breakdown by outlet.
  
  🔷   Donut chart for inventory distribution by outlet size.
  
  🔷   Funnel chart for sales distribution by outlet location.
  
  🔷   Table for detailed outlet type performance metrics.
    

👉𝗜𝗻𝘀𝗶𝗴𝗵𝘁𝘀 𝗮𝗻𝗱 𝗢𝗽𝗽𝗼𝗿𝘁𝘂𝗻𝗶𝘁𝗶𝗲𝘀

   𝐇𝐢𝐠𝐡-𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐢𝐧𝐠 𝐎𝐮𝐭𝐥𝐞𝐭: Tier 3 outlets generate the highest sales, suggesting a focus on expanding services in these areas.
   
   𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐒𝐚𝐭𝐢𝐬𝐟𝐚𝐜𝐭𝐢𝐨𝐧 𝐓𝐫𝐞𝐧𝐝𝐬: Customers' average rating was discovered to be 3.9.
   
   𝐈𝐧𝐯𝐞𝐧𝐭𝐨𝐫𝐲 𝐎𝐩𝐭𝐢𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧: Fruits and vegetables, snack food, and household items are top-selling categories, presenting opportunities for targeted marketing and stock optimization.
    
