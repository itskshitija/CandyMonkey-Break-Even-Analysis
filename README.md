# 🍫CandyMonkey Case Study: Break-Even Analysis
<img src="https://github.com/user-attachments/assets/4430a3b1-7c3e-4c2f-aaa5-a0f2d04e40dd" alt="CandyMonkey Logo" width="200"/>

## 📌Introduction
CandyMonkey, a local confectionery brand in Raipur, is launching a new chocolate product called the Mini Pack. This chocolate is expected to appeal to both children and families seeking delightful chocolate treats. The company has conducted a market study and has generated reliable sales forecasts. They have already developed samples and know the proportion of different raw materials that will be used. You have been provided with the following information by the company and have been asked to conduct a break-even analysis for CandyMonkey’s new product. This involves estimating the sales required to cover all costs, taking into account sales forecasts, variable costs, and fixed costs. They plan to launch this product on January 1st, 2024.

## 🚀Objective
Create a financial model covering the first twelve months to perform a break-even analysis for CandyMonkey's Mini Pack chocolates. Utilize the provided sales forecasts, variable costs, and fixed costs, and assess how different factors could influence profitability.

## 📍Business Case
A CandyMonkey company wants to overhaul their business strategy, To do so the management team has requested these specific details:
- **Develop a financial model to perform a break-even analysis for the Mini Pack.**
- **Estimate the sales volume required to cover fixed and variable costs over the first twelve months.**
- **Evaluate the impact of changes in key variables (e.g., pricing, costs, sales growth) on profitability.**
- **Provide insights to guide strategic decisions related to pricing, production, and marketing.**

## 📜Requirement Gathering and Documentation
As a business analyst, the first step would be to gather all the requirements necessary for the analysis and document it.
Documentation is the most critical part of project development as it is the foundation of all further project deliverables describing what inputs and outputs are associated with each process function.

### I have created a Business Requirement documentation for our business case [Here](https://github.com/itskshitija/CandyMonkey-Break-Even-Analysis/blob/main/CandyMonkey_BRD.pdf)

### CandyMonkey Mini Pack Details

## Packet Size
| Item               | Packet (in gms) | Price (in Rs. per unit) |
|--------------------|-----------------|-------------------------|
| Mini Pack (100g)   | 100             | 140                     |

## Material Details of Each Packet
| Item         | Price/kg in Rs. | Material % |
|--------------|-----------------|------------|
| Cocoa        | 1000            | 40%        |
| Sugar        | 50              | 45%        |
| Fruit n Nut  | 1200            | 5%         |
| Others       | 150             | 10%        |

## Sales Quantity and Growth
| Item               | 1st Month (in units) | Month on Month Growth % |
|--------------------|-----------------------|--------------------------|
| Mini Pack (100g)   | 1300                 | 10% from 4th month onwards |

## Labour and Packing Cost
| Item               | Cost per Unit (in Rs.) |
|--------------------|------------------------|
| Mini Pack (100g)   | 10                     |

## Factory Expenses
| Expense Type       | Amount (in Rs.) |
|--------------------|-----------------|
| Factory Rent       | 60,000          |
| Administration Cost| 35,000          |

## Marketing Cost
| Month             | Cost (in Rs.)     | Month on Month Growth % |
|-------------------|-------------------|--------------------------|
| 1st Month         | 50,000            | 10% from 4th month onwards |

## Sales Quantity Calculation for CandyMonkey Mini Pack
### Sales (in Units)
| Month      | January | February | March | April | May  | June | July | August | September | October | November | December |
|------------|---------|----------|-------|-------|------|------|------|--------|-----------|---------|----------|----------|
| Mini Pack  | 1300    | 1300     | 1300  | 1430  | 1573 | 1731 | 1905 | 2096   | 2306      | 2537    | 2791     | 3071     |

### Unit Sales Price (in Rs.)
| Month      | January | February | March | April | May  | June | July | August | September | October | November | December |
|------------|---------|----------|-------|-------|------|------|------|--------|-----------|---------|----------|----------|
| Mini Pack  | 140     | 140      | 140   | 140   | 140  | 140  | 140  | 140    | 140       | 140     | 140      | 140      |

- The sales after March increased due to month-on-month growth of 10% starting from the fourth month (April).
  #### Sales After March = (1300 + 10%)
- Selling price of Mini Pack chocolates are same throughout the year i.e Rs.140

