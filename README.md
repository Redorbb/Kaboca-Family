# Kaboca-Family
Kaboca Family of functions was introduced by a user known as Redorbb in 2025. These functions aim to explore extreme growth rates. The function name Kaboca, is derived from the Hungarian word for cicada, symbolizing rapid emergence and multiplication.

The Kaboca family has 4 functions: Realistic Kaboca, Realistic finalKaboca, Mathematical Kaboca, Mathematical finalKaboca. The realistic ones respect physical time limits such as Planck time, while the mathematical ones doesn't respect such constraints. Now let me tell you about these functions.

Kaboca is defined as Kaboca(t), where t is the time in hours, days or any preferred unit. For example Kaboca(24 hours) or Kaboca(1 week) represent the total number of Kabocas produced within that time under the rules defined below. So Writing Kaboca(1) means Kaboca(1 year)

**Note:** `The Kaboca function is an original concept created by the author. It is not derived from or based on any existing large naming systems including those of Jonathan Bowers or others! `

## Generation 1 - start
So we begin with a single Kaboca at generation `g = 1` .

Each Kaboca lays eggs according to the rule:

### Egg count
Each kaboca lays: ```10^(2^g)```
Where g is the generation number of the Kaboca.
So at generation 1: `10^(2^1) = 10^2 = 100 eggs`

### Lay times
Each Kaboca lays eggs `g` times. So gen 1, it lays eggs **once**.

### reproduction Time

Reproduction time = 24 hours / g

So for generation 1, the eggs hatch after 24 hours.

## Generation 2 - Hatching and probabilities
After 24 hours, 100 eggs laid by the first Kaboca hatch. Each egg independently follows a probability distribution to determine what type of Kaboca it becomes:

- 70% chance -> 10 Kaboca
- 25% chance -> 100 Kaboca
- 4% chance -> 1000 Kaboca
- 1% chance -> 1 super Kaboca
- 
**Estimated Output:** 7201 Kabocas total.

### Generation 2 behaviour
- Each lays `10^(2^2) = 10^4 = 10000 eggs`
- Lays eggs `g = 2` times
- reproduction time = `24 /2 = 12 hours`

## Super kabocas explanation:

First of all, these hatch chances aren't **fixed**, they shift the following way:

### Examples of shifting:

#### Generation 2 Hatches:

- 70% chance -> 10 Kaboca
- 25% chance -> 100 Kaboca
- 4% chance -> 1000 Kaboca
- 1% chance -> 1 super Kaboca
  
#### Generation 3:

- 70% chance -> 100 Kaboca
- 25% chance -> 1000 Kaboca
- 4% chance -> 1 super Kaboca
- 1% chance -> 10 super Kaboca

#### Generation 4:

- 70% chance -> 1000 Kaboca
- 25% chance -> 1 super Kaboca
- 4% chance -> 10 super Kaboca
- 1% chance -> 100 super Kaboca

#### Generation 5:

- 70% chance -> 1 super Kaboca
- 25% chance -> 10 super Kaboca
- 4% chance -> 100 super Kaboca
- 1% chance -> 1 super super Kaboca

#### Generation 6:

- 70% chance -> 10 super Kaboca
- 25% chance -> 100 super Kaboca
- 4% chance -> 1 super super Kaboca
- 1% chance -> 10 super super Kaboca

Now each super Kaboca gives 1 affine function which is f(x) = x + k where k is a natural number, and k > 1 and k <= 100, to one of the modifiers in the following order:

- egg count
- lay egg times
- Hatching
- reproduction time.
### Examples:

Lets say we have 6 super kabocas that hatched now each of them lays eggs. So they will each lay instead of `10^2^g` amount of eggs they will lay `F(x) = x + k` where `k > 1` and `k <=100` ! Which is `10^2^g + k` eggs.

Now what if we have a super super kaboca? It adds two F(x) = x + k functions to the followings:

