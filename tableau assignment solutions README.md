1. Basics:
1.	What is the difference between Discrete and Continuous Data?
Sol) Continuous means forming an unbroken whole, without interruption
When any field is colored green on the Columns shelf it is continuous.
Continuous fields always result in axes. 

Discrete means individually separate and distinct.
When any field is colored blue on the Columns shelf it is discrete.
Discrete fields always result in headers.


2.	What is the criteria for data to land into dimensions and measures?
Sol) Dimension is a discrete field considered as independent variable. Tableau treats any field containing qualitative and categorical information as dimensions.
Measure is a continuous field considered as dependent variable. Tableau treats any field containing numerical information as measures.


3.	What is Metadata, where is it present in the workbook?
Sol) Metadata is the Data that provides information about other data.
The Metadata API enables us to see relationships between the content and asset that you're evaluating with other items on your Tableau Online site or Tableau 
Server. These items include the following: Upstream and downstream content
including data sources, workbooks, sheets, fields, metrics, flows, and owners.


4.	What happens when you aggregate or disaggregate the Data?
Sol) Aggregation function performs mathematical calculation such as Sum, average, count etc. and returns a single value.
If we want to see data at most detailed level we can disaggregate the data, Tableau will display a separate mark for every data value in every row f the data source.


5.	You are working on a dataset, the client adds in more data to the dataset. What happens to the Visualization that
 you had created? Give the explanation for both Live and Extracted data.
Sol) If client adds more data, the visualization remains unchanged for extracted data until you refresh.
Whereas visualization gets updated for live data.


6.	What is the file extensions in Tableau and how each one is different?
Sol) One can save work using several different Tableau specific file types.
The different file extensions in tableau are:
•	Workbooks (.twb) – Tableau workbook files have the .twb file extension. Workbooks hold one or more worksheets, plus zero or more dashboards and stories.
•	Bookmarks (.tbm) – Tableau bookmark files have the .tbm file extension. Bookmarks contain a single worksheet and is an easy way to quickly share your work.
•	Packaged Workbooks (.twbx) – Tableau packaged workbooks have the .twbx file extension. A packaged workbook is a single zip file that contains
a workbook along with any supporting local file data and background images. This format is the best way to package your work for sharing with
others who don’t have access to the original data.
•	Extract (.hyper or .tde) – Depending on the version the extract was created in, Tableau extract files can have either the .hyper or .tde file
extension. Extract files are a local copy of a subset or entire data set that you can use to share data with others, when you need to work offline, and improve performance.
•	Data Source (.tds) – Tableau data source files have the .tds file extension. Data source files are shortcuts for quickly connecting to the original
data that you use often. Data source files do not contain the actual data but rather the information necessary to connect to the actual data as well as
any modifications you've made on top of the actual data such as changing default properties, creating calculated fields, adding groups, and so on.
•	Packaged Data Source (.tdsx) – Tableau packaged data source files have the .tdsx file extension. A packaged data source is a zip file that contains the 
data source file (.tds) described above as well as any local file data such as extract files (.hyper or .tde), text files, Excel files, Access files, and 
local cube files. Use this format to create a single file that you can then share with others who may not have access to the original data stored locally on your computer. 


7.	Create relevant hierarchy and folders for Global Superstore Dataset.
In the worksheet

8.	How can we change the icons and the colour of the dimensions and measures?
Sol) Can’t be changed.


2. Text Table, Highlight Tables, Heat Maps, Tree Map:
1.	Create a text table for the Avg (Sales) for each subcategory using Sample Superstore? List which Sub Category is got Avg (Sale) more than $1000? - Sample Superstore
2.	Create a Heat Table for the order date and Region against the Sub Category based in Count of Sales with two colours diverging that is distinguished by Sum of Profit - Sample Superstore
4.	Create a Highlight table for the States for the Order Date Year whose highlighting is done based on Sum of profits - Sample Superstore
5.	Which customer is having maximum returns of sales in the year 2011? - Global Superstore
6.	How much is profit share less in Pennsylvania when compared to New York? - Sample Superstore
7.	Check for the pane wise percentages with Category, Sub- Category and quarter wise order date, also check for the Row wise grand totals and Column wise grand totals. - Sample Superstore

3. Filled Maps, Symbol Maps:
1.	Use Global Superstore. Check Which Western Country in EMEA region has least profit percentage.
2.	Use “Sample Superstore. Xls”, which state shares boarders only profit for tables
3.	Use “Sample Superstore. Xls”, which state has no data for Profits for Office Supplies

