# grid-col-gap-test
Messing around with changing the column gap
Columns 3 and 4 will have a diffrent margin. Giving the effect that they are smaller.  

Formula is number of columns = what to use in `nth-child()`.  
Then subtract what you need.   
If you want to edit the 2nd and 4th column i.e. 
```
.grid div:nth-child(4n - 2) {}
```
