def max_stolen_value(vals):
    prev1 = prev2 = 0
    for val in vals:
        prev1, prev2 = max(prev1, prev2 + val), prev1
    return prev1

vals = [6, 7, 1, 3, 8, 2, 5]
print("Maximum stolen value:", max_stolen_value(vals))