- egg count (Same as super Kaboca)
- lay egg times

So a super super Kaboca will lay `10^2^g + k` amount of eggs and it will lay it `g + k` times. If its the 7th generation then it will lay it `7 + k` where k is between `2` and `100` !.

Super super super Kaboca or lets just say it as **super^3** Kaboca. It adds Three `F(x) = x + k` functions to the followings:

- egg count (Same as super Kaboca and super^2 Kaboca)
- lay egg times (Same as super^2 Kaboca)
- Hatching
  
#### Example for hatching :

lets say we are at generation 7 and these are the original chances

##### Generation 7:

- 70% chance -> 100 super Kaboca
- 25% chance -> 1 super super Kaboca
- 4% chance -> 10 super super Kaboca
- 1% chance -> 100 super super Kaboca

We get

##### Generation 7:

- 70% chance -> 100 + k super Kaboca
- 25% chance -> 1 + k super super Kaboca
- 4% chance -> 10 + k super super Kaboca
- 1% chance -> 100 + k super super Kaboca

**Super^4 Kaboca** this is where things will get rough. It gives four `f(x) = x + k` to

- egg count
- lay egg times
- hatching
- reproduction time

So here the first three is the same as for **Super^3 Kaboca** and for reproduction time instead of **24 / g** hours we will get **24 / (g + k)** hours.

**Super^5** Kaboca We give the four functions the same way as super^4 Kaboca but for the fifth function instead of `f(x) = x + k` we will add `f(x) = k * x` to the egg count, where **k is a natural number between 2 and 100** !

So our egg count here is `10^2^g + k` (from the first function) now it will be `F(x) = k * x` which is `(10^2^g + k ) * k` number of eggs!

Super^6 Kaboca Same function `F(x) = x * k` added to the lay egg times. So it looks something like this

- (egg count + k) * k
- (lay egg times + k) * k
- hatching + k
- reproduction time + k

### super^n Kabocass Function modifier behavior

#### super^7 Kaboca

- (egg count + k) * k
- (lay egg times + k) * k
- (hatching + k) * k
- reproduction time + k 

#### super^8 Kaboca

- (egg count + k) * k
- (lay egg times + k) * k
- (hatching + k) * k
- (reproduction time + k) * k

### super^9 Kaboca

This adds instead of a liner function it adds an exponential one. `F(x) = x^k` where **k is a natural number between 2 and 100**. Adds this function to the egg count. This is how it will look.

- ((egg count + k) * k)^k
- (lay egg times + k) * k
- (hatching + k) * k
- (reproduction time + k) * k

### Super^10 Kaboca

- ((egg count + k) * k)^k
- ((lay egg times + k) * k)^k
- (hatching + k) * k
- (reproduction time + k) * k

### Super^11 Kaboca

- ((egg count + k) * k)^k
- ((lay egg times + k) * k)^k
- ((hatching + k) * k)^k
- (reproduction time + k) * k

### Super^12 Kaboca
- ((egg count + k) * k)^k
- ((lay egg times + k) * k)^k
- ((hatching + k) * k)^k
- ((reproduction time + k) * k)^k

### Super^n Kaboca where n > 12

- **Super^13 Kaboca** gives a `tetration k times` to the egg count,
- **Super^14 Kaboca** gives an extra tetration to the lay egg count
- **Super^15 Kaboca** gives an extra tetration to the hatching
- **Super^16 Kaboca** gives an extra tetration to the reproduction time and so on

So each time a **super^n Kaboca** reaches the egg count again it gives a **much higher function** to it then before.

So starting from **super^17 Kaboca** will give **Pentation function, super^21 Kaboca** will give a **hyperoperation level**, **super^25 Kaboca Ackermann(x,x) probably, and so on.

**Note:** It always gives a higher level function but what it cannot give is `Busy Beaver`, `Tree` and `Rayo`. Everything else is allowed.

