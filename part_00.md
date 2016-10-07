
#The science of programming - Note 1
##Part  0 Why use logic?
###A story
考慮一個除法程式 remainder quotient calculation  
`x` :  dividend,  non-negative integer  
`y` : divisor, positive integer  
`q` : quotient  
`r` : remainder  

``` c++
//division ver.1
r = x;
q = 0;
while(r > y){
    r = r - y;
    q = q + 1;
}
```
然後開始debug

