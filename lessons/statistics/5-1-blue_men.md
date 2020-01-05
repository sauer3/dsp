[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

### In order to join Blue Man Group, you have to be male between 5’10” and 6’1”. What percentage of the U.S. male population is in this range?
>> low = dist.cdf(177.8)
>> high = dist.cdf(185.4)
>> 
>> high-low
>>  
>> About 34 percent of the male population meet the height requirements for the blue man group. 
