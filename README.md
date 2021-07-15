# BalancedBrackets
Check for Balanced Brackets in an expression (well-formedness) using Stack


Example: 

Input: exp = “[()]{}{[()()]()}” 
Output: Balanced

Input: exp = “[(])” 
Output: Not Balanced 

Algorithm: 

Declare a character stack S.
Now traverse the expression string exp. 
If the current character is a starting bracket (‘(‘ or ‘{‘ or ‘[‘) then push it to stack.
If the current character is a closing bracket (‘)’ or ‘}’ or ‘]’) then pop from stack and if the popped character is the matching starting bracket then fine else brackets are not balanced.
After complete traversal, if there is some starting bracket left in stack then “not balanced”

Best Explainnation

https://www.youtube.com/watch?v=P31WyOcQvaE