## Raw Material Consumed in kg
Raw materials are - 
1. Cocoa
2. Sugar
3. Fruit n nut
4. Others

## Raw Material Consumed (in Kg)
| Month      | Cocoa (kg) | Sugar (kg) | Fruit n Nut (kg) | Others (kg) |
|------------|------------|------------|------------------|-------------|
| January    | 52         | 58.5       | 6.5              | 13          |
| February   | 52         | 58.5       | 6.5              | 13          |
| March      | 52         | 58.5       | 6.5              | 13          |
| April      | 57.2       | 64.35      | 7.15             | 14.3        |
| May        | 62.92      | 70.785     | 7.865            | 15.73       |
| June       | 69.24      | 77.895     | 8.655            | 17.31       |
| July       | 76.2       | 85.725     | 9.525            | 19.05       |
| August     | 83.84      | 94.32      | 10.48            | 20.96       |
| September  | 92.24      | 103.77     | 11.53            | 23.06       |
| October    | 101.48     | 114.165    | 12.685           | 25.37       |
| November   | 111.64     | 125.595    | 13.955           | 27.91       |
| December   | 122.84     | 138.195    | 15.355           | 30.71       |

#### Raw Material Consumed (in Kg) is calculated as:
```
Raw Material Consumed (kg)=Sales Quantity (units)×Material per Unit (grams)÷1000
```

## Cost of Raw Material (in Rs.) 

| Month      | Cocoa Cost (Rs.) | Sugar Cost (Rs.) | Fruit n Nut Cost (Rs.) | Others Cost (Rs.) | Total Cost (Rs.) | Cost of Material (per unit) (Rs.) |
|------------|------------------|------------------|-------------------------|-------------------|------------------|----------------------------------|
| January    | 52000            | 2925             | 7800                   | 1950             | 64675            | 49.75                            |
| February   | 52000            | 2925             | 7800                   | 1950             | 64675            | 49.75                            |
| March      | 52000            | 2925             | 7800                   | 1950             | 64675            | 49.75                            |
| April      | 57200            | 3217.5           | 8580                   | 2145             | 71142.5          | 49.75                            |
| May        | 62920            | 3539.25          | 9438                   | 2359.5           | 78256.75         | 49.75                            |
| June       | 69240            | 3894.75          | 10386                  | 2596.5           | 86117.25         | 49.75                            |
| July       | 76200            | 4286.25          | 11430                  | 2857.5           | 94773.75         | 49.75                            |
| August     | 83840            | 4716             | 12576                  | 3144             | 104276           | 49.75                            |
| September  | 92240            | 5188.5           | 13836                  | 3459             | 114723.5         | 49.75                            |
| October    | 101480           | 5708.25          | 15222                  | 3805.5           | 126215.75        | 49.75                            |
| November   | 111640           | 6279.75          | 16746                  | 4186.5           | 138852.25        | 49.75                            |
| December   | 122840           | 6909.75          | 18426                  | 4606.5           | 152782.25        | 49.75                            |

#### The Cost of Material per Unit is calculated by dividing the Total Cost of Raw Materials by the Total Sales Quantity (in units) for the respective month. 
```
Cost of Material per Unit = Sales Quantity (units) ÷ Total Cost of Raw Materials (Rs)
```
The cost of raw materials is increasing after March due to the 10% month-on-month growth in sales quantity starting from April. As the sales quantity increases, the total amount of raw materials required also increases, directly impacting the cost.

## Contribution Analysis
#### Breakdown of Contribution:
- **Sales:** Total revenue generated from selling Mini Packs.
- **Variable Cost:** Total cost of materials and labor (changes based on sales volume).
- **Contribution:** The profit remaining after deducting variable costs, which contributes to covering fixed costs and generating profit.
  
