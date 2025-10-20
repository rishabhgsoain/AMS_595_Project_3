# AMS_595_Project_3

The purpose of this project was to practice Python programming skills including loops, recursion, list comprehension, and mathematical calculation as part of the coursework at **Stony Brook University**.  
 All code, explanations, and outputs are contained in the notebook `Gosain_Rishabh_Project3.ipynb`.

 ---

 ## Summary
 Through brief coding exercises emphasizing mathematical reasoning and effective algorithm design, this project aims to improve comprehension of Python foundations.  
 The tasks include factorization, prime number production, and recursive functions (such as Pascal's Triangle).

 ---

 ## Creating Pascal's Triangle Rows

 The *n*th row of Pascal's Triangle is returned by the recursive function `pascal(n)`.  
 Recurrence rule → `row[i] = previous[i − 1] + previous[i]` is used.  
 Both loop-based and recursive methods are shown.  
 The output is validated for sample inputs, such as `n = 5 → [1, 4, 6, 4, 1]`.

 ## Calculating the Prime Factor

 - Specifies the `prime_factors(n)` function, which yields a number's prime factors.  
 - Iterates across `range(2, n + 1)` using list comprehension, including prime (`is_prime(i)`) and precise divisors of `n` numbers.  
 Outputs like `prime_factors(60) → [2, 3, 5]` are produced.  
 The idea of reusable helper functions (`is_prime`) is reinforced.

 ---

 ## Thinking Iteratively and Recursively

 Iteration and recursion are contrasted in situations such as Pascal's Triangle.  
 Recursion makes reasoning simpler, although it might not be as effective for high n.  
 - Talks about memory utilization in recursion, base cases, and function calls.

 ---

 ## Tools Used

 Python 3 is the language used. The environment is Jupyter Notebook. The optional libraries are NumPy and Matplotlib *(if visualization is provided).

 ---

 Rishabh Gosain
 116732806
