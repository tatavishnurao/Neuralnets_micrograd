# Neuralnets_micrograd
Just posting my learning about Neural Networks

I just started Andrej's Neural Networks Series. Would you believe me if I stayed whole night for about 6 hours to pour in his wisdom into me? His teachings are just so simple and on-point.

I had just had to start out with Excalidraw to visualize and soak in his teachings


![Image](https://github.com/user-attachments/assets/ea1c9beb-f945-4686-90d1-e0851d0323f6)

### 3-step Illustration
```
1) We are itearating thorugh each edge and node one-by-one
2) Then we applying Chain Rule locally which points to children nodes everytime we backpropogate
3) Now, for final sauce Iteratively add and multiply on local derivatives
```
### Backpropogation in a Nutshell: The recursive application of Chain rule backwards thorugh the computation graph

#### The core of the backpropagation is the differentiability of curve-fitting function for each constant k is a real number

![Image](https://github.com/user-attachments/assets/0d7abf4a-45bb-463f-8a67-ae50b1dd567b)

The backpropoagtion aims to solve the curve-fitting problem i.e, 
```
y(x) = k0 + k1x + k2x^2 + k3x^3 + k4x^4 + k5x^5 where for every k is a real number.
```

________________________________________________________________________________________________________

### THE GOAL is to find the set of coeffients which satisfies the curve-fitting for the points available

--The Backpropogation can happen in 4 steps:
1) Forward Pass: The derivations obtained from the function
2) Backward Pass: The use of Gradient descent and Chain rule
3) Nudge the knobs for the points in y(x):

![Image](https://github.com/user-attachments/assets/cb2c2dc7-2e2a-416b-abc0-8faea969e504)

