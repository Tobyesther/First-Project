![image](https://github.com/Tobyesther/First-Project/assets/140488645/9c94ffe4-b3b0-4f66-be96-aa741ff6ef15)**TASK 1**

This task is titled 3rd data Analysis Cohort, assigned by Promise Chinonso.

**INTRODUCTION**

In this first task, we were asked to create a table of information, consisting of 20 rows and 5 columns which should include the following information: Employee ID, Employee Full Name, Department, Salary and Job Type.

**ACTIVITY**

We were asked to show/highlight the employees who are working as 'Freelancers' and earning above $10,000.
Split the emloyees full names into first names and last names, highlighting any form of duplicate value in the table.
Highlight employees whose names start with E in yellow color, and highlight the highest salary value in green and the lowest salary value in red.

**RAW DATA**

![image](https://github.com/Tobyesther/First-Project/assets/140488645/76383531-38c6-4529-8ecd-4283db37f242)
----

**SKILLS AND FUNCTIONS DEMONSTRATED**

Data Manipulation, Use of Conditional Formatting, Use of Filters and Text-to-Column.
------

For the first activity, the filter function was used across the headers in each column by pressing Ctrl + Shift + L. Then, on the job type column, the data was filtered to show just employees working as freelancers.
After this, the Salary column was highlighted and conditional formatting function was applied by choosing the rule that only highlight cells that are greater than $10,000 in red color.

![image](https://github.com/Tobyesther/First-Project/assets/140488645/2b985cd0-17bc-4e22-95e7-28f8200d5e43)
-----

The Second activity depicts how the the full name of each employee was split into first and last names in different columns. To achieve this, an extra column was inserted just after the Job type column, then clicking on 'data'tab , the text-to-column function was used specifying space as the delimiter between the names. The conditional fomatting function was also used here to highlight duplicate data in the Employee ID and Full Name column.

![image](https://github.com/Tobyesther/First-Project/assets/140488645/640e8c0a-420d-412d-b4d8-644330c96ddf)
-----

The last activity shows the highlighted cells whose names begins with 'E' in yellow color in the Full name column. This was done by highlighting the full name column and then applying the conditional formtting function to highlight cells with 'E' as the first letter in Yellow color. This same function was applied to the salary column to indicate the highest and lowest value in green and red color respectively.

![image](https://github.com/Tobyesther/First-Project/assets/140488645/8b7dc4d2-6d5b-467d-a47c-38c09bf51712)
------

**CONCLUSION**

Overall, the task was fun, as i was able to explore different functions and see the effect of these functions on the data and how they give data a new meaning in terms of interpretation.



**TASK 2**

This task depicts an already prepared Sales data containing 700 rows and 12 columns of data. The columns consists of a segment,Country, Product, Discount Band, Units Sold, Manufacturing Price, Sales Price, Gross Sales, Discount, Sales, Profit, Month Column respectively.

**ACTIVITY**

The questions given were:
>Using the same Sales Data, determine the following
>The total Revenue and Profit generated
>The average Revenue and Units Sold for every order
>The total Discount given in $
>Total number of sales recorded
>The highest Profit generated
>Create a column named ‘Sales Range’, return ‘High Sales’ if the Sales value is above average, otherwise, return ‘Low Sales’.

**SKILLS AND FUNCTIONS DEMONSTRATED**

> SUM FUNCTION
> AVERAGE FUNCTION
> COUNT
> IF FUNCTION
> MAX FUNCTION

**RAW DATA**

![image](https://github.com/Tobyesther/First-Project/assets/140488645/423759bb-ed8c-49df-84ec-bdab666af0e4)
------

>The Total Revenue and Profit generated was calculated using the 'SUM' function, i.e =SUM(J2:J701) and =SUM(K2:K701) respectively.
>The Average Revenue and Units Sold for every order was calculated using the 'AVERAGE function, i.e =AVERAGE(J2:J701) and =AVERAGE(E2:E701).
>The total discount was also calculated using the 'SUM' function i'e, =SUM(I2:I701)
>The total number of sales was generated using the 'COUNT' function, i,e, =COUNT(J2:J701)
>The highest Profit generated was calculated using the 'MAX' function, i.e, =MAX(K2:K701)
>The last activity for this set of question was gotten by creating a column named 'Sales Range' to indicate if the values in each cell in the sales column was 'high sales or low sales' by calculating the average of the sales column using =AVERAGE(J2:J701). Ater calculating the average, the 'IF' function was used to determine if each value would be categorized as 'High sales' or 'Low sales'. Using the function =IF(J2:J701>P12,"High Sales","Low Sales"), P12 indicating the cell where the average value is.

![image](https://github.com/Tobyesther/First-Project/assets/140488645/7d799118-2403-446d-9a50-91011582831b)
-------

**TASK 3**

**ACTIVITY**

Using the same Sales data set, another set of questions were given to calculate;
Calculate:
>The average revenue generated from each sale of ‘Paseo’
>The number of sales made in the Government and Midmarket segment
>The total revenue generated from the sales of ‘Montana’ in Canada
>In which Country, Segment and Month was the highest unit of goods sold?
>What is the total profit made in December?

**SKILLS AND FUNCTIONS DEMONSTRATED**

>SUMIFS
>COUNTIFS
>AVERAGEIFS
>MAX
>VLOOKUP

>The first question was calculated using the 'AVERAGEIF' function, i.e, =AVERAGEIF(A2:A701,"Paseo",H2:H701).
>The number of sales made in the government and midmarket segment was calculated separately using the 'COUNTIF' function, i.e, =COUNTIF(K2:K701,"Government") and =COUNTIF(K2:K701,"Midmarket") and the values gotten were added to get the final value.
>The total revenue generated from the sales of montana in Canada was gotten using the 'SUMIFS' function, i.e, =SUMIFS(H2:H701,L2:L701,"Canada",A2:A701,"Montana").
>To Calculate the country, segment and month with the highest unit of goods sold, the 'VLOOKUP' function was employed. To calculate this, the highest unit of goods sold was generated using the 'MAX' function, i.e, =MAX(C2:C701),then the country, segment and month was calculated using =VLOOKUP(N6,C:L,10,FALSE), =VLOOKUP(N6,C:K,9,FALSE), and =VLOOKUP(N6,C:J,8,FALSE), where C:L, C:K and C:K are the columns containing the country, segment and month respectively.
>The total profit made in December was calculated using the 'SUMIF' function, i.e, =SUMIF(J2:J701,"December",I2:I701).

![image](https://github.com/Tobyesther/First-Project/assets/140488645/f6dc9cd4-0ef4-408b-a84e-2a350b0a5fa5)
------

**CONCLUSION**

It was a positively challenging task, as it requires you to think carefully and observe the questions and their respective functions closely.




