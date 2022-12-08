# JPMC Task 1

### Creating the virtual environment

In the terminal:

`> python -m venv venv`

Now we will see semething like (venv) C:\your\project\path\jpmc-task=1

### Installing requirements.txt

`pip install -r requirements.txt`

<hr>

## Task

### Purpose

We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

### Acceptance Criteria

getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask
getRatio function should return the ratio of the two stock prices
main function should output correct stock info, prices and ratio
