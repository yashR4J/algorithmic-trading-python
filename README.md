# The Algorithmic Trading Process (A High-Level Understanding)
### Steps of running a quantitative investing strategy can be broken down as follows:
1. Collect Data
2. Develop a hypothesis for the strategy
3. Backtest that strategy
4. Implement the strategy in production

=================

This module differs from production algorithmic trading in 3 major ways:
1. Uses random data
2. Does not execute trades
3. Saves recommended trades as Excel files

=================

IEX Cloud API

Public Resource for APIs:
https://github.com/public-apis/public-apis

#### **Virtual Environment Setup**

```bash
python3 -m virtualenv venv/
source venv/bin/activate

pip3 install -r requirements.txt

deactivate
```

# Project 1: Equal-Weighted S&P 500 Screener
S&P500 
- market capitalisation-weighted (larger companies have a larger weight)
    - alternatively, we construct a version of the S&P500 Index Fund that assigns each company with the same weighting

# Project 2: Quantitative Momentum Screener
- momentum investing: investing in assets that have increased in price the most

# Project 3: Quantitative Value Screener
- value investing: investing in stocks that are trading below their perceived intrinsic value
- creating algorithmic value investing strategies relies on concept of multiples
    - multiples: calculated by dividing company stock price by a measure of the company's worth (i.e. earnings, assets)
        - e.g. P/E ratio, P/BV ratio and P/FCF ratio
    - to minimise impact of a specific multiple - use a composite
        - this project uses a composite of 5 different value investing metrics

## Course Outline

* Section 1: Algorithmic Trading Fundamentals
  * What is Algorithmic Trading?
  * The Differences Between Real-World Algorithmic Trading and This Course
* Section 2: Course Configuration & API Basics
  * How to Install Python
  * Cloning The Repository & Installing Our Dependencies
  * Jupyter Notebook Basics
  * The Basics of API Requests
* Section 3: Building An Equal-Weight S&P 500 Index Fund
  * Theory & Concepts
  * Importing our Constituents
  * Pulling Data For Our Constituents
  * Calculating Weights
  * Generating Our Output File
  * Additional Project Ideas
* Section 4: Building A Quantitative Momentum Investing Strategy
  * Theory & Concepts
  * Pulling Data For Our Constituents
  * Calculating Weights
  * Generating Our Output File
  * Additional Project Ideas
* Section 5: Building A Quantitative Value Investing Strategy
  * Theory & Concepts
  * Importing our Constituents
  * Pulling Data For Our Constituents
  * Calculating Weights
  * Generating Our Output File
  * Additional Project Ideas
