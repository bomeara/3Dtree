# 3Dtree
Way to make a 3D tree in R

![Tree](3d.jpg)

Inspired by

![Phrapl tree 1](http://www.phrapl.org/img/movie645.gif)

![Phrapl tree 2](http://www.phrapl.org/img/movie1232.gif)

To use:

```
install.packages("devtools")
devtools::install_github("bomeara/Tree3D")
library("Tree3D")
phy <- ape::rcoal(20)
Plot3DTree(phy)
```
