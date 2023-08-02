# Power-BI-Marketing-Insights
1. What marketing campaign(s) had the highest ROI, Return of Ad Spends(RoAS)? Provide visualizations to support your answer.
-	RoAS and ConversionRate columns are created using DAX function:
-	RoAS = DIVIDE(SUM('amazon_marketing_stream_data '[attributed_sales_7d]), SUM('amazon_marketing_stream_data '[cost]), 0) is the DAX formula.

2. How does the sales performance vary across different product categories? Present your findings in a suitable chart.
=Product mattress has the most attributed sales.

3. How does each campaign behave and each item behave hourly?
=Bar chart for  sales vs Product and category is created over time two different bar charts for comparision.

4. Is there any correlation between the timing of marketing campaigns and changes in product sales?
=The relationship between Time and Sales is evident as we observe a noticeable pattern: sales tend to be higher at the beginning of the campaign and gradually decrease towards the end of the day.

5. What is the overall trend of sales before, during, and after each marketing campaign? Are there any significant spikes or dips in sales?
= n/a

6. How can the marketing strategies be optimized to improve overall sales and customer engagement?
=The correlation between Customer Engagements, Total Clicks, and Impressions is clear. To enhance customer engagement and optimize the platform, it is essential to create an appealing user interface. A well-designed interface attracts users, leading to increased engagements and ultimately boosting sales.

7. Which products have shown the highest growth in sales during the campaign period? Are there any products that performed poorly during campaigns?
=n/a

8. A sudden change in the dataset format occurs, making it incompatible with the existing Power BI model. 
How would you handle this situation while maintaining progress on the dashboard creation?
=To update the data source path in Power BI to the new folder, follow these steps:

1. Open Power BI and open the report or data model that requires the data source path update.
2. Click on "File" in the top-left corner of the window.
3. Select "Options and settings" from the menu.
4. In the options dialog box, choose "Data source settings" from the left-hand side menu.
5. Locate the data source that needs to be updated in the list of connections.
6. Click on "Change Source" for the relevant data source.
7. A new dialog box will appear. Here, you can copy the new folder's data source path.
8. Paste the new folder's data source path into the dialog box and click "OK" to confirm the changes.

By following these steps, you will successfully update the data source path to the new folder in Power BI, allowing your report or data model to access the updated data.
