# COBOL Numeric Data Handling Bug

This repository demonstrates a common error in COBOL programs related to the handling of numeric data. The program initializes a counter and increments it within a loop.  The issue arises when the counter exceeds its defined size, potentially leading to unexpected results or program termination.  The solution addresses this by using a data type that can accommodate the expected range of values. 

**Bug:** The program might produce incorrect results or fail if the counter exceeds its data type limits. 
**Solution:** Use a larger data type for the counter variable to handle larger values without exceeding its capacity. 
