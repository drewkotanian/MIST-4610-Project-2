# MIST-4610-Project-2

# Team Name:
Team Query Wizards

# Team Members:
1. Conner MacDonald [@cmacdonald32](https://github.com/cmacdonald32)
2. Drew Kotanian [@drewkotanian](https://github.com/drewkotanian)
3. Luke Mulert [@lukemulert03](https://github.com/lukemulert03)
4. Patrick Gray [@pfg52386](https://github.com/pfg52386)

# Description of Dataset:
Our dataset digs into Connecticut's real estate scene from 2001 to 2020, pulling insights from the Office of Policy and Management's records. It's a snapshot of property transactions, covering key details like listing years, sale values, and property types. Each entry has a unique serial number, making it easy to track. The listing year gives a timeline, and the recorded date tells us when deals went down. Town and address details add a sense of place, letting us explore real estate changes across Connecticut. Financial info, like assessed and sale values, tells us about property worth and actual sale prices. The sale ratio gives a hint about how property values stack up. Categories like property type and residential type help break down the data, offering a closer look at different real estate segments. In a nutshell, our dataset is a window into Connecticut's real estate story. It's not just numbers; it's a tool for exploring the ups and downs, trends, and stories behind property transactions in the state.

# Question 1:
Question: We are interested to find out, on average, which towns have the highest real estate sale price? For these towns, what is the max sale amount? Note: We have filtered the average sales results to only display towns in Connecticut with an average over a million dollars.

Importance:
This question is interesting because it helps us understand which towns in Connecticut have the highest mean household price. This data is able to open doors for more potential questions from buyers, given that higher household prices indicate wealthier areas, lower crime, and often better school systems. This can give developers and realtors in the area a better idea of how to value new homes, given that a sale can be hard if it is too far above competitors' average price. The second part of the question gives us an idea about what type of residential homes are most common out of these higher priced areas. This can show us how different residential types can affect the price of a home or apartment paired with it's location.

![PNG image](https://github.com/drewkotanian/MIST-4610-Project-2/assets/148258205/0c31dcef-ed76-4090-b578-54ff3ccbeb00)
Our first graph illustrates the highest average real estate sale in respective Connecticut towns. Initially, we included every town and the individual sales that occurred in each town. However, we quickly discovered that due to the large amount of towns in the data set, the graph was difficult to follow. Therefore, to illustrate our data in a more efficient manner, we filtered our town results to show towns in Connecticut with an average sale of over one million dollars. In our next visualization, we further analyze the same data.

![PNG image](https://github.com/drewkotanian/MIST-4610-Project-2/assets/148258205/0ff50c5b-2f6e-4ddd-907c-316b401917fd)
As we further visualize this data, we wanted to dive deeper into the sales statistics of the 5 towns with the highest average. As a result, we created a table displaying the highest individual sale in each of the towns. This helps give us insight on why the average sale for these towns is so high. With some additional outside research, it is interesting to note that each of these towns displayed are within 150 miles of New York City, which is a significant factor to higher real estate prices.

# Question 2:
Question: For real estate sales with a sales ratio greater than one, what is the most common property type and town of the estate?

Importance:
Answering this question is crucial for two main reasons. First, when real estate sales have a sale ratio greater than one, it means the property is sold for less than its assessed value. This is not good because it indicates potential unfairness in how properties are valued for taxes. By figuring out the common property types and towns with this kind of sale ratio, we can spot areas where property values might be unfairly high. This discovery prompts further investigation and possible adjustments to make things fairer. Second, looking into this information helps us understand how competitive different areas are in the real estate market. If certain property types and towns consistently have sale ratios greater than one, it suggests that sellers might need to lower their prices. This could create opportunities for buyers to negotiate better deals. Knowing this gives people in the market a better idea of how to make smart decisions based on what's really happening. In summary, tackling this question is about finding out if properties are valued fairly and understanding where good opportunities might be for buyers and sellers in the real estate game.

<img width="1410" alt="PNG image" src="https://github.com/drewkotanian/MIST-4610-Project-2/assets/148258205/d1aff5f1-618c-4419-aef9-91832439fc70">
Our first graph for Question 2 illustrates the count of Towns with a sales ratio greater than one. From this graph, we can conclude that the towns of Bridgeport, Stamford, and Waterbury have the highest amount of properties with a sales ratio greater than 1 and are selling for less than their original appraisal price. Bridgeport has 18,264 properties selling for less than the appraised value, Stamford has 17,374 and Waterbury has 17,938 selling for less than the assessed value. Comparing these towns to some of the more expensive Towns from our graphs in Question 1, you can see that towns such as Darien and Willington are not even on this graph because they do not have a single property that sold for less than its appraised value. 

<img width="1415" alt="PNG image" src="https://github.com/drewkotanian/MIST-4610-Project-2/assets/148258205/7e9cf28c-3857-45d1-8364-8144548ae272">
Our second graph for question 2 illustrates the most common property types that have a sales ratio greater than 1 (sold for less than their appraised value). We decided to use a treemap because it is very easy to visualize the most common property types. We conclude that property types "Two Family", and "Three Family" are the most common property types that sold for less than their appraised value. "Two Family" with 26,408 and "Three Family" with 12,586. This gives us insight as to what property types tend to be the most profitable / least profitable.


#  Manipulations applied to the data set for analysis:
In leveraging Tableau to analyze the CT real estate scene from 2001 to 2020 dataset, we strategically manipulated the Excel file by incorporating essential functions. Employing the SUM function allowed us to accumulate numerical values, providing a comprehensive overview of the cumulative real estate metrics over the specified timeframe. Additionally, the COUNT function played a pivotal role in generating our insightful graphs, enabling us to visualize key trends and patterns within the Connecticut real estate market, thereby enhancing the our interpretability of the data.


# Tableau packaged workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.


