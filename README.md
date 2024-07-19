Installment Description (Function)
- Personal information entry function
Allow users to fill in their first name, last name, national ID card number, address, and telephone number.
- Purchasing information entry function
Fill in the room price, down payment price, installment period (years).
- Function to check money in account
Check the money in the buyer's wallet to see if there is enough to make a down payment on the condo + the first installment.
- Annual interest rate calculation function
There are conditions for calculating the annual interest rate. With factors coming from Down payment price and installment period (years)
The conditions are as follows: - Down payment less than 10%, repayment period less than 10 years = interest rate 5% - Down payment less than 10%, repayment period more than or equal to 10 years and less than 20 years = interest rate.
6% - Down payment less than 10%, Installment period greater than or equal to 20 years = Interest rate 7% - Down payment less than 20%, Installment period less than 10 years = Interest rate 4% - Down payment less than 20%, installment period greater than or equal to 10 years and less than 20 years = interest rate
5% - down payment less than 20%, term greater than or equal to 20 years = interest rate 6% - down payment more than 20%, installment period less than 10 years = interest rate 3% - down payment more than 20%, Installment period greater than or equal to 10 years and less than 20 years = interest rate
4% - Down payment more than 20%, term more than or equal to 20 years = interest rate 5%
- Function to show condo price including all interest.
- Condo down payment display/collection function
- Function to display/collect monthly installments
- Currency conversion function between ETH and USD using Oracle.


Oracle >>> @chainlink/contracts/src/v0.8/shared/interfaces/AggregatorV3Interface.sol </br>
Wallet >>> Metamask </br>
Framework >>> https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js </br>
