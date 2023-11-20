Expected number of rolls until I see 6 (or whatever other fixed value).
## Solution
Let’s
1. 
$$ 
P(N=i)=\frac{1}{6}*(\frac{5}{6})^{i-1}
$$

Then answer Is 
$$
\sum_{n=1}^{\infty} n \cdot P(N=n) = \frac{1}{6} \sum_{n=1}^{\infty} (\frac{5}{6})^n
$$

### Trick
$$
\sum_{n=1}^{\infty} n \cdot r^{n} = r \cdot \sum_{n=1}^{\infty} n \cdot r^{n-1} = 
r \frac{d}{dr}\sum_{n=1}^{\infty} r^{n} = 
r \cdot \frac{d}{dr} \left(\frac{1}{1-r}\right) = 


$$