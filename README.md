# Code-Alpha-stock-protfolio-tracker-code
stocks={
"TCS":3500,
"INFY":1500,
"WIPRO":500
}
stock= input("Enter stock name:").upper()
quantity = int(input("Enter quantity: "))
if stock in stocks:
     total=stocks[stock]*quantity
     print("Total Investment value=",total)
else:
         print("Stock not found")