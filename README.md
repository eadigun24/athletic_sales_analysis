# athletic_sales_analysis
## challenge Notes
* The main requirements for this challenge was from the module challenge details in bootcamp.
* Section 1:
    * This involved reading in the two csv files into separate dataframes.
    * Displaying the results of loading the data successfully into separate dataframes.
    * Checking the datatypes of the dataframes.
    * Combining both dataframes into a singular dataframe.
    * Column datatype redifining from an object to datetime datatype.
* Section 2:
    * Creating a groupby for products sold by region, state and city.
        * Created a custom sum function; which just returns the sum of the items.
        * The reasoning for this is in the future, if modifications are required for the summation
        * logic; we'd be fully abstracted and flexible to do so.
        * Sorted the values of the grouby in descending order.
    * Created a pivot table for the same indexes as above.
        * Created a custom sum function with the same reasoning as above.
        * Renamed the values column as specified.
        * Sorted the values of the pivot table in descending order.
* Section 3:
    * Same as in Section 2, with different parameter in the values field.
* Section 4: 
    * This section added an additional value in the index values for both the groupby and pivot table.
* Section 5:
    * In this section, I'm filtering the combined sales dataframe to determine which retailer sold the most women's athletic footwear.
    * Thereby, allowing me use the groupby and pivot table functions to further analyze the data.
* Section 6 and 7:
    * Binned the data by days and weeks.
    * Applied sorting to the resulting data (in descending order).