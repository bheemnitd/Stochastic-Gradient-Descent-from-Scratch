## Overview.
<p align = 'justify'>Here we will implement linear regression with one variable to predict profits for a food truck. Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities.<p>
  
<p align = 'justify'>Here we will implement linear regression with one variable to predict profits for a food truck. Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities.</p>

<p align = "justify">You would like to use <a href = 'https://github.com/bheemnitd/SINGLE-FEATURE-LINEAR-REGRESSION-FROM-SCRATCH-WITH-NUMPY/blob/master/ex1data1.txt'>this</a> data to help you select which city to expand to next.The file <a href = 'https://github.com/bheemnitd/Single-Feature-Linear-Regression-From-Scratch/blob/master/ex1data1.txt'>ex1data1.txt</a> contains the dataset for our linear regression problem. The first column is the population of a city and the second column is the profit of a food truck in that city. There are 97 sample are available to train the model. A negative value for profit indicates a
loss.</p>

<p align = 'justify'>Here we used 97 training example to train the model, and used Stochastic Gradient Descent as Otimizer over 5000 iteration to get optimized theta(paramer/weight).</p>

<p align = 'justify'><b>Stochastic gradient descent</b> (often shortened to SGD), also known as incremental gradient descent, is an iterative method for optimizing a differentiable objective function, a stochastic approximation of gradient descent optimization. In SGD we update the parameters at every point where as in Batch Gradient Descent we update the parameters in batch means after adding the loss at all point's.</p>

## Dataset
Here some sample of training dataset.
<table>
  <tr><td><h5>Population of city in 10,000s</h5></td><td><h5>Profit in $10,000s</h5></td></tr>
  <tr><td>6.1101</td><td>17.592</td></tr>
  <tr><td>5.5277</td><td>9.1302</td></tr>
  <tr><td>8.5186</td><td>13.662</td></tr>
  <tr><td>7.0032</td><td>11.854</td></tr>
  <tr><td>5.8598</td><td>6.8233</td></tr>
</table><br>

## Setup
<p> Important liraries.</p>
<li> matplotlib</li>



