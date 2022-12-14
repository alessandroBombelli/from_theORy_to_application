In this example, we will learn how to model in an OR fashion a bin-packing problem. In a bin-packing problem, we have a set of bins $\mathcal{B}$ (each with a certain capacity and cost) and a set of items $\mathcal{I}$ (each with specific dimensions). Our goal is to place every item $i \in \mathcal{I}$ in one of the bins $b \in \mathcal{B}$ in a way that minimizes the overall cost of the chosen bins. If all bins have an uniraty cost, then we want to minimize the number of bins used.   

Bin-packing problems depend heavily on the geometry of the problem. They can be one-dimensional (1D), with weight, volume, memory, etc., being the "dimension" of the problem both for items and bins. Two- (2D) and three-dimensional (3D) problems generally entail a purely geometric interpretation, with length and width (2D) and length, width, and height (3D) being the dimensions considered.

In our example, we deal with a horizontal problem with bins having a specific length $\overline{L_b}$ and width $\overline{W_b}$, and each item having a specific length $L_i$ and width $W_i$. We can even rotate each item by 90 degrees (hence, switching the nominal length and width) if that is most efficient for the final solution.

We have a set of 9 identical bins with $\overline{L_b}=15$ and $\overline{W_b}=12$. In addition, our set of items contains 9 items with the following $\left[L_i,W_i\right]$ values: $\mathcal{I}= \\{0:[5,3],1:[3,3],2:[5,4],3:[2,9],4:[4,9],5:[6,4],6:[5,5],7:[6,3],8:[5,3]\\}$. By running run our OR model, we can find out that we only need one bin, as there is a packing strategy that allows us to have all 9 items perfectly fit! See below:

![2D_BPP](https://github.com/alessandroBombelli/from_theORy_to_application/blob/main/bin_packing/bin_0.png)



