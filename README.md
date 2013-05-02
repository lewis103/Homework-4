Homework-4
==========
(1)
This problem was very interesting, however, was also very challenging for me. I spent a multitude of hours just 
trying to understand it and come up with the code to run some tests. Even though I was not able to completely run
the code I wanted I still made some interesting discoveries and hopefully gathered enough data and examples to make
a fairly educated conjecture. I began to notice a correlation between functions that produce prime numbers and 
whether that function can or can not be factored. With that I used, factor(), a lot while
working with this problem.

What I found:
It seems that functions such as (x^2+x) which can be factored will never produce a prime, in fact, (x^2+x)*(any x in Z)
will never return a prime number. I began exploring this route, testing functions that could be factored, however, I 
came upon the contradiction (x^2+5x+1) which can not be factored however it may produce a prime. 

It seems to me that there is definitely a correlation between a functions ability to be factored and there is also 
clearly a relationship between even and odd numbers as our integer coefficients. 



(2)
When plotting with n = 15 the primes consistently become more and more scarce as you approach the target number, 
in this case, 10^7. However, when I began running tests of other numbers things got interesting. I first tried n = 2 
and it produced exactly what I expecting the first bar slightly higher than the second. It is when I began running 
large numbers of n that something really caught my eye. The trend clearly slopes down, however, it is not consistent. 
There are what appears to be, inconsistent “spikes” in the data. After looking closer I came to the conjecture that 
as a trend the primes spread out, however, the exact pattern is random.

(3)
Your secret rational number is (1234567)/(8901234) 
