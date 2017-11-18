# tlehman's jupyter notebooks 
## Inclusive Institutions

After reading [Why Nations Fail](http://whynationsfail.com/summary/) by Daron Acemoglu and James 
Robinson, I wanted to look at some data to check the thesis of the book. I summarize their thesis
as:

> Inequality between nations can be explained mostly by differences in the inclusiveness of 
> their economic and political institutions.

The two kinds of institutions they mention, economic and political, demand different measures. 
For political institutions, I chose the [Democracy Index](https://en.wikipedia.org/wiki/Democracy_Index), where the lowest values (< 4) correspond to authoritarian countries, and the highest scores 
(>= 8) correspond to full democracies. For the record, the U.S. is at 7.98, which means it is 
categorized as a flawed democracy, not a full democracy.

For economic institutions, the authors used "inclusive economic institutions" to mean that 
individuals can own property, and that intellectual property rights are secure, that's a central 
part of their thesis, that allowing individuals to protect their ideas creates incentives for 
people to innovate. This is very closely related to the [Index of Economic Freedom](https://en.wikipedia.org/wiki/Index_of_Economic_Freedom). 

We will use the Democracy Index (0 - 10) and the Index of Economic Freedom (0 - 100), normalized 
to the range (0 - 1), then multiplied together, to represent "economic and political inclusivity".

Then, we will use per-capita GDP (at purchasing-power parity) as the measure of the how rich 
people of that country are. Please keep in mind these are proxies for the relavant variables, 
but that this sort of analysis is far better than just agreeing or disagreeing with the thesis 
based on your subjective response to the book's 
arguments. If these two variables turn out to be uncorrelated, we can pretty much reject the book
outright. Otherwise, we should engage the arguments and study the limits of the theory.
