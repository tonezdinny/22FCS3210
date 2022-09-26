# Question 1

Consider the following JavaScript-like program to answer the items below.  

```
var x;

function sub1() {
    document.write("x = " + x);
}

function sub2() {
    var x;
    x = 10;
    sub1();
}

x = 5;
sub2();
```

a) What value of x is displayed in function **sub1** IF **static-scoping** rules are applied?  


b) What value of x is displayed in function **sub1** IF **dynamic-scoping** rules are applied?  

# Question 2

Consider the following program, written in JavaScript-like syntax:  

```
// main program
var x, y, z;

function sub1() {
    var a, y, z;
    // ... 
}

function sub2() {
    var a, b, z;
    // ...
}

function sub3() {
    var a, x, w;
    // ...
}
```

Given the following calling sequences and assuming that dynamic scoping is used, what variables are visible during execution of the last subprogram activated? Include with each visible variable the name of the unit where it is declared.  

a) main calls sub1; sub1 calls sub2; sub2 calls sub3.  
 
b) main calls sub1; sub1 calls sub3.  
 
c) main calls sub2; sub2 calls sub3; sub3 calls sub1.  

d) main calls sub3; sub3 calls sub1.  
 
e) main calls sub1; sub1 calls sub3; sub3 calls sub2.  
 
f) main calls sub3; sub3 calls sub2; sub2 calls sub1.  