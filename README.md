Excel-19

Project Description

Excel-19 is a comprehensive guide to What-If Analysis in Microsoft Excel. Here you'll find practical tips, concise explanations, and illustrated examples for creating scenarios, Goal Seek, Data Tables and learn how to solve Quadratic Equation.

Table of Contents

What-If Analysis

What-If Analysis in Excel allows you to try out different values (scenarios) for formulas.

Assume you own a book store and have 100 books in storage. You sell a certain % for the highest price of $50 and a certain % for the lower price of $20.

![screenshot](Screenshots/What1.png)

If you sell 60% for the highest price, cell D10 calculates a total profit of 60 * $50 + 40 * $20 = $3800.

Different Scenarios

But what if you sell 70% for the highest price? And what if you sell 80%, 90% or even 100% for the highest price? Each different percentage is a different scenario. You can use the Scenario Manager to create these scenarios.

1. On the Data tab, in the Forecast group, click What-If Analysis.

![screenshot](Screenshots/What2.png)

2. Click Scenario Manager.
3. Add a scenario by clicking on Add.
4. Type a name (60% highest), select cell C4 (% sold for the highest price) for the Changing cells and click on OK.

![screenshot](Screenshots/What3.png)

5. Enter the corresponding value 0.6 and click on OK again.

![screenshot](Screenshots/What4.png)

6. Next, add 4 other scenarios (70%, 80%, 90% and 100%).

Your Scenario Manager should look like this:

![screenshot](Screenshots/What5.png)

(Note: to see the result of a scenario, select the scenario and click on the Show button. Excel will change the value of cell C4 accordingly for you to see the corresponding result on the sheet.)

Scenario Summary

To easily compare the results of these scenarios, execute the following steps.

1. Click the Summary button in the Scenario Manager.
2. Next, select cell D10 (total profit) for the result cell and click on OK.

![screenshot](Screenshots/What6.png)

Result:

![screenshot](Screenshots/What7.png)

Goal Seek

You can use Excel's Goal Seek feature to find how many books you need to sell for the highest price, to obtain a total profit of exactly $4700.

1. On the Data tab, in the Forecast group, click What-If Analysis.
2. Click Goal Seek.

![screenshot](Screenshots/Goal1.png)

3. Select cell D10.
4. Click in the 'To value' box and type 4700.
5. Click in the 'By changing cell' box and select cell C4.
6. Click OK.

![screenshot](Screenshots/Goal2.png)

Result: 

![screenshot](Screenshots/Goal3.png)

Data Tables

Instead of creating different scenarios, you can create a data table to quickly try out different values for formulas. You can create a one variable data table or a two variable data table.

1. Select cell B12 and type =D10 (refer to the total profit cell).
2. Type the different percentages in column A.
3. Select the range A12:B17.
4. On the Data tab, in the Forecast group, click What-If Analysis.
5. Click Data Table.

![screenshot](Screenshots/Data1.png)

6. Click in the 'Column input cell' box (the percentages are in a column) and select cell C4.

![screenshot](Screenshots/Data2.png)

(Note: this is a one variable data table so we leave the Row input cell blank.)

7. Click OK.

Result:

![screenshot](Screenshots/Data3.png)

Two Variable Data Table

1. Select cell A12 and type =D10 (refer to the total profit cell).
2. Type the different unit profits (highest price) in row 12.
3. Type the different percentages in column A.
4. Select the range A12:D17.
5. On the Data tab, in the Forecast group, click What-If Analysis.
6. Click Data Table.
7. Click in the 'Row input cell' box (the unit profits are in a row) and select cell D7.
8. Click in the 'Column input cell' box (the percentages are in a column) and select cell C4.

![screenshot](Screenshots/Data4.png)

9. Click OK.

Result:

![screenshot](Screenshots/Data5.png)

Goal Seek example

Use Goal Seek in Excel to find the grade on the fourth exam that produces a final grade of 70.

1. The formula in cell B7 calculates the final grade.

![screenshot](Screenshots/Goal4.png)

2. The grade on the fourth exam in cell B5 is the input cell.
3. On the Data tab, in the Forecast group, click What-If Analysis.
4. Click Goal Seek.
5. Select cell B7.
6. Click in the 'To value' box and type 70.
7. Click in the 'By changing cell' box and select cell B5.
8. Click OK.

![screenshot](Screenshots/Goal5.png)

Result: a grade of 90 on the fourth exam produces a final grade of 70.

![screenshot](Screenshots/Goal6.png)

Solve a Quadratic Equation

A quadratic equation is of the form ax^2 + bx + c = 0 where a ≠ 0. 

For example, we have the formula y = 3x^2 - 12x + 9.5. It's easy to calculate y for any given x.

For x = 2, y = -2.5

![screenshot](Screenshots/Goal7.png)

But what if we want to know x for any given y? For example, y = 24.5. We need to solve 3x^2 - 12x + 9.5 = 24.5. 

1. Click Goal Seek.
2. Select cell B2.
3. Click in the 'To value' box and type 24.5
4. Click in the 'By changing cell' box and select cell A2.
5. Click OK.

![screenshot](Screenshots/Goal8.png)

Result:

![screenshot](Screenshots/Goal9.png)
