# Sales-Data-Task
The projects contained in this repository are assignments from the second and third lessons on data analysis with Promise Chinonso
# Introduction
This task was assigned in a bid to explore various spreadsheet functions and formulas to on a Sales Data containg 700 rows of information and 12 columns of data. The attributes of this data are Segment, Country, Product, Discount, Units Sold, Manufacturing Price, Sales Price, Gross Sales, Month, Profit and Sales. Working with this dataset has helped me to better understand knowing when and how to apply different types of spreadsheet formulas and functions as well as formatting data. See the sample dataset in the following subject file.
# Sample Dataset
![Screenshot (5)](https://github.com/dianeanalyst/Sales-Data-Task/assets/120665115/96b7bf6d-6219-4b1f-99be-edd24db32c71)

# Task Activity
# 1
The total Revenue and Profit generated: This was calculated with the use of the SUM() function for each parameters.
# 2
The Average Revenue and Units Sold for every order: Here, I made use of the AVERAGE() function for each of the parameters.
# 3
The total discount given in $: In this case, I once again made use of the SUM() functions to get the total of the entries in the 'Discount' column and thereafter, formatted the result into dollar currency data type.
# 4
Total Number of Sales recorded:  At this stage, I determined the total number of sales made by the company by using the COUNT() funtion on the Sales column.
# 5
Highest Profit generated: The MAX() function was used to determine the highest profit generated in the company.
# 6
Next on the task activity list was to create a column named 'Sales Range' to return 'High Sales' or 'Low Sales' if the corresponding Sales value was more than average sales or not. Here, I started by calculating the average sales by using AVERAGE(J2:J701). Furthermore, created the column 'Sales Range' using the function =IF(J2>$V$6,"High Sales","Low Sales") and then flash-fill to populate each row of the data. The file below, shows the resulting values for task 1-6.

![Screenshot (6)](https://github.com/dianeanalyst/Sales-Data-Task/assets/120665115/617b29a9-009a-4a7d-bb9a-4c4642def282)

# Introduction to Task 3
Task 3 can be best described as a build up on task 2 as it is a continuation of using formulas and functions to solve data related problems.
# Task Activity
# 1
Average Revenue generated from each sale of Paseo: This prompted me to untilize the AVERAGEIF() funtion in the following format =AVERAGEIF(C2:C701,"Paseo",H2:H701)
# 2
The number of sales made in the 'Government' and 'Midmarket' segments: I determined this separately by using =COUNTIF(A2:A701, "Government") and =COUNTIF(A2:A701, "Midmarket") respectively.
# 3
The total revenue generated from the sales of Montana in Canada: Because the SUMIF() function is perfect for summing various conditional parameters, this was used to determine that the total revenue for the given conditions sums up to 2,982,114.5 dollars.
# 4
The VLOOKUP function as we were thoroughly taught was understood to be perfect in determining what country, month and segment was the highest unit of goods sold. I employed it in the format as shown here. =VLOOKUP(R15,E2:O701,11,FALSE) =VLOOKUP(R15,E2:N701,10,FALSE) =VLOOKUP(R15,E2:L701,8,FALSE) for country, segment, and month accordingly.
# 5
Using the SUMIF() function again, the total profit made in december was also determined. The file below shows the entire tasks results in task 3.

![Screenshot (7)](https://github.com/dianeanalyst/Sales-Data-Task/assets/120665115/e7a2e28d-cfc9-40b3-b547-94351d59d2c5)

# Conclusion
The use of Excel functions is necessary for accuracy and ease when working with data. Being able to know which to apply as at when needed is as well very important. Spreadsheet has continually been proven to be useful in many aspects than many know it to be.
