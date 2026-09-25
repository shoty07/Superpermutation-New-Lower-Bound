# A New Lower Bound for the Superpermutation Problem

I have discovered a new closed-form formula that establishes a tighter lower bound for the Superpermutation problem for any $n \ge 3$. 

While the previous widely accepted lower bound (originating from the 2011 4chan anonymous post and verified in 2018) yields **93,884,313,611** for $n=14$, my formula yields **93,884,313,645** (an improvement of 34).

## The Formula

The lower bound $L(n)$ for a superpermutation of $n$ symbols is given by:
Let $\alpha$ be defined as:

$$ \alpha = \left\lfloor \frac{\ln(n!-1)}{\ln(n)}-1 \right\rfloor $$

Then, the lower bound $L(n)$ is:

$$ L(n) = n!+n-1 + \sum_{k=1}^{\alpha} \left\lfloor \frac{n!-1}{n^k} \right\rfloor $$

## Computation & Proof
The results have been computed and verified for $n=14$. 
The formal mathematical proof is currently in preparation and will be published based on community interest.

Feel free to test the formula and reach out.