## Continue with our current generations
Lets continue where we left we were at generation 2! 24 hours. So we have
7200 Kabocas and 1 super Kaboca we will be focusing on them as different threads!

- First thread is 1 super Kaboca
- Second thread is 7200 Kaboca

### first thread:

Cuz that super kaboca changes only the egg count by k its really inrelevent at these numbers
So instead of 10^2^g it will hatch 10^2^g + k. Where k is a natural number and k >1 and k<=100
For future usages lets always use the smallest value for k which is 2. Just to minorize things!

### Second thread:

1. Each Lays `10^(2^2)` = `10^4` = `10000 eggs`
2. egg lay times = g = 2 (cuz we are at the second generation)
3. egg hatching probabilities for next generation will be

- 70% chance -> 100 Kaboca
- 25% chance -> 1000 Kaboca
- 4% chance -> 1 super Kaboca
- 1% chance -> 10 super Kaboca

4. reproduction time = 24/g = 24/2 = 12 hours

Knowing this generation 3 will hatch at the **36th hour**.

## Generation 3 (36 hour +):

The kaboca numbers are getting big so later I will use estimation instead an minoration! From the second thread(which is all normal Kabocas)
Total number of eggs that hatched is 144,000,000 from which we will get

- 0.7 *  144,000,000 * 100 Kaboca +
- 0.25 * 144,000,000 * 1000 Kaboca +
- 0.04 * 144,000,000 * 1 super Kaboca +
- 0.01 * 144,000,000 * 10 super Kaboca

10,080,000,000 + 36,000,000,000 + super Kabocas (5,760,000 + 14,400,000)

Its around `46 * 10^9` Kabocas total
### Egg and hatching time

1. egg count = 10^2^3 = 10^8 eggs
2. egg lay times = 3
3. egg hatching probabilities for next generation will be

- 70% chance -> 1000 Kaboca
- 25% chance -> 1 super Kaboca
- 4% chance -> 10 super Kaboca
- 1% chance -> 100 super Kaboca

4. reproduction time = 24/g = 24/3 = 8 hours

Knowing this the fourth generation will hatch at 36 + 8 = **44th** hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its  46 * 10^9 * 10^8 * 3 its around 1.3 * 10^19 eggs

## Generation 4

 It hatched around 0.7 * 1.3* 10^19 * 1000 + 0.25 * 1.3* 10^19 * 1 + 0.04 * 1.3* 10^19 * 10 + 0.01 * 1.3* 10^19 * 100 Kaboca variants.
 Lets minor things and use only 0.7 * 1.3 * 10^19 * 1000 for easier calculations.
 its value is around `9.1 * 10^21` Kabocas.

1. egg count = 10^2^4 = 10^16
2. egg lay times = 4
3. egg hatching probabilities for next generation will be
- 70% chance -> 1 super Kaboca
- 25% chance -> 10 super Kaboca
- 4% chance -> 100 super Kaboca
- 1% chance -> 1 super super Kaboca

4. reproduction time = 24/g = 24/4 = 6 hours

So the next generation will hatch at 44 + 6 = **50th** hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its  9.1 * 10^21 Kabocas * 10^16 egg count * 4

## Generation 5

It hatched around 36 * 10^37 Kaboca variants from which we likely have 36 *10^35 super^2 kabocas
We know that it not just modifies the egg count it also modifies the egg lay times as well.
Here we get the egg lay counts modified
So instead of egg lay count = g =5 we get egg lay count = g+k = 7
This multiplier doesnt affect our huge numbers much yet, so lets continue on the normal way!