4. Bar Charts, Stacked, Side by Side:
1.	Which Customer name & Year is having all the Product Categories sum of profit less than over-all Average profit? - Sample Superstore
2.	What is the Maximum of Life Expectancy Female for the region Africa & year 2012? - World Indicators
3.	What is the share of the top 20 customers based on the sales amount compared to the customers based on profit amounts - Sample Superstore


5. Line Graphs, Dual Line, dual axis:
1.	How can you show two different graphs in one view? - Global Superstore
2.	Which Region is having Average of Energy Usage>1000000 and average of Population 65+>10? - World Indicators


6. Trendlines, Cluster, scatter Plot, boxplot, Word Cloud (Packed Bubbles), Histogram:
1.	Draw a trend line for profit as a linear function of sales only for product technology? - Sample Superstore
2.	Create a histogram showing the number of Sales using Sales Bins of $1000. Which bins have profit ratios (profit as a percentage of sales) of more than25%? - Global Superstore
3.	Using “Sample Superstore”, use order sheet create a histogram showing the number of orders using sales bins of $1000. Which bin has the highest Customer?
4.	Using “Global Superstore”, use the orders sheet, build a scatter plot showing the sum of sales on the x-axis and sum of profits on the y axis for all products (Product name). What is the equation for linear regression for products in Technology?
5.	Use “World Indicators”.  Take Health Exp% GDP, Health Exp/Capita, Life Expectancy Male, Female. What are the variables that are considered to create the clusters by default?

7. Calculate Fields, Quick table calculations, LOD:
1.	How do you create a profit ratio using the Calculated fields?
2.	Global Superstore data set; Region wise year wise sales are ranked. What is the rank of some country when compared to last year?
3.	What percent of total profits do the top 10 customers by Sales represent? - Sample Superstore 
4.	Find the customer with the lowest overall profit. What is his/her profit ratio? - Sample Superstore
5.	The rank of the Machine subcategory is “4” in the Central region, is the subcategory rank is increased, decreased or remaining the same in West region.
6.	Ranking States based on Sales what is the rank of coastal state which has sales crossed $20000. - Sample Superstore
7.	What is the percent of orders which took more than 7 days on an average to deliver.
8.	Use “World Indicators”. Without using table calculations what is the proper syntax to build a calculated field which will display overall total GDP on this view?



8. Filters:
1.	What are the different types of filters and give their working order?
Sol) There are basically 6 types of filter:
Extract filter
Data source filter
Context filter
Dimension filter
Measure filter
Table Calculation filter.
2.	Create a list of Top 10 Products based on Profits whose sale value is more than $5000? - Global Superstore
3.	Create a Chart with Customer Name and Profit and check for the Sale Value for top 15 Customers? - Global Superstore
4.	Apply filter to all the worksheet, filter by year 2011, then find the sum(sales) for the highest subcategory.- Global Superstore
5.	What is the name of 375th top most customer by sum of profits - Sample Superstore
6.	What are the various Forecast length that Tableau cannot recognizes?
Sol) Tableau cannot recognize forecast length like year, quarter, month, week, days, hour, minute, second greater than 99.



9. Dashboards & story:
1.	What are the different device type preview that Dashboards can use?
Sol) The different device type preview that Dashboards can use are:
Desktop
Laptop
Phone.

2.	Create a dashboard using World Indicators showing the all the Actions that can be performed in Tableau.


10. Time Series:
1.	Use Order date and drill down the information for Quarter and Month level separately and show the line Chart in a Continuous Form- Global Superstore


11. Sets, Parameters, Groups:
1.	Parameters can be used in?
Sol) Parameters can be used from filter shelf. They can be used in reference lines, sets, calculated field.
2.	What are the different ways to create a Parameter?
Sol) Different ways to create a parameter are:
1)	In the data pane, click the drop down arrow in the upper right corner and select create parameter. In that dialog box enter the values.
2)	Can be created from filters.
3)	Can be created from set.


12. Forecast:
1.	You are provided with the dataset for the past 10yrs. How can you forecast the data for next 4 years, Quarter wise.
2.	Use “Sample Superstore”. What is the Sales Forecast Estimate for the month of September 2018?

13. Pie Chart:
1.	Create a Pie Chart using regions and sum of sales, sort the pie in ascending order, increase the size in the view and label them with Count of Quantity
2.	 and Sum of Profits- Sample superstore
