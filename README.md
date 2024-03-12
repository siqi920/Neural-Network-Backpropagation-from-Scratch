# simple 2 layer  neural network for XOR gate from scratch
Feed forwad equations
\begin{align*}
&z^1 = w^1 x + b^1 \\
&a^1 = f(z^1) \\
&z^2 = w^2 a^1 + b^2 \\
&a^2 = f(z^2) 
\end{align*}

loss fuction: cross entropy loss (binary classfication in this case)
$$
l = -\frac{1}{N} {(y \cdot \log(a^2) + (1-y) \cdot \log(1-a^2)))}
$$
Where N is number of training data, y is the true label, $a^2$ is output of the network.