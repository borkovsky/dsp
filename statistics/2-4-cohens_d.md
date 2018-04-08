[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> 
def CohEffect (g1, g2):
    diff = g1.mean() - g2.mean()
    
    variance_1 = g1.var()
    variance_2 = g2.var()
    n1 = len(g1)
    n2 = len(g2)
    pooled_variance = (n1 * variance_1 + n2 * variance_2) / (n1 + n2)
    d = diff/ np.sqrt(pooled_variance)
    return d