1. egg count = 10^2^5 = 10^32
2. egg lay times = 5 (we threat super^2 kabocas now as the same as normal ones cuz they don't affect our big numbers much YET)
3. egg hatching probabilities for next generation will be
- 70% chance -> 10 super Kaboca
- 25% chance -> 100 super Kaboca
- 4% chance -> 1 super super Kaboca
- 1% chance -> 10 super super Kaboca

4. reproduction time = 24/g = 24/5 = 4.8 hours

So the next generation will hatch at 50 + 4.8 = **54.8**th hour
total layed eggs = total number of Kabocas * egg count * egg lay times
its 36 * 10^37 * 10^32 * 5 = 1.8 * 10^71

## Generation 6

It hatched `1.8 * 10^71` eggs
0.7 * 10 * 10^71 + 0.25 * 100 * 10^71 + 0.04 * 1 * 10^71 +0.01 * 10 * 10^71
it around `2.5 * 10^73` Kabocas

1. egg count = 10^64
2. egg lay times = 6
3. egg hatching probabilities for next generation will be
- 70% chance -> 100 super Kaboca
- 25% chance -> 1 super^2 Kaboca
- 4% chance -> 10 super^2 Kaboca
- 1% chance -> 100 super^2 Kaboca

4. reproduction time = 24/g = 24/6 = 4 hours

So the next generation will hatch at **58.8th** hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
its 2.5 * 10^73 * 10^64 * 6 = `1.5 * 10^138`

## Generation 7

it hatched 1.5* 10^138 eggs at 58.8th hour!
we get here around 0.7 * 100 *  1.5* 10^138 +  0.25 * 1 *  1.5* 10^138 +  0.04 * 10 *  1.5* 10^138 +  0.01 * 100 *  1.5* 10^138
its approx 1.06 * 10^140 Kaboca variants. Lets minorize it to 10^140 for easier calculations

1. egg count = 10^128
2. egg lay times = 7
3. egg hatching probabilities for next generation will be
- 70% chance -> 1 super^2 Kaboca
- 25% chance -> 10 super^2 Kaboca
- 4% chance -> 100 super^2 Kaboca
- 1% chance -> 1 super^3 Kaboca

4. reproduction time = 24/g = 24/7 = 3.43 hours

So the next generation will hatch at **62.23th** hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
10^140 * 10^128 * 7 = 7 * 10^268

## Generation 8

it hatched 7 * 10^268 eggs at 62.23th hour!
we get here around 6.5 * 7 * 10^268 Kabocas
We here have a new variant which is `super^3` Kaboca.
It gives a modifier function to the egg hatching numbers
So its next generation instead of 

- 70% chance -> 10 super^2 Kaboca
- 25% chance -> 100 super^2 Kaboca
- 4% chance -> 1 super^3 Kaboca
- 1% chance -> 10 super^3 Kaboca

we will have 

- 70% chance -> 10 + k super^2 Kaboca
- 25% chance -> 100 + k super^2 Kaboca
- 4% chance -> 1 + k super^3 Kaboca
- 1% chance -> 10 + k super^3 Kaboca

This doesn't affect to much Yet, cuz the function is weak. So lets continue cuz soon things will get explode!
1. egg count = 10^256
2. egg lay times = 8
3. egg hatching probabilities for next generation will be
- 70% chance -> 10 super^2 Kaboca
- 25% chance -> 100 super^2 Kaboca
- 4% chance -> 1 super^3 Kaboca
- 1% chance -> 10 super^3 Kaboca

4. reproduction time = 24/g = 24/8 = **3** hours

So the next generation will hatch at **65.23th** hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
4.5 * 10^269 * 10^256 * 8 = 3.6 * 10^526

## Generation 9

it hatched 3.6 * 10^526 eggs
Our Kabocas esitamate is 3.6 * 10^528.

1. egg count = 10^512
2. egg lay times = 9
3. egg hatching probabilities for next generation will be
- 70% chance -> 100 super^2 Kaboca
- 25% chance -> 1 super^3 Kaboca
- 4% chance -> 10 super^3 Kaboca
- 1% chance -> 100 super^3 Kaboca

4. reproduction time = 24/g = 24/9 = **2.67** hours

So the next generation will hatch at **67.9th** hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
3.6 * 10^528 * 10^512 * 9 = 3.24 * 10^1040

## Generation 10

it hatched 3.24 * 10^1040 eggs
Our Kabocas esitamate is 2.55 * 10^1042 .

1. egg count = 10^1024
2. egg lay times = 10
3. egg hatching probabilities for next generation will be
- 70% chance -> 1 super^3 Kaboca
- 25% chance -> 10 super^3 Kaboca
- 4% chance -> 100 super^3 Kaboca
- 1% chance -> 1 super^4 Kaboca

4. reproduction time = 24/g = 24/10 = **2.4** hours

So the next generation will hatch at **70.3th** hour.
total layed eggs = total number of Kabocas * egg count * egg lay times
2.55 * 10^1042 * 10^1024 * 10 = 2.55 * 10^2067

## Generation 11 (here things will start a bit accelerating)

it hatched 10^2067 eggs
Now 1% of them will be super^4 kaboca estimated value around `10^2065`!
Now we will be focusing only on this thread and leave the other thread behind. Why? Not because its irreleveant because we will hatch multiple generations **before** the other super^3 (99%) kabocas eggs hatch!
this super^4 Kaboca will amplify the reproduction count so each generation will come faster!
instead of

- reproduction count = 24/g

we will have

- reproduction count = 24/ g + k

which is 24/13 instead of 24/11. They hatch faster so they start their jobs earlier.

1. egg count = 10^2048
2. egg lay times = 11
3. egg hatching probabilities for next generation will be
- 70% chance -> 10 super^3 Kaboca
- 25% chance -> 100 super^3 Kaboca
- 4% chance -> 1 super^4 Kaboca
- 1% chance -> 10 super^4 Kaboca

4. reproduction time = 1.85 hours.

So the next generation will hatch at **72.15th** hour. (A bit more then 3 days) instead of **72.48th** hour.
total layed eggs = 1.1 * 10^4113 eggs

## Generation 12
it hatched 1.1 * 10^4113 eggs
Our Kaboca estimate is around 3 * 10^4114

1. egg count = 10^4096
2. egg lay times = 12
3. egg hatching probabilities for next generation will be
- 70% chance -> 100 super^3 Kaboca
- 25% chance -> 1 super^4 Kaboca
- 4% chance -> 10 super^4 Kaboca
- 1% chance -> 100 super^4 Kaboca

4. reproduction time = 24/g = 24/14 = **1.71** hours
Next will hatch in = **73.86th** hour.
total eggs layed = 3.6 * 10^8211 eggs

## Generation 13

Hatched = `3.6 * 10^8211 eggs`
Kaboca estimate = 2.55 * 10^8213

1. egg count = 10^8192
2. egg lay times = 13
3. egg hatching probabilities for next generation will be
- 70% chance -> 1 super^4 Kaboca
- 25% chance -> 10 super^4 Kaboca
- 4% chance -> 100 super^4 Kaboca
- 1% chance -> 1 super^5 Kaboca

4. reproduction time = 24/g = 24/10 = **1.6** hours
Next will hatch in = **75.46th** hour.
total eggs layed = 2.75 * 10^16405

Now as we can see here we added super^5 Kaboca. this modifies the egg count
Instead of 10^8192 + k it will lay (10^(8192) + k) * k which is (10^8192 + 2) * 2 cuz we said above we use the smalles value for k which is 2.
As we can see the number of Kabocas power is likely doubleing a bit more then doubleing bt lets just say its doubleing. So because we don't have strong functions yet like exponentials, tetration etc
we will move along with the generation and estimating its value conform this easier rule only writing down the necessary information. until we reach something bigger.
Also when we reach the next power of superKaboca it takes around 3 generations. So the next one will appear at Generation 16 the other one at generation 19 the other at 22 and so on.

## Generation 14
1. Kaboca number = 10^16407.
2. egg count = 10^16384
3. reproduction time = 24/16 = 1.5 hours
4. Next hatch in **76.96th hour**
5. total eggs layed =  10 ^ 32791

## Generation 15
1. Kaboca number = 10^32815.
2. egg count 10^32768
3. reproduction time = 24/17 = 1.41 hours
4. Next hatch in **78.37th hour**
5. total eggs layed =  10 ^ 65,583

## Generation 16
1. Kaboca number = 10 ^ 65,585.
2. egg count 10^65536
3. reproduction time = 24/18 = 1.33 hours
4. Next hatch in **79.7th hour**
5. total eggs layed =  10 ^ 131,121
6. Function added = F(x) = k * x to the lay times

lets sonsider 131,121 power as our current value the next generation will double it the other one will quaddripple it and so on. So when the next super comes in to bring our new function we can say that
131,121 * 4 which is `1,048,968`!

## Generation 19
1. Kaboca number = 10^524,484
2. egg count 10^2^19
3. reproduction time = 1.14
4. next hatch = **83.3th hour**
5. total eggs layed = 10^2^20
6. function added = F(x) = k * x to the hatching numbers

## Generation 22
1. Kaboca **Power** number = 4,195,872
2. egg count **Power** number = 4,194,304
3. function added = F(x) = k * x to the reproduction time
4. reproduction time = 24/((22 + k)*k) = 0.5 hours
5. next hatch = 83.3 + 1.09 + 1.04 + 0.5 = **85.9th hour**
6. total layed **Power** number = 8,390,176

## Generation 25 (where start to explode)
1. Kaboca **Power** number = 33,566,976
2. egg count **Power** number = 33,566,976^k (because of a polinominal function defined below)
3. function added = F(x) = x^k to the egg count (polynominal function) 
4. reproduction time = 24/((25 + k)*k) = 0.44 hours
5. next hatch = 85.9 + 0.48 +0.46 + 0.44 = **87.28th hour**
6. total layed **Power** number = 33,554,432^k

Now lets check the next one how this affects our egg count now
## 87.28th hour

### Generation 26 hatched 
Because of F(x) = x^k to the egg count (polynominal function) added by the next tier super Kaboca, we layed
10^1.1258999e+15 number of eggs its egg power count is = 1.12 *10^15 = 10^(1.12*10^15) Kabocas were borned.
Our polinominal function starts to take effect now.

1. Kaboca **Power** number = 1.12 *10^15
2. egg count = (10^2^g)^k = (10^2^g)^2 = 2.3 * 10^15 eggs

Now lets see what happens if we add this polynominal function to the egg lay times. Instead of (g + k)*k we will have ((g + k) * k)^2
It doesnt effect these huge power much. The same goes to the egg Hatches. But what if we again reach the reproduction rate? Then things will explode immenseliy

At Generation 32 we will reach the reproduction rate again with the polinominal function. So this what will happen!

1. reproduction time = 0.363 hours
2. next hatch time = **89.65th hour**

## 89.65th hour
it is 322,740 seconds. Here we will have a very huge number already but at just 322741 seconds (1 second more we will gonna have `5.391 * 10^44 Generations`!
Remember we defined this functions parameter as a time not a constant! So that 1 second is gonna give us 10^44 generations!

This is the `realistic Kaboca function` meaning its reproduction time is physically limited and cannot go below planck time. If we allowed reproduction time to drop below this limit, the function would converge toward
infinity in a single second- producing inifinite number of generations. That's why we threat Planck time as the ultimate lower bound, keeping the growth finite but still unimaginably fast!

**Now think about this:** we reach **32 generations** at second **322,740**, and just *one second later*, we explode to over **10⁴⁴ generations**.

From this we can deduce two important patterns:

1. Every **3 generations** yields a new tier of **Super Kaboca** — each adding more modifiers to the function.
2. Every **12 generations** unlocks a **higher-level function** (affine → multiplicative → exponential → tetration → pentation → …).

This means that in the span of *just one second*, the entire functional structure accelerates up the hyperoperation ladder, eventually reaching levels that surpass even functions like **TREE(n)** for finite _n_. This growth is not just fast — it’s explosive beyond comprehension.

**Also, we haven't even reached the 90th hour yet.**  
So what about `Kaboca(1 week)` or even `Kaboca(1 year)`?

This function grows at **super-fast** rates — far beyond traditional large number systems.  
It evolves not just by scale, but by the **acceleration of function complexity**, reaching unimaginable heights with each generation.

**Kaboca is not just a number — it's a process of exponential explosions stacked on evolving operations.**

## Evolution functions and generations

### Evolution functions
Everything here has an order. Even functions that we apply that has an order, but they also evolving as well. Also evolution of them evolves as well.
#### Recap
At every 12 generations we always add one level higher function to it. So these will be the followings:
At Generation 2 Hatches we get likely around 1 super Kaboca. This adds a f(x) = x + k to the egg lay count.
- At generation 5 it adds it adds it to the lay egg times.
- At generation 8 adds it at Hatching numbers.
- At generaation 11 adds it to the reproduction time.


At generation 11 all 4 Kaboca components (lay egg count,lay egg times, hatching numbers,reproduction time) will have F(x) = x + k with them. The next generations will carry these functions with them. They will look something like this:
- egg lay count = x^2^g + k
- egg lay times = g + k
- hatching numbers = (Numbers per the chances) + k
- reproduction time = 24 / (g+k)

At generation 23 all components will receive F(x) = k*x so they will look like this
- egg lay count = k* (x^2^g + k)
- egg lay times = k*(g + k)
- hatching numbers = k*((Numbers per the chances) + k)
- reproduction time = 24 / k*(g+k)

Lets use Kaboca Components from now on. So the first Component refers to `egg lay count`, the second Component refers to `egg lay times` etc.

At generation 35 we will add F(x) = X^K function to our existing expression so it will look something like
- Kaboca Komponents = (k * (x + k))^k

At generation 47 we will have F(x) = k^x
- Kaboca Komponents = k^((k * (x + k))^k)

So you mught be asking, what is the sequence. Which functions we will give at every 12 generations to our expressions? I will show you a detailed order.

### Order of the functions and their evolution
Lets consider k=2 the smallest value so this is the order.

1. F(x) = x + k (affine)
2. F(x) = k*x (multiplicative)
3. F(x) = x^k (power function)
4. F(x) = k^x (exponential function)
5. F(x) = k ↑ ↑ x (tetration)
6. F(x) = k ↑ ↑ ↑ x (pentation)
7. F(x) = k ↑ ↑ ↑ ↑ x (hexation)

So our expression at 12 * 7 = 84th generation our first Kaboca Component will look something like this:
k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x+k))^k. This expression keeps going and growing at every 12 generations.
Lets call this expression R. This R means Rest. So the entire expression till now.
After these, 7 functions written above, the function will evolve. Instead of going one operation it will go the following way:

