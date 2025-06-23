# Kaboca-Family
A mathematical function that outgrows any famous numbers and functions
Generation 1 start
So we begin with a single Kaboca at generation g = 1 .

Each Kaboca lays eggs according to the rule:

Egg count = 10^(2^g)

Where g is the generation number of the Kaboca.

Each Kaboca lays eggs g times during its generation. So at generation 1, the Kaboca lays eggs once.

Thus the first Kaboca lays:

1 x 10^(2^1) = 1 x 100 = 100 eggs.

These eggs hatch after a reproduction delay given by:

Reproduction time = 24 hours / g

So fo generation 1, the eggs hatch after 24 hours.

Generation 2 - Hatching and probabilities
After 24 hours, 100 eggs laid by the first Kaboca hatch. Each egg independently follows a probability distribution to determine what type of Kaboca it becomes:

Generation 2 hatch chances:

70% chance -> 10 Kaboca
25% chance -> 100 Kaboca
4% chance -> 1000 Kaboca
1 % chance -> 1 super Kaboca
So total if we follow the estimation: We get 7201 Kabocas.

Now, each of these 7200 of them begins to lay eggs:

Each Lays 10^(2^2) = 10^4 = 10000 eggs

Lays eggs g = 2 times

Has a reproduction time = 24/2 = 12 hours

Super kabocas explanation:

First of all, these hatch chances aren't fixed, they shift the following way:

Examples of shifting:

Generation 2:

70% chance -> 10 Kaboca
25% chance -> 100 Kaboca
4% chance -> 1000 Kaboca
1 % chance -> 1 super Kaboca
Generation 3:

70% chance -> 100 Kaboca
25% chance -> 1000 Kaboca
4% chance -> 1 super Kaboca
1 % chance -> 1 0 super Kaboca
Generation 4:

70% chance -> 1000 Kaboca
25% chance -> 1 super Kaboca
4% chance -> 10 super Kaboca
1 % chance -> 100 super Kaboca
Generation 5:

70% chance -> 1 super Kaboca
25% chance -> 10 super Kaboca
4% chance -> 100 super Kaboca
1 % chance -> 1 super super Kaboca
Generation 6:

70% chance -> 10 super Kaboca
25% chance -> 100 super Kaboca
4% chance -> 1 super super Kaboca
1 % chance -> 10 super super Kaboca
Now each super Kaboca gives 1 affine function which is f(x) = x + k where k is a natural number, and k > 1 and k <= 100, to one of the modifiers in the following order:

egg count
lay egg times
Hatching
reproduction time.
Examples:

Lets say we have 6 super kabocas that hatched now each of them lays eggs. So they will each lay

instead of 10^2^g amount of eggs they will lay F(x) = x + k where k > 1 and k <=100! Which is 10^2^g + k eggs.

Now what if we have a super super kaboca? It adds two F(x) = x + k functions to the followings:

egg count (Same as super Kaboca)
lay egg times
So a super super Kaboca will lay 10^2^g + k amount of eggs and it will lay it g + k times. If its the 7th generation then it will lay it 7 + k where k is between 2 and 100 times.

Super super super Kaboca or lets just say it as super^3 Kaboca. It adds Three F(x) = x + k functions to the followings:

egg count (Same as super Kaboca and super^2 Kaboca)
lay egg times (Same as super^2 Kaboca)
Hatching
Example for hatching :

lets say we are at generation 7 and these are the original chances

Generation 7:

70% chance -> 100 super Kaboca
25% chance -> 1 super super Kaboca
4% chance -> 10 super super Kaboca
1 % chance -> 100 super super Kaboca

We get

Generation 7:

70% chance -> 100 + k super Kaboca
25% chance -> 1 + k super super Kaboca
4% chance -> 10 + k super super Kaboca
1 % chance -> 100 + k super super Kaboca
Super^4 Kaboca this is where things will get rough. It gives four f(x) = x + k to

egg count
lay egg times
hatching
reproduction time
So here the first three is the same as for Super^3 Kaboca and for reproduction time instead of 24 /g hours we will get 24/ (g + k) hours.

