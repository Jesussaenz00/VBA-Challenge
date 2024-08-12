# VBA-Challenge

In this challenge I was asked to develop a VBA script to help analyze a dataset containing types of stocks with their open price, closing price, highest price, lowest price and their daily performance. The dataset is divided by quarters and are represented in a single sheet, so the dataset contains 4 sheets; reporting records from a single year. 

In the script I added columns to every sheet, representing how the stock performed in the quarter. The analysis begins with a column added, representing the quarterly change from the opening price at the beginning of a given quarter to the closing price at the end of that quarter. Then the percentage change from the opening price at the beginning of a given quarter to the closing price at the end of that quarter. Finally the last column is the total stock volume of the stock. 

To finalize the analysis I added a function to represent the "Greatest % increase", "Greatest % decrease", and "Greatest total volume”. This function applies to every sheet representing every quarter. 
