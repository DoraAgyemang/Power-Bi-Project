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

3. Select any empty area on the report to de-select the text box. Then in the Data pane, expand Products and select the **Category** and **ProductName** field. This step adds a table to the report.

![image](https://github.com/DoraAgyemang/Power-Bi-Project/assets/128803445/2fd99baf-5afc-4148-973e-3fc2655c8949)


   


