# data_structures
Implementation of all data structures in C and python

## array

* it stores n number of homogeneous elements
* address of elements varies with addtion of size of int like addresses of a[0]=2046 then a[1]=2048
* how it works internally
    * let's say, a[0] = 10 and it's address is 2046
    * now, it uses pointer concept to give element output
    * *((address of a) + 0*sizeof(int))
    * i.e. 2046 + 0*2 = 2046
    * thus it displays the values at 2046 
