# <h1 align="center">Market Analysis for National Clothing Chain</h1>

<p>In this repository, you'll find a detailed market analysis report for a national clothing chain using Power BI. The analysis leverages custom M and DAX codes to extract insights from customer data and US Census Bureau statistics.</p>



<p align="center"><img width="738" alt="Screenshot 2024-01-20 at 4 05 48 PM" src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/e6b4cc9a-dccf-4893-a9f7-d25fe1f516d7"></p>

---------------------------------------

<h3 align="center">General Analysis</h3>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/3a7ff0ae-633f-4d26-b00b-cfaf18c9ec4f" alt="General Analysis"></p>

The analysis kicks off by predicting customer income based on their last 6 months' purchases, utilizing a linear regression formula: ```Y = mX + b``` In this context, 
  - (Y) represents the average sale per state, dependent on 
  - (X) the average income per state.
  - The correlation between average sales and average income is calculated as **0.78**, demonstrating a strong relationship.

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/125f3606-c0c1-400d-85aa-3d661f4d8a0b" alt="General Analysis Chart"></p>

---------------------------------------

<h3 align="center">Customers Analysis</h3>

Predicting customer incomes enables a deeper understanding, guiding product recommendations. 
The formula for predicted income is expressed as ```Predicted Income = -722.14 - Y / -0.01``` 
The analysis highlights:

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/96e49801-3803-4402-bd83-41b7aaf1df6e" alt="Customers Analysis"></p>

<ul>
  <li>Highest income customer: Jon Little (Income: $556.79k)</li>
  <li>Correlation between income and sale: R^2 = 0.78</li>
  <li>Customers categorized into income buckets for targeted product recommendations.</li>
</ul>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/335d9018-d117-4b22-a119-5ac0d175744a" alt="Customers Analysis Buckets"></p>

---------------------------------------

<h3 align="center">Products Analysis</h3>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/76c1bb13-9ca8-4b62-b9ee-93cc88cce454" alt="Products Analysis"></p>

<p align="center">Building on customer analysis, customers are categorized into three income ranges: Low, Medium, and High. Recommendations by category:</p>

<ul>
  <li>Low-Income: Recommend (Shirt) to 44% of customers.</li>
  <li>Medium-Income: Recommend (Shirt and Sweater) to 39.70% of customers.</li>
  <li>High-Income: Recommend (Shirt, Sweater, and Leather Bag) to 16.30% of customers.</li>
</ul>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/0a1c1d4f-ae4f-4a25-8202-434b38f4c889" alt="Products Analysis Chart 1"></p>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/ea7b85b0-1d76-487d-952a-243c2763fbc3" alt="Products Analysis Chart 2"></p>

<p>After studying and analyzing the relation between the customers rating and the return rate of the products, we find that the correlation between the return rate and the customers rating is R^2 = (0.50).</p>

---------------------------------------

<h3 align="center">Other Analysis and Recommendations</h3>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/ab82fee4-b20a-42e2-8e8f-6bd08847c4ea" alt="Other Analysis"></p>

<p align="center"><img src="https://github.com/Gab-182/Market-Analysis-Report-for-National-Clothing-Chain/assets/83855149/62044bd3-22ff-4b87-88b7-9efbd4d2dba8" alt="Other Analysis Chart"></p>

<p>Here we show the 10 highest and lowest states by income, which the advertising and product recommendation should consider with the earlier findings such as the customers buys and incomes.</p>

<ul>
  <li>Top and bottom 10 states by income are identified for targeted advertising and product recommendations.</li>
  <li>Recommendations:
    <ul>
      <li>Market the Sweater strategically in states with colder climates to maximize sales.</li>
      <li>Improve the quality of the Leather Bag for high-income customers, considering its low rating (3.2).</li>
      <li>Promote Shirts in the lowest 10 states, given their high rating and preference among low-income customers.</li>
    </ul>
  </li>
</ul>
