# JPMC Task 1 Documentation

## Background

You have been tasked with adding a chart to a trader's dashboard to help them identify under/over-valued stocks. The trader wants to monitor two historically correlated stocks and visualize when the correlation weakens, indicating a potential trade strategy. By identifying when one stock moves proportionally more than the historical correlation would imply, traders can buy the underperforming stock and sell the outperforming stock. Assuming the prices converge, the trade should be profitable.

Most data visualization for traders is built using JPMorgan Chase's Perspective data visualization software. This task involves interfacing with the relevant financial data feed and making adjustments to monitor potential trade opportunities.

- Bid Price: Highest price a buyer is willing to pay.
- Ask Price: Lowest price a seller is willing to accept.
- Price: Average of bid and ask prices, representing a mid-market price.
- Top Bid (Highest Bid Price): Reflects the highest price buyers are willing to pay.
- Top Ask (Lowest Ask Price): Reflects the lowest price sellers are willing to accept.
## Task Instructions

### 1. Set Up Your Local Development Environment

- Download the necessary files, tools, and dependencies.
- Set up a virtual environment using the command:
  ```sh
  python3 -m venv venv
  git commit ...
  git format-patch -1 HEAD

For the first task of this project you will need to accomplish the following:

### 1. Set up your local dev environment by downloading the necessary files, tools and dependencies.
### 2. Fix the broken client datafeed script in the repository by making the required adjustments to it.
### 3. Generate a patch file of the changes you made
### (optional): Add unit tests in the test script in the repository.
### 4. Submit your work
Let's get to work! 
