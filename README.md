# Task 1 – Stack Trace
Paste your completed manual Stack trace here:

{ [ ( ) ] }

# Task 2 – Stack based delimiter checker
Paste:
Screenshot of your source code
<img width="653" height="706" alt="Screenshot 2026-10-18 222049" src="https://github.com/user-attachments/assets/9fa37770-1f23-48cf-ac37-0e4fa3003ae2" />

Screenshot of a valid input and output
<img width="500" height="94" alt="image" src="https://github.com/user-attachments/assets/291c0e38-7eda-4140-818e-7d4e634f025b" />

Screenshot of an invalid input and output
<img width="681" height="64" alt="image" src="https://github.com/user-attachments/assets/03431849-2abd-4df2-af75-fde135cd2a84" />

# Task 3 – Search Trace
Paste:
<img width="769" height="880" alt="Screenshot 2026-10-18 215913" src="https://github.com/user-attachments/assets/2b7d8b40-8395-4c2a-9375-eab9eaf27b75" />
<img width="876" height="843" alt="Screenshot 2026-10-18 215939" src="https://github.com/user-attachments/assets/d59864ca-e5d8-4a94-8c0d-d3f7b16925d1" />
<img width="684" height="576" alt="Screenshot 2026-10-18 220016" src="https://github.com/user-attachments/assets/e66d115c-2de1-4e51-b079-d74a4b681a0c" />

# Task 4 – Explanation
The program checks if the opening and closing delimiters in a given input are properly matched. It uses a stack to keep track of opening delimiters like `(`, `[` and `{`. When the program encounters an opening delimiter, it performs a PUSH operation to add it to the stack. When it finds a closing delimiter, it uses PEEK to check the top of the stack. If the delimiters match, it performs a POP operation to remove the opening delimiter.

The program also displays a stack execution trace, showing each character being examined, the operation performed, and the current contents of the stack. If a closing delimiter has no matching opening delimiter or the delimiters do not match, the program displays an invalid result with the reason. After checking all the characters, it displays Valid if all delimiters are properly matched and the stack is empty. This helps us understand how a stack works and how it can be used to check delimiters in a sequence of characters.
