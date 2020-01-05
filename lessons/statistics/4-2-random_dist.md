[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> ## Generate 1000 random numbers and plot PMF. What goes wrong?
pmf = thinkstats2.Pmf(np.random.random(1000))
thinkplot.Pmf(pmf)
thinkplot.Config(xlabel='Random variable', ylabel='PMF')

there is too much noise to see any pattern.
>> ## Plot the CDF
cdf = thinkstats2.Cdf(np.random.random(1000))
thinkplot.Cdf(cdf)
thinkplot.Config(xlabel='Random variable', ylabel='CDF')

The distribution is uniform.