8.  F(x) = hyper_{6+k}(k,x)
9.  F(X) = hyper_{k*(6+k)}(k,x)
10. F(X) = hyper_{(k*(6+k))^k}(k,x)
11. F(X) = hyper_{k^((k*(6+k))^k)}(k,x)
12. F(X) = hyper_{k ↑ ↑ k^((k*(6+k))^k)}(k,x)
13. F(X) = hyper_{k ↑ ↑ ↑ (k ↑ ↑ k^((k*(6+k))^k))}(k,x)
14. F(X) = hyper_{k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(6+k))^k)))}(k,x)

As you can see the say functions are applied here as the first in the first ones, but they are putted on the index of the hyper function. So Our first Kaboca Komponent at generation 168 will look something like this
- egg count =  hyper_{k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(6+k))^k)))}(k,R)
- where R is k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x+k))^k
- and x is 10^2^g = 10^2^168

So our final expression will look something like this
hyper_{k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(6+k))^k)))}(k , k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(10^2^168+k))^k)

After this evolution takes place again and instead of putting the hyper in the index, we will put hyper to the index of the index. Nest it one moree time

15.  F(x) = hyper_{hyper_{6+k}(k,x)}(k,x)
16.  F(x) = hyper_{hyper_{k*(6+k)}(k,x))}(k,x)
17.  F(x) = hyper_{hyper_{(k*(6+k))^k}(k,x)}(k,x)
18.  **And so on**