```
Contribution = Sales - Variable Cost
```
| Month        | Sales (₹) | Material Cost (₹) | Labour Cost (₹) | Total Variable Cost (₹) | Contribution (₹) | Contribution per Unit (₹) |
|--------------|-----------|-------------------|-----------------|-------------------------|------------------|---------------------------|
| January      | 182,000   | 64,675            | 13,000          | 77,675                 | 104,325          | 80.25                     |
| February     | 182,000   | 64,675            | 13,000          | 77,675                 | 104,325          | 80.25                     |
| March        | 182,000   | 64,675            | 13,000          | 77,675                 | 104,325          | 80.25                     |
| April        | 200,200   | 71,142.5          | 14,300          | 85,442.5               | 114,757.5        | 80.25                     |
| May          | 220,220   | 78,256.75         | 15,730          | 93,986.75              | 126,233.25       | 80.25                     |
| June         | 242,340   | 86,117.25         | 17,310          | 103,427.25             | 138,912.75       | 80.25                     |
| July         | 266,700   | 94,773.75         | 19,050          | 113,823.75             | 152,876.25       | 80.25                     |
| August       | 293,440   | 104,276           | 20,960          | 125,236                | 168,204          | 80.25                     |
| September    | 322,840   | 114,723.5         | 23,060          | 137,783.5              | 185,056.5        | 80.25                     |
| October      | 355,180   | 126,215.75        | 25,370          | 151,585.75             | 203,594.25       | 80.25                     |
| November     | 390,740   | 138,852.25        | 27,910          | 166,762.25             | 223,977.75       | 80.25                     |
| December     | 429,940   | 152,782.25        | 30,710          | 183,492.25             | 246,447.75       | 80.25                     |

#### Observation
- The Contribution per Unit (₹80.25) remains consistent across all months because the sales price per unit (₹140) and the material cost per unit (₹49.75) are constant.
- Any increase in total contribution is due to the growth in sales quantity from April onwards.

## Break-Even Analysis
Break-Even Analysis is a financial calculation used to determine the point at which total revenue equals total costs (both fixed and variable), resulting in neither profit nor loss. This point is known as the break-even point (BEP). It helps businesses understand how many units of a product or service they need to sell to cover their costs.

### Financial Performance Table (Amount in Rs)

| **Description**           | **Jan**  | **Feb**  | **Mar**  | **Apr**  | **May**  | **Jun**  | **Jul**  | **Aug**  | **Sep**  | **Oct**  | **Nov**  | **Dec**  |
|----------------------------|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| **Contribution**          | 104,325  | 104,325  | 104,325  | 114,758  | 126,233  | 138,913  | 152,876  | 168,204  | 185,057  | 203,594  | 223,978  | 246,448  |
| **Fixed Expenses**        |          |          |          |          |          |          |          |          |          |          |          |          |
| Factory Rent              | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   | 60,000   |
| Administration Cost       | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   | 35,000   |
| Marketing Cost            | 50,000   | 50,000   | 50,000   | 55,000   | 60,500   | 66,550   | 73,205   | 80,526   | 88,578   | 97,436   | 107,179  | 117,897  |
| **Total Fixed Expenses**  | 145,000  | 145,000  | 145,000  | 150,000  | 155,500  | 161,550  | 168,205  | 175,526  | 183,578  | 192,436  | 202,179  | 212,897  |
| **Profits**               | -40,675  | -40,675  | -40,675  | -35,243  | -29,267  | -22,637  | -15,329  | -7,322   | 1,478    | 11,158   | 21,798   | 33,550   |

#### **Negative Profits (January to August):**
- From January to August, the profits remain negative, reflecting that the business's Contribution was insufficient to cover the Fixed Expenses (Factory Rent, Administration Costs, and Marketing Costs).
- This indicates that the business had not yet reached its break-even point — the point where Total Contribution = Total Fixed Expenses, and profits become zero.

#### Transition to Positive Profits (September Onwards):
- From September onwards, profits turn positive, showing that the business has successfully surpassed its break-even point.
- This change implies that the cumulative increase in contribution margin from growing revenue has finally covered all fixed costs, and the business is now generating surplus profits.

#### Break-Even Analysis
- The negative profits until August indicate that the business was operating below the break-even point.
- The positive profits from September onwards signify that the business has crossed the break-even threshold, and every additional contribution is directly adding to profits.

The primary driver of achieving the break-even point here is the incremental increase in contribution margin due to increased sales revenue over the months.

## 📊Visualizing Break-Even Analysis
![image](https://github.com/user-attachments/assets/c838589f-2803-4021-bf98-c75b4cf30783)

![image](https://github.com/user-attachments/assets/ab18798e-d7f5-41a3-8176-082ab034be01)

## 🔚Insights
- **Sales:** Sales and increasing from 4th month onwards which is resulting in increased total contribution per month from the newly launched product Mini Pack.
- **Break-Even  Point:**  Company will be able to achieve the break-even point in the month of September and then profits will continue to rise till the month of December as per data provided for forcast.
