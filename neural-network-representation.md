## One hidden layer neural network
![](/assets/Snip20180131_28.png)

![](/assets/Snip20180131_29.png)

![](/assets/Snip20180131_31.png)


## Vectorizing across multiple examples

![](/assets/Snip20180131_33.png)

## Justification for vectorized implementation

![](/assets/Snip20180131_34.png)


## Forward Propagation and Back Progagation

### 1. proof of derivative for sigmoid function

$$
\sigma(z) = \frac{1}{1 + e^{-z}}
$$

$$
\sigma'(z)=\frac{e^{-z}}{(1 + e^{-z})^2}=\frac{1 + e^{-z} - 1}{(1 + e^{-z})^2} =
\frac{1}{1 + e^{-z}} - \frac{1}{(1 + e^{-z})^2}
=\sigma(z)(1 - \sigma(z))
$$

### 2. forward propagation

$$z^{[1]} = w^{[1]}X + b^{[1]}$$

$$A^{[1]} = g^{[1]}(z^{[1]})$$

$$z^{[2]} = w^{[2]}A^{[1]} + b^{[2]}$$

$$A^{[2]} = g^{[2]}(z^{[2]}) = \sigma(z^{[2]})$$

### 3. back propagation




