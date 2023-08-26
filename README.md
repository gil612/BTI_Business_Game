# BTI_Business_Game
In BTI we simulate a business game, to train our management skills. In Jupyter Notebook we developed an algorithm to list the most profitable orders.
The source can be found here: https://bti-online.com/business-games/?lang=en

The game aims to creating good balance sheet, income statement and cash flow statement, according to a strategy built within the group.

### Order
Order is a card specifying:

- The ID the order
- Type of product [Basic, Comfort, Hyper]
- Number of pieces
- Revenue (in M)
- The time (in quarters) needed to be paid [1, 2]
- Shipping quarter [1, 2, 3, 4]
- Market [Europa, Nordamerika, Asien]

The production cost is calculated with the formula `#pieces * value of piece` (usually 4M per piece).

The difference between the revenue and production cost of each order must be large. 


In first year the game is played with same given orders for all groups. After the first year round is completed, follow these instructions:

1. Every group decides how many orders to handle each year.
1. The orders are given by turns for second year.
1. Year two round is being played according to a task list.
1. Balance sheet, income statement, cashflow statement are filled out.

After the second year round is completed repeat the same process for the third year.



Since the strategy of our group was mass production, we decided to focus on the basic products with highest value.

Here's a dictionary of important accounting terms:

Umsatzerlöse : Revenue<br>
Jahresüberschuss /-fehlbetrag : Net income<br>
Aktiva : Liabilities and owner's equity<br>
Passiva : Assets<br>
Zins : Interest rate<br>
Umsatzrentabilität : Operating Margin<br>
Kapitaluschlagshäufigkeit: Asset turnover<br>
Eigenkapitalretabilität : Return on equity<br>
Gesamtkapitalrentabilität : Return on assets<br>
Verschuludngsgrad : debt-to-equity ratio (D/E)<br>
Cashflow aus der Gesachäftstätigkeit : Operativ cash flow<br>
Cashflow aus der Investitionstätigkeit : Investing cash flow<br>
Cashflow aus der Finanztätigkeit : Financing cash flow
