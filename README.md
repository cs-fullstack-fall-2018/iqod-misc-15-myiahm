# IQOD_Misc_18
Interview Question of the Day

## Coinify

Write a function to convert some amount (100 or less) to the fewest number of coins. It should take 2 arguments: The amount to convert, and an array of the coin values available in standard denominations. Print the combination of coins for change.

    Sample function : amountTocoins(46, [25, 10, 5, 2, 1])
    
    Here 46 is the amount. and 25, 10, 5, 2, 1 are coins. 
    
    Output : 25, 10, 10, 1

### HINT: Start with highest to lowest number of coins passed in to function and think modulus :-P

### BONUS: Reject amounts greater than 100 and log appropriate message