Every 7th function addings which is 84 generations, we will evolving our function. What this is tell us we have more then 10^44 generation around 90th hour.
So we aren't gonna do all that instead we are gonna use a weaker function, a generation version of Kaboca, instead of the time paramater for now. Just to estimate where these numbers stand
We will call this KabocaG function where G refers to the generation number.

#### Evolution of evolution
We know now that every 7th (84 generations) adds an evolution. So our evolution/84 generations the added functions will look something like this:

1. F(x) = x + k evolution level (1)
2. F(x) = hyper_{6+k}(k,x) evolution level (2)
3. F(x) = hyper_{hyper_{6+k}(k,x)}(k,x) evolution level (3)
4. F(x) = hyper_{hyper_{hyper_{6+k}(k,x)}(k,x)}(k,x) evolution level (4)
5. F(x) = hyper_{hyper_{hyper_{hyper_{6+k}(k,x)}(k,x)}(k,x)}(k,x) evolution level (5)
6. F(x) = hyper_{hyper_{hyper_{hyper_{hyper_{6+k}(k,x)}(k,x)}(k,x)}(k,x)}(k,x) evolution level (6)
7. F(x) = hyper_{hyper_{hyper_{hyper_{hyper_{hyper_{6+k}(k,x)}(k,x)}(k,x)}(k,x)}(k,x)}(k,x) evolution level(7)

