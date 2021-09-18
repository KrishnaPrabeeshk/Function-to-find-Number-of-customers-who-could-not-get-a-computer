#-find-Number-of-customers-who-could-not-get-a-computer
Input will be n ->  total number of computers in a cafe followed by seq  Letters in the sequence occur in pairs. The first occurrence indicates the arrival of a customer; the second indicates the departure of that same customer. 
A customer will be serviced if there is an unoccupied computer.
For each set of input the function should output a number telling how many customers, if any walked away without using a computer. Return 0 if all the customers were able to use a computer.
example: (2, “ABBAJJKZKZ”) should return 0 , (3, “GACCBDDBAGEE”) should return 1 as ‘D’ was not able to get any computer
