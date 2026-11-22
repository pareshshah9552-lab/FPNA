  I built this project to practise FP&A work: comparing revenue against budget, looking at overdue invoices, and checking whether a discount is worth offering to get paid sooner.

All the data is made up (sample data). It is not from any company or client.

 What I wanted to find out
1. Where did revenue come in above or below budget, and was it because of volume or price?
2. How much money is overdue, and which products does it sit with?
3. Is it worth giving a small discount to get overdue invoices paid?

 What is in the Excel file
- **Summary**: budget vs actual/forecast revenue by product, and the overdue amount for each.
- **Analysis**: my findings, recommendations, and a month-by-month trend.
- **Data**: the monthly volume and price for 4 products.
- **Overdue AR**: the list of overdue invoices, how old they are, and the main risks.
- **Discount Scenario**: compares 1% to 10% discounts against doing nothing.

 How I worked it out
- Volume variance = (actual volume - budget volume) x budget price
- Price variance = (actual price - budget price) x actual volume
- Overdue age = today's date minus the due date, grouped into 0-3, 3-6, 6-12 and 12+ months
- For the discount, I compared the cash I would expect with a discount offer against the cash I would expect with no offer

What I found
- Total revenue ended up almost the same as budget, but that hid big differences between products. Pro Plan was 8.2% above budget, Enterprise Plan was 8.7% below, and Basic Plan lost money on price.
- 8 invoices are overdue, totalling $105,726. Three of them make up about 56% of the total.
- Enterprise Plan has the most overdue money and is already below budget, so I would follow up on it first.
- In my model, a 5% discount gave the best result. The recovery and acceptance rates are my own assumptions (you can change them in the blue cells), so treat the result as an example, not a real outcome.

 Tools
Excel (formulas, SUMIFS, charts) and Power BI.

## About me
Paresh Shah, finance professional focused on FP&A and revenue analysis.
LinkedIn: https://www.linkedin.com/in/paresh-shah-702364207