Super^5 Kaboca We give the four functions the same way as super^4 Kaboca but for the fifth function instead of f(x) = x + k we will add f(x) = k * x to the egg count, where k is a natural number between 2 and 100!

So our egg count here is 10^2^g + k (from the first function) now it will be F(x) = k * x which is (10^2^g + k ) * k number of eggs!

Super^6 Kaboca Same function F(x) = x * k added to the lay egg times. So it looks something like this

(egg count + k) * k
(lay egg times + k) * k
hatching + k
reproduction time + k
super^7 Kaboca

(egg count + k) * k
(lay egg times + k) * k
(hatching + k) * k
reproduction time + k
super^8 Kaboca

(egg count + k) * k
(lay egg times + k) * k
(hatching + k) * k
(reproduction time + k) * k
super^9 Kaboca

This adds instead of a liner function it adds an exponential one. F(x) = x^k where k is a natural number between 2 and 100. Adds this function to the egg count. This is how it will look.

((egg count + k) * k)^k
(lay egg times + k) * k
(hatching + k) * k
(reproduction time + k) * k
Super^10 Kaboca

((egg count + k) * k)^k
((lay egg times + k) * k)^k
(hatching + k) * k
(reproduction time + k) * k
Super^11 Kaboca and Super^12 Kaboca

((egg count + k) * k)^k
((lay egg times + k) * k)^k
((hatching + k) * k)^k
(reproduction time + k) * k
((egg count + k) * k)^k
((lay egg times + k) * k)^k
((hatching + k) * k)^k
((reproduction time + k) * k)^k
Super^13 Kaboca gives a tetration k times to the egg count, Super^14 Kaboca gives an extra tetration to the lay egg count and so on.

So each time a super^n Kaboca reaches the egg count again it gives a much higher function to it then before.

So starting from super^17 Kaboca will give Pentation function, super^21 Kaboca will give a hyperoperation level, super^25 Kaboca Ackermann(x,x) and so on.

Note: It always gives a higher level function but what it cannot give is Busy Beaver, Tree and Rayo. Everything else is allowed.

#Continue with our current generations#
Lets continue where we left we were at generation 2! 24 hours. So we have
7200 Kabocas and 1 super Kaboca we will be focusing on them as different threads!
First thread is 1 super Kaboca
Second thread is 7200 Kaboca

##first thread:
Cuz that super kaboca changes only the egg count by k its really inrelevent at these numbers
So instead of 10^2^g it will hatch 10^2^g + k. Where k is a natural number and k >1 and k<=100
For future usages lets always use the smallest value for k which is 2. Just to minorize things!

##Second thread:
Each Lays 10^(2^2) = 10^4 = 10000 eggs
egg lay times = g = 2 (cuz we are at the second generation)
egg hatching probabilities for next generation will be
70% chance -> 100 Kaboca
25% chance -> 1000 Kaboca
4% chance -> 1 super Kaboca
1% chance -> 10 super Kaboca
reproduction time = 24/g = 24/2 = 12 hours

Knowing this generation 3 will hatch at the 36th hour.

#Generation 3 (36 hour +):
The kaboca numbers are getting big so later I will use estimation instead an minoration!
From the second thread(which is all normal Kabocas)
Total number of eggs that hatched is 144,000,000 from which we will get
0.7 *  144,000,000 * 100 Kaboca +
0.25 * 144,000,000 * 1000 Kaboca +
0.04 * 144,000,000 * 1 super Kaboca +
0.01 * 144,000,000 * 10 super Kaboca

10,080,000,000 + 36,000,000,000 + super Kabocas (5,760,000 + 14,400,000)

Its around 46 * 10^9 Kabocas total
##Egg and hatching time##

egg count = 10^2^3 = 10^8 eggs
egg lay times = 3
egg hatching probabilities for next generation will be
70% chance -> 1000 Kaboca
25% chance -> 1 super Kaboca
4% chance -> 10 super Kaboca
1% chance -> 100 super Kaboca
reproduction time = 24/g = 24/3 = 8 hours

Knowing this the fourth generation will hatch at 36 + 8 = 44th hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its  46 * 10^9 * 10^8 * 3 its around 1.3 * 10^19 eggs

