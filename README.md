# Survival-Duration-Calculator
The provided code defines a function named `age_calculator()` which calculates the duration of a person's life based on their age and the selected time unit. Here's a description of the code:

1. **Function Definition**:
   - The code defines a function named `age_calculator()`.

2. **User Interaction**:
   - The program prints a welcome message for the survival duration calculator.
   - It prompts the user to input their age.

3. **Time Unit Selection**:
   - After inputting the age, the user is prompted to choose a time unit (Months, Weeks, Days, Hours, Minutes, or Seconds) to represent the duration of their life.

4. **Calculation**:
   - Based on the selected time unit, the program calculates the duration of the person's life in that unit.
   - The calculation is performed by multiplying the age by the corresponding conversion factor for the chosen time unit.
   - For example, if the user selects "Months", the age is multiplied by 12 to calculate the duration in months.

5. **Output**:
   - The program then prints the calculated duration in the selected time unit.

6. **Error Handling**:
   - The code handles errors for invalid inputs. If the user enters an unexpected input for the time unit selection, it simply prints "No response".

7. **Return Statement**:
   - Finally, the function returns to the caller after printing the result.

Overall, the code provides a simple calculator for determining the duration of a person's life in different time units based on their age.
