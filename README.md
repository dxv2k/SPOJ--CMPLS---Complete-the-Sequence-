# SPOJ--CMPLS---Complete-the-Sequence-


What I've learned?

- Method of differences
https://brilliant.org/wiki/method-of-differences/

FORMULA
    D1(n) = f(n+1) - f(n)
    D2(n) = D1(n+1) - D1(n)

EXAMPLE:
    f(1) = 4 , f(2) = 3 , f(3) = 4 , f(4) = 7, f(5) = 12  

    Table
    n     f(n)    D1(n)   D2(n)   D3(n)   ...
    1     4       -1      2       0
    2     3       -1      2       0
    3     4        3      2       0
    4     7        5      2       0
    5     12       7      2       0


THOEREM
  If a polynomial f(x) has degree k, then the  k^(th) difference is constant.
  Furthermore, the k^(th) difference is equal to k! times the leading
  coefficient of f(x)
