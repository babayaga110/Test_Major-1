# Test-_-Major_1

Question 1
Problem Statement: You have been given a string S of length N. The given string is a binary string
which consists of only 0’s and ‘1’s. Ugliness of a string is defined as the decimal number that this
binary string represents.
Example: “101” represents 5
“0000” represents 0
“01010” represents 10
There are two types of operations that can be performed on the given string:-
(1) Swap any two characters by paying a cost of A coins.
(2) Flip any character by paying a cost of B coins
Flipping a character means converting a ‘1’to a ‘0’or converting a ‘0’ to a ‘1’.
Initially, you have been given coins equal to the value defined in CASH. Your task is to minimize the
ugliness of the string by performing the above mentioned operations on it. Since the answer can be
very large, return the answer modulo 10^9+7.
Note: (1) You can perform an operation only if you have enough number of coins to perform it.
(2) After every operation the numbers of coins get deducted by the cost for that operation.
Input Format
 The first line contains an integer, N, denoting the number of character in the string
 The next line contains a string, S, denoting the binary string
 The next line contains an integer, CASH, denoting the total number of coins present initially
 Next will contains an integer, A, denoting the cost to swap two characters.
 Then the next line contains an integer, B, denoting the cost to flip a character.
Constraints
 1 <= N <= 10^5
 1<len(S)<= 10^5
 1<=CASH <=10^5
 1<=A<=10^5
 1<=B<=10^5

![image](https://user-images.githubusercontent.com/70019018/150628085-c0ded7b3-0d1f-4645-956b-5ed3738040c6.png)

![image](https://user-images.githubusercontent.com/70019018/150628092-46866efe-7b5c-4d79-b836-5ce154d10f4d.png)




Question 2:
Problem Statement:
One of the first lessons IT students learn is the representation of natural numbers in the binary number
system (base 2). This system uses only two digits, 0 and 1. In everyday life we use for convenience
the decimal system (base 10) which uses ten digits, from 0 to 9. In general, we could use any
numbering system.
Computer scientists often use systems based on 8 or 16. The numbering system based on K uses K
digits with a value from 0 to K-1. Suppose a natural number M is given, written in the decimal
system. To convert it to the corresponding writing in the system based on K, we successively divide
M by K until we reach a quotient that is less than K
The representation of M in the system based on K is formed by the final quotient (as first digit) and is
followed by the remainder of the previous divisions
For example:
 If M=122 and K=8, 122 in base 10= 172 in base 8 This means that the number
 In decimal system = 172 in octal system.
 172 in base 8 = 1*8^2 + 7*8 + 2 = 122
You made the following observation in applying the above rule of converting natural numbers to
another numbering system
 In some cases in the new representation all the digits of the number are the same. For
example 63 in base 10= 333 in base 4
Given a number M in its decimal representation, your task is find the minimum base B such that in the
representation of M at base B all digits are the same.
Input Format
 The first line contains an integer, M, denoting the number given
Constraints
 1 <= M = 10^12

![image](https://user-images.githubusercontent.com/70019018/150628055-6125afe3-8db2-4897-9f00-53992e0578f0.png)
