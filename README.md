# 2705_PalindromePartition

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/2705_PalindromePartition/blob/main/2705_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

Let x1 ,x2 , x3 , .. xn is PalindromePartition.

Then x 1 x , x 2 x , ... x n x will be PalindromePartition.

Thne dp[i/2] + dp[i/2 -1] + .... + 1 have the answer because we need right side and left side.

In this case dp[i-2] will have all values until dp[i/2] because we are keep summing up the values.

So dp[i/2] + dp[i-2] will gives you the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
