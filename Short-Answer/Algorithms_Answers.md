Add your answers to the Algorithms exercises here.

1. (a) Linear
So the n^3 is confusing. You think it is high because of it.  However the
increment step is also big.

For every iteration the counter is incremented by n^2. So I would assume that
n^3 and a step of n^2 would be dropped and left with it taking n steps of
looping adding n^2 to reach n^3. So runtime is linear 0(n)

2. (b) quadratic
There are 4 nested loops. 3 of them are iterating over n. Two of the loops are
going over n + 1 and n + 1. Basically both are iterating on n. Fourth loop will
always iterate over ten items regardless of how big k is. That would make it
constant. Then we are left with O(n^3) runtime

3. (c) linear
Each time with the function the input value is reduced. When it hits 0 the
function with stop. So the function runs a number of times equal to input value.
O(n)

Section 2

We want to close in on the floor f. If we drop an egg and cut floors in half
based on < or > we should be able to narrow down our options much like binary
search eliminating a good chunk of floors. ex. start at middle. drop egg. if it
breaks f must be on the lower half. Move to middle of new section and drop egg.
each drop we eliminate half of remaning possibilities and based on low or high
can repeat until we find the floor f.  O(log(n))