This is where things explode even stronger. We Reached 7 evolutions. After the seventh evolution the evolution will have an evolution. So each evolution now gives the following functions/evolution to our R the following way:

8. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is x + k times. evolution level(8)
9. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is k*(x + k) times. evolution level(9)
10. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is (k*(x + k))^k times. evolution level(10)
11. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is k^((k*(x + k))^k) times. evolution level(11)
12. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is k ↑ ↑ k^((k*(x + k))^k) evolution level(12)
13. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x + k))^k)) evolution level(13)
14  hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x + k))^k))) evolution level(14)

At 15 evolves again and continus the following way

15. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is hyper_{6+k}(k,x) where x will be k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x + k))^k)))
16. hyper_{hyper_hyper ... hyper{R}(k,R) total number of hypers is hyper_{k*(6+k)}(k,x) where x will be k ↑ ↑ ↑ ↑ (k ↑ ↑ ↑ (k ↑ ↑ k^((k*(x + k))^k)))
17. **And so on**

We are here now at lets say 15 evolution and around 1260 generations. KabocaG(1260). this is extremely huge number already and we are very far from 10^44(next second) and way far from Kaboca(90hours) and
even way way far from Kaboca(1) = Kaboca (1 year).

### Generation estimations
It keeps growing and growing but not as a constant as an evolving function. Where evolution itself evolves as well.
So how big is this number?

1. It passed G1 at KabocaG(74) (74th generation)
2. G2 is surpassed at KabocaG(86)
3. G10 falls at KabocaG(122)
4. surpasses Grahams number at KabocaG(158)
5. Surpasses Tree(3) around KabocaG(254-266)
6. Around KabocaG(300) surpasses BB(8)
7. Around KabocaG(10000) surpasses Tree(1000)
8. Around KabocaG(100000) >> Tree(Tree(4))

Why it grows so fast? Its a hypertransfinite growth, cuz each 84 generations makes 1 evolution. Each 84*7 evolves the evolution itself. Each 84*7^2 evolves the evoltutions evolution and so on.

## Final Kaboca
