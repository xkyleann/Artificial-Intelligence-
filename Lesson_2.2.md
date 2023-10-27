
# Arithmeics **Lesson 2.2**
* symbolic constants -> names
* constants -> numbers
* **_What to do_** -> working with numbers, perform basic arithmetics, defining complex operations, and utilize the properties numbers.

# Numerical Constans  
 ``` Prolog
	 x = 4. % it has to start with ?-
  ```
**_output_** -> X = 4 

# Operators 
* X =:= Y  -> the X and Y values are equal 
* X =\= Y -> the X and Y values are not equal 
* X < Y  ->   X is less than Y
* X =< Y -> X is less than or equal Y
* X > Y -> X is greater than Y
* X >= Y -> X is greater or equal to Y

 ``` Prolog
	 4 =< 4. %it has to start with 
 ```

``` Prolog
(1)   test(X) :- X > 3, write('Wow, you are amazing'), nl %if number in test(X) bigger than 3 it will write and say true.
(2)   test(X) :- X = 3, write('Good enough.'), nl %if number in text(X) is equal to 3, it will write and say false.
(3)   text(X) :- X < 3, write('Do  not worry, there is second attempt in February'), nl. %if the number in text(X) is smaller than 3 it will write that output and say true.
```

**_Examples_**:
 * ?- test(4). %X=4, so output is matches with rule (1)
   * Wow, you are amazing! true
 * ?- test(3).  % X=3, so output is matches to rule (2)
   * Good enough. true
 * ?- test(0). % X=0, so output is matches to rule (3)
  * Do not worry, there is second attempt in February.

# Arithmetic Operations 
*  
