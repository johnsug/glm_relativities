# glm_relativities

In my prior life as a health actuary, we created rating factors using the "pure premium" method, eg, divided total claims by total exposure, with no regard for correlated variables.  P&C actuaries, however, generally create rating factors using regression methods (generally, GLMs) so that they can hold all other features constant.

As this was a new idea to me, I wanted to learn how to do this. While I was able to figure out how to create factors in the univariate case, I needed some help in the multivariate case. Namely, I wasn't sure how to turn GLM coefficients into relativities when more than one dependent variables were used. In my Googling, I stumbled upon two resources to help me along:

1. Chapter 2 of Non-Life Insurance Pricing with Generalized Linear Models, "The Basics of Pricing with GLMs", located [here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0CB0QFjAAahUKEwiK0JutioXJAhXEKiYKHd7RBMc&url=http%3A%2F%2Flink.springer.com%2Fchapter%2F10.1007%252F978-3-642-10791-7_2&usg=AFQjCNFNMRaDL6CUwDaVPejlWTQDrFgoIg&bvm=bv.106923889,d.eWE)
2. Allen Engelhardt's walk-through of chapter 2 of Non-Life Pricing with GLMs, located [here](http://www.cybaea.net/journal/2012/03/13/R-code-for-Chapter-2-of-Non_Life-Insurance-Pricing-with-GLM/)

Feeling I may want to come back to this again, I created this repository.
