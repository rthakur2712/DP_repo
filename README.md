# DP_repo
O(3^n) 
to traverse through all the submasks of a mask
```for (int m=0; m<(1<<n); ++m)
    for (int s=m; s; s=(s-1)&m)
 ... s and m ...
 ```