# Left Recursion Elimination

Eliminate any left-recursive productions (including indirect ones). When you are done, submit this README.md file with your answers on Canvas. 

## Q1

```
X -> XYz | Xw | w
X -> wX'
X' -> YzX' | wX' | ep 

Y -> Yp | q
Y -> qY'
Y' -> pY'| ep
 
```


## Q2

```
S -> aA | Sd
S -> aAs'
S' -> dS' | ep

A -> b
```

## Q3

```
A -> Bxy | x
A -> CDxy | x
A -> ADxy | x
A -> xA'
A' -> DxyA' | ep

B -> CD
B -> AD
B -> BxyD
B -> B'
B' -> xyDB' | ep


C -> A | c
C -> Bxy | c
C -> CDxy | c
C -> cC'
C' -> cC' | ep

D -> d  
```


```
A -> Bxy | x

B -> AD \cD

D -> d
```

```
A -> ADxy | cDxy | x

D -> d
```

```
A -> xA' | cDxyA'

A' -> DxyA' | ep

D -> d
```