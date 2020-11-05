# Session_3 Assignment

***The solution with test cases available in notebook.***


***1) Write a function using only list filter lambda that can tell whether a number is a Fibonacci number or not. You can use a pre-calculated list/dict to store fab numbers till 10000 : *** 

**def fib_checker(t:int)**

***2) Using list comprehension (and zip/lambda/etc if required) write five different expressions that :***

* Add 2 iterables a and b such that a is even and b is odd : 
**def odd_even_adder(list1 :list, list2:list)**

* Strips every vowel from a string provided (tsai>>t s) : 
**def strip_vowel(s : str)**

* Acts like a ReLU function for a 1D array : 
**def relu(l :list)**

* Acts like a sigmoid function for a 1D array : 
**def sigmoid(l:list)**

* Takes a small character string and shifts all characters by 5 (handleboundary conditions) tsai>>yxfn : 
**def str_shift(s:str)**

***3) A list comprehension expression that takes a ~200 word paragraph (write your own paragraph to check), and checks whether it has any of the swear words mentioned in https://github.com/RobertJGabriel/Google-profanity-words/blob/master/list.txt*** :
**def swear_checker(s:str)**

***4) Using reduce functions***

* Add only even numbers in a list :
**def add_even(l:list)**

* Find the biggest character in a string (printable ascii characters) : 
**def big_char(s:str)**

* Adds every 3rd number in a list : 
**def add_thirdnum(l:list)**

***5) Using randint, random.choice and list comprehensions, write an expression that generates 15 random KADDAADDDD number plates, where KA is fixed, D stands for a digit, and A stands for Capital alphabets. 10<<DD<<99 & 1000<<DDDD<<9999*** : 
**def ka_num_plate(n:int)**

***6) Write the above again from scratch where KA can be changed to DL, and 1000/9999 ranges can be provided*** : 
**def dl_num_plate(st_code:str, n:int, *args)**
