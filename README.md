# ExcelTutorial

Excel formulas are essential for data analysts because they:

1. Automate repetitive calculations and processes, saving time.
2. Ensure accuracy and consistency in calculations.
3. Provide flexibility to manipulate and transform data.
4. Create reproducible and auditable analysis workflows.
5. Can be integrated with other Excel features to enhance data visualization capabilitie

## Basic Formulas in Excel

The below about 17 basic Excel formulas.

| Index | Formula | Explanation | Example |
|-------|---------|-------------|---------|
| 1.    | SUM     | The SUM() formula performs addition on selected cells. It works on cells containing numerical values and requires two or more cells. | =SUM(A2:A5) will add the values in cells A2 to A5. |
| 2.    | MIN     | The MIN() formula returns the minimum value from a range of cells. | =MIN(A7:A10) will find the minimum value among the cells in range A7 to A10. |
| 3.    | MAX     | The MAX() formula returns the maximum value from a range of cells. | =MAX(A7:A10) will find the maximum value among the cells in range A7 to A10. |
| 4.    | AVERAGE | The AVERAGE() formula calculates the average of selected cells. | =AVERAGE(A2:A5) will calculate the average of values in cells A2 to A5. |
| 5.    | COUNT   | The COUNT() formula counts the total number of selected cells. | =COUNT(A7:A10) will count the total number of cells in range A7 to A10. |
| 6.    | POWER   | The POWER() formula raises a number to a specified power. | =POWER(A12/100,2) will square the value in cell A12 divided by 100. |
| 7.    | CEILING | The CEILING() formula rounds a number up to the nearest given multiple. | =CEILING(A13,1) will round the value in cell A13 up to the nearest whole number. |
| 8.    | FLOOR   | The FLOOR() formula rounds a number down to the nearest given multiple. | =FLOOR(A14,1) will round the value in cell A14 down to the nearest whole number. |
| 9.    | CONCAT  | The CONCAT() formula joins or merges multiple strings or cells with strings into one. | =CONCAT(A2,B2) will join the values in cells A2 and B2. |
| 10.   | TRIM    | TRIM removes extra spaces from text, commonly used to clean data. | =TRIM(A15) will remove extra spaces from the text in cell A15. |
| 11.   | REPLACE | The REPLACE() formula replaces part of a text string with a different text string. | =REPLACE(A16,1,1,"B") will replace the first character with "B" in cell A16. |
| 12.   | SUBSTITUTE | The SUBSTITUTE() formula replaces occurrences of a specified substring within a string. | =SUBSTITUTE(A17,"Jacoba","Rahim") will replace "Jacoba" with "Rahim" in cell A17. |
| 13.   | LEFT    | The LEFT() formula returns the specified number of characters from the start of a text string. | =LEFT(A18,9) will return the first nine characters from cell A18. |
| 14.   | MID     | The MID() formula returns a specific number of characters from a text string, starting at a specified position. | =MID(A19,11,6) will return characters starting from the 11th position in cell A19. |
| 15.   | RIGHT   | The RIGHT() formula returns the specified number of characters from the end of a text string. | =RIGHT(A20,7) will return the last seven characters from cell A20. |
| 16.   | XLOOKUP | The XLOOKUP() formula searches for a value in a range and returns a corresponding value in another range. | =XLOOKUP("search_value", A1:A10, B1:B10) will search for "search_value" in range A1:A10 and return the corresponding value from range B1:B10. |
| 17.   | IFS     | The IFS() formula checks multiple conditions and returns a value corresponding to the first TRUE condition. | =IFS(A21<10, "Small", A21<20, "Medium", A21<30, "Large") will return "Small" if A21 is less than 10, "Medium" if A21 is less than 20, and "Large" if A21 is less than 30. |

## Example
- [Basic formulas example Excel file](/BasicFormulas/BasicFormulas.xlsx)
  
![BasicFormulas image](/BasicFormulas/BasicFormulas.png)

