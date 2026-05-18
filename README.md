1.Project Title:

Mumbai Restaurant Analysis & Customer Preferences

2.Ask  Phase

1.In which area/region of Mumbai  are the majority of the restaurants  located?

2.Which Cuisine Categories are  most expensive, and which ones is pocket- friendly/budget friendly?

3.Are  the expensive Cuisine categories strictly concentrated  in posh areas or they distributed across all locations?

3.Prepare and Process phase:

Data Source:
*This dataset contains restaurant insights from  Zomato Mumbai ,which is successfully s
Sourced and downloaded from Kaggle.

Data Type:
The feature within this dataset consist of qualitative and quantitative text/String(such as Name,Cuisine Category,Region) and quantitative numeric data (such as Price),etc

4.Cleaning Steps Performed:

1.Delimited Data Parsing:
Originally,the raw ingestion had data completely combined into a single column structured with pipe delimiters(|).The Text to Columns feature was utilized to parse and split the text into distinct relational columns.

2.Removal of Repeating Headers:

The source file contained structural anomalies where column headers recursively repeated after every few rows.An Excel Data Filter was applied to systematically isolate,select and delete these duplicate header rows simultaneously .

3.Handling Missing Values:
Performed data profiling to successfully identify all structural blank cells and missing records within the CITY and REGION columns.

5.Analyze Phase:
Question 1.Answer:The area with highest concentration of restaurants is Mira road with 173 listings ,followed closely  by  Vasai  with 115 listings.This implies high market saturation and intense competition in these local food hubs.

Question 2 Answer:Based on the data analysis.French Cuisine is the most expensive in Mumbai with a premium average price of 2100 for two people,followed closely by Brazilian Cuisine(1900),.Conversely cuisine like paan(143.84) or Tea (164.28) are the most pocket-friendly.

Question 3 Answer:
Yes,the data confirms that expensive and luxury cuisines are strictly concentrated in affluent/post areas of Mumbai.For example high-end categories like European and Modern Indian are Heavily located in premium commercial and upscale residential hubs such as Bandra Kurla Complex(BKC),Juhu,Worli and Bandra West.They are rarely found in budget-conscious or far-off residential suburbs.


6.Business Insight:
For any new restaurant launch,premium menu pricing must directly align with the income levels of that specific area.Opening a luxury cuisine restaurant in a non-affluent location carries a very high financial risk due to a lack of target audience.

7.Act Phase(Data-Driven Recommendations) 
Based on the analysis and insights,here are the strategic recommendations for stakeholders looking to open or scale a restaurant business in Mumbai:
1.Strategic Location Targeting:
Avoid opening  a standard/casual dining restaurant in high-saturation zones like Andheri West unless backed by highly unique theme or  cuisine.Instead explore emerging or slightly lower-density commercial hubs to save on high real estate costs.
2.Pricing and Demographic Alignment:
Strictly align the menu pricing with the target region’s purchasing power.Premium international cuisine (e,g,European) should only be launched in affluent clusters like Bandra West,BKC,or Juhu to ensure a market-demographic fit.
3.Volume vs Margin Play:
 Investors looking for quick,high-volume transactions with low overhead costs should focus on micro-segments like high-end cafes,beverages or quick-bites.Conversely,fine dining format like French or Brazilian must focus on luxury experience branding to justify their premium margins.
