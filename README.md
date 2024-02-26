# Power-Bi-Project

### Overview
This project seeks to analyse the sales of various products of a company in the United States and also the revenue for each product.

### Import Data
1. Open Power BI Desktop. The application interface should look similar to this:
   
![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/e9fb3506-d23e-42c1-9068-c7cc7eab6880)

2. On the Power BI Desktop welcome screen, select **Get data**, and then in the list of data sources, select **Web** and then select **Connect**.
 
![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/2dcce161-af91-4294-a96b-a176723766f6)

3. In the From web dialog box, enter your URL and then select **OK**:
   
![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/51c233a8-3aa1-46a1-95f3-8dc7a2bfbbd3)

4. Select **Load** to load the data into the data model for your report.
   
![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/f830a85d-9812-4006-8c29-b2c366f540ee)

Do same for any other data you will like to import from the web for visualisation and analysis.

### Eploring the data model
1. In Power BI Desktop, on the left-side edge, select the **Model tab**, and then arrange the tables in the model so you can see them. You can hide the panes on the right 
   side by using the » icons:

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/731d4944-c111-4509-b8d3-993aca1a8d5b)

2. In the orders table, select the Revenue field and then in the Properties pane, set its Format property to Currency. This step will ensure that revenue values are 
   displayed as currency in report visualizations.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/86da68e2-a127-4187-a333-3730a92bdb44)

3. On the left-side edge, select the **Data view**tab, and then in the **Data** pane, select the **customers**table.
4. Select the **City** column header, and then set its **Data Category** property to **City**:

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/1b0565c9-5ffb-4789-91fd-ffa7bc6dfa29)

This step will ensure that the values in this column are interpreted as city names, which can be useful if you intend to include map visualizations.

### creating a report
1. On the **File** menu, select **Options and Settings**. Then select **Options**, and in the **Security** section, ensure that **Use Map and Filled Map** visuals is 
   enabled and select **OK**.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/de82ed0c-30fe-4102-a3ff-a018ed3fbfdc)

This setting ensures that you can include map visualizations in reports.

2. In the ribbon, select **Text Box** and add a text box containing the text **Sales Report** to the report. Format the text to make it **bold** with a font size of **32**.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/591b6faf-3bff-417a-ad0d-7a2586b81e18)

3. Select any empty area on the report to de-select the text box. Then in the Data pane, expand Products and select the **Category** and **ProductName** field. This step 
   adds a table to the report.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/2fd99baf-5afc-4148-973e-3fc2655c8949)

4. With the table still selected, in the **Data** pane, expand **Orders** and select **Revenue**. A Revenue column is added to the table. You may need to expand the size 
   of the table to see it.

The revenue is formatted as currency, as you specified in the model. However, you didn’t specify the number of decimal places, so the values include fractional amounts. It won’t matter for the visualizations you are going to create, but you could go back to the **Model** or**Data** tab and change the decimal places if you wish.
   
![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/f1a5e6e7-990b-4057-bf05-927eda2b569a)

5.![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/196216b0-4a1e-481e-a19c-746614a76300)

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/fa5a25d4-6f8b-4406-82eb-1381dd7068f4)

6. Select a blank area of the report, and then in the **Data pane**, select the **Quantity** field in the **orders** table and the **Category** field in the **products** table. This step results in another column chart showing sales quantity by product category.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/6bb9a4f4-39b0-416c-a220-ac7121f87d15)

7. With the new column chart selected, in the Visualizations pane, select Pie chart and then resize the chart and position it next to the revenue by category column chart.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/c946cf84-702a-490f-8218-0cc5d9069ba8)

Select a blank area of the report, and then in the **Data pane**, select the**City** field in the **customers** table and then select the **Revenue** field in the **orders** table. This results in a map showing sales revenue by city. Rearrange and resize the visualizations as needed:

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/ba22451e-8028-4918-a472-a71920b53d56)
