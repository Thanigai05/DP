

####
# DP

                                Algorithm for Solving LPP using Dynamic Programming

Step 1: Define the Problem

    Objective: Maximize Z=c1x1+c2x2+…Z=c1​x1​+c2​x2​+…
    Constraints:
        x1≤b1
        x2≤b2
        (other constraints)

Step 2: Create a Table to Track Values

    Make a table (matrix) to keep track of the objective function Z for each possible pair of values x1​ and x2​.

Step 3: Check All Combinations

    Loop through all possible values of x1​ and x2​ within their allowed limits (like 0 to 4 for x1​ and 0 to 6 for x2​).

Step 4: Verify Constraints

    For each pair of x1​ and x2​, check if they meet the constraints. If they do, calculate Z.

Step 5: Store the Best Value

    For valid pairs, calculate Z and store the highest Z you find.

Step 6: Track the Best Pair

    Keep track of which values of x1​ and x2​ give the best Z.

Step 7: Return the Best Solution

    After going through all combinations, return the highest Z and the values of x1​ and x2​ that gave that value.

--------------------------------------------------------------------------------------------------------------------------------

Steps in simple:

    - Start with an empty table to store possible Z values.
    - Loop through every possible x1​ and x2​ within their limits.
    - For each pair of x1​ and x2​, check if it meets the constraints.
    - If it does, calculate Z.
    - If this Z is bigger than the current best Z, update the best value.
    - After checking all pairs, return the best Z and the values of x1​ and x2​ that gave it.

===========================================================================================



                         Algorithm for Solving Cargo Loading using Dynamic Programming

Step 1: Define the Problem

    Objective: Maximize the total revenue from the selected items, where revenue = sum of the returns from selected items.
    Constraints:
        The total weight of selected items should not exceed the maximum weight capacity of the cargo.

Step 2: Create a Table to Track Values

    Create a table (matrix) to store the maximum possible revenue for each combination of items and weight capacity.

Step 3: Check All Combinations

    Loop through all possible items and weight combinations. For each item, check every weight capacity from 0 to the maximum capacity of the cargo.

Step 4: Verify Feasibility

    For each item and weight combination, check if including the item would exceed the cargo's weight capacity. If the item can be included, calculate the revenue.

Step 5: Store the Best Value

    For every feasible combination, calculate the possible revenue and store the maximum revenue found for each weight capacity.

Step 6: Track the Best Solution

    Keep track of the best (maximum) revenue and the specific items that contribute to this maximum revenue.

Step 7: Return the Best Solution

    After checking all possible combinations, return the maximum revenue and the corresponding items that were selected to achieve that revenue.

----------------------------------------------------------------------------------------------------------------------------
Steps in Simple Terms:

    - Start with an empty table to store the maximum revenue for each possible weight capacity.
    - Loop through every possible item and every weight capacity (from 0 to the max weight).
    - For each item and weight combination, check if including the item exceeds the cargo's capacity.
    - If the item can be included without exceeding the capacity, calculate the revenue and store it.
    - If the calculated revenue is higher than the previous maximum, update the table.
    - Once all combinations have been checked, return the maximum revenue and the items selected to achieve it.

===================================================================================================
