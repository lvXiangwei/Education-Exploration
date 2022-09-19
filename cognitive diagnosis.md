### HierCDF

![](pics/HierCDF-framework.jpg)

#### Baisc concepts: 


- S: students

- E: question

- C: attributes

- R:{(s, e, y)} set of response logs

- Q: Q-matrix

####  Attributes hierarchy

G = (V, E), directed acyclic graph(DAG)

V： attribute node

E: a->b, a is the basis of the learning of b



#### Model

- cognitive state module
  - $m_{ik}$, student i' s cognitive level on attribute k
  - $c^{+}_{u,k|j}$, student i 's cognitive level on attribute k when she has master j 
  - $c^{-}_{u,k|j}$, student i 's cognitive level on attribute k when she has not master j 
- question feature module
- CDM adaptor