#Generation 4
 It hatched around 0.7 * 1.3* 10^19 * 1000 + 0.25 * 1.3* 10^19 * 1 + 0.04 * 1.3* 10^19 * 10 + 0.01 * 1.3* 10^19 * 100 Kaboca variants.
 Lets minor things and use only 0.7 * 1.3 * 10^19 * 1000 for easier calculations.
 its value is around 9.1 * 10^21 Kabocas

egg count = 10^2^4 = 10^16
egg lay times = 4
egg hatching probabilities for next generation will be
70% chance -> 1 super Kaboca
25% chance -> 10 super Kaboca
4% chance -> 100 super Kaboca
1 % chance -> 1 super super Kaboca
reproduction time = 24/g = 24/4 = 6 hours

So the next generation will hatch at 44 + 6 = 50th hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its  9.1 * 10^21 Kabocas * 10^16 egg count * 4

#Generation 5
It hatched around 36 * 10^37 Kaboca variants from which we likely have 36 *10^35 super^2 kabocas
We know that it not just modifies the egg count it also modifies the egg lay times as well.
Here we get the egg lay counts modified
So instead of egg lay count = g =5 we get egg lay count = g+k = 7
This multiplier doesnt affect our huge numbers much yet, so lets continue on the normal way!

egg count = 10^2^5 = 10^32
egg lay times = 5 (we threat super^2 kabocas now as the same as normal ones cuz they don't affect our big numbers much YET)
egg hatching probabilities for next generation will be
70% chance -> 10 super Kaboca
25% chance -> 100 super Kaboca
4% chance -> 1 super super Kaboca
1 % chance -> 10 super super Kaboca
reproduction time = 24/g = 24/5 = 4.8 hours

So the next generation will hatch at 50 + 4.8 = 54.8th hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its 36 * 10^37 * 10^32 * 5 = 1.8 * 10^71

#Generation 6
It hatched 1.8 * 10^71 eggs
0.7 * 10 * 10^71 + 0.25 * 100 * 10^71 + 0.04 * 1 * 10^71 +0.01 * 10 * 10^71
it around 2.5 * 10^73 Kabocas

egg count = 10^64
egg lay times = 6
egg hatching probabilities for next generation will be
70% chance -> 100 super Kaboca
25% chance -> 1 super^2 Kaboca
4% chance -> 10 super^2 Kaboca
1 % chance -> 100 super^2 Kaboca
reproduction time = 24/g = 24/6 = 4 hours

So the next generation will hatch at 58.8th hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
its 2.5 * 10^73 * 10^64 * 6 = 1.5 * 10^138

#Generation 7
it hatched 1.5* 10^138 eggs at 58.8th hour!
we get here around 0.7 * 100 *  1.5* 10^138 +  0.25 * 1 *  1.5* 10^138 +  0.04 * 10 *  1.5* 10^138 +  0.01 * 100 *  1.5* 10^138
its approx 1.06 * 10^140 Kaboca variants. Lets minorize it to 10^140 for easier calculations

egg count = 10^128
egg lay times = 7
egg hatching probabilities for next generation will be
70% chance -> 1 super^2 Kaboca
25% chance -> 10 super^2 Kaboca
4% chance -> 100 super^2 Kaboca
1 % chance -> 1 super^3 Kaboca
reproduction time = 24/g = 24/7 = 3.43 hours

So the next generation will hatch at 62.23th hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
10^140 * 10^128 * 7 = 7 * 10^268

#Generation 8
it hatched 7 * 10^268 eggs at 62.23th hour!
we get here around 6.5 * 7 * 10^268 Kabocas
We here have a new variant which is super^3 Kaboca.
It gives a modifier function to the egg hatching numbers
So its next generation instead of 

70% chance -> 10 super^2 Kaboca
25% chance -> 100 super^2 Kaboca
4% chance -> 1 super^3 Kaboca
1 % chance -> 10 super^3 Kaboca

we will have 

70% chance -> 10 + k super^2 Kaboca
25% chance -> 100 + k super^2 Kaboca
4% chance -> 1 + k super^3 Kaboca
1 % chance -> 10 + k super^3 Kaboca

This doesn't affect to much Yet, cuz the function is weak. So lets continue cuz soon things will get explode!

