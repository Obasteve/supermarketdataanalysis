# supermarketdataanalysis
Project Title Here
Analyze Supermarket Data Across the Country - Company XYZ.
Company XYZ has a supermarket in the major cities across the county, these are Lagos, Abuja and Port-Harcourt. This is to analyse the sales activites and records for 3 months. 

Project Steps
Step 1 - Loading the Dataset
We import the data set for the sales records in the three cities by importing our libraries for that fuctions, after which we combine the the three data sets that were already in a csv files. After combining them together as a single data set. using the concat function, we then export it and rename it so that we can start our analysis proper


Step 2 - Data Exploration
 -I import all our libraries for this purpose, then I import the newly merged data set named "newlist" using pd.read_csv. 
 
 -The head() method was used  to view first few rows of the dataset. I then checked the number of rows and columns using the shape attribute.
 -The columns in our newlist data set were all generated. After which I carried out the statistical summary using the decribe attribute.
 -The data frame infomation was carried out to assertain the indext types, column types and the non-null values, I  also check for missing data using the isnul and notna method


Step 3 - Dealing with DateTime Features
-I use the to_datetime() method to convert the dat and time to an appropriate data type. Year,month day, hr and minute colmun were also extracted and used as new column from the datetime. 
After that is done, use the type attribute to confirm the datatype.
-The unique column was also generated using the nunique() attribute.

Step 4 - Unique Values in Columns
The unique values for most of the columns was generated. The aa['column'].unique().tolist()
attribute was used to obtain the unique columns.The value_counts() function was also used for unique values.


Step 5 - Aggregration with GroupBy
A groupby object with the "City Column", and aggregation function of sum and mean was created, it was used to display a table that shows the gross income of each city, and determine the city with the highest total gross income.
and other columns such as "Unit Price", "Quantity" etc. 

Step 6 - Data Visualization

-Using countplot, I determined the branch with the highest sales record. -I Explore a countplot for the Payment and City Column
-I also determine the highest & lowest sold product line, using the groupyby.
-I also determine the Payment channel used by most customer to pay for each product line. 
- Determine the Payment channel for each branch.
- I also Determine the branch with the lowest rating. This you can determine using abox plot which gives a statistical summary of the plotted features, and you can pick out the branch with the lowest rating from the plot
- I used catplot to determine the gender types that come to purchase each product line.

Insights
- Home and lifestyle recorded the highest volume of sales.
- I discovered that PortHacourt City has the higest sales and most people buy electronic appliances, food and beverages. 
- In payment, most of the mode of payment was done by cash.
- The visualization also showed that the women gender has the highest customer mode.

Future Work
-I think the time of sales will be analyse in my future work to ascertain the peak time customers come in to the supermarket to buy stuffs.

Standout Section
Using swarmplot, it was evident that most of the gross income was around N2500

Executive Summary.
This is an analysis to determine the sales and trasanctions activities over the space of 3 months of company XYZ in the 3 major citis of Nigeria. The analysis have shown how gender influnces sales of some consumables 
and the mode of payment of customers admist many others contained in the analysis.