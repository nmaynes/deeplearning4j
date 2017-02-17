### 
### Regularization 

Regularization is a technique to protect  Neural Networks against overfitting to the training data. Overfitting is when the network is accurate on the training data but performs worse on unfamiliar data, such as test or live data. 

Deeplearning4J supports both L1 and L2 Regularization.

### Definition & Structure
#### Different Methods of Normalizing Data
There are two types of normalization/regularization methods used with machine learning algorithms. They are frequently referred to as L1 and L2. 
 
##### L1 or least absolute errors
The sum of the weights. Tends to keep the weights at zero, also called feature selection.  

##### L2 or least squares errors
The sum of the square of the weights. Tends to move the weights towards but not necessarily equal to zero. This allows L2 to be used with any type of training algorithm.

##### How to select which one to use
Trial and error. While there are guidelines outlined in academic papers about what types of problems are appropriate for each normalizer, model knowledge and experimentation are the most helpful techniques in practice. 

#TODO
#### Reverting Labels and Inputs

#### Normalizer Stats

#### Persistence

#### Initialization With The Fit Method

#### Conclusions & Next Steps

#### Other Resources
[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](http://jmlr.org/proceedings/papers/v37/ioffe15.pdf)
[Understanding the backward pass through Batch Normalization Layer](https://kratzert.github.io/2016/02/12/understanding-the-gradient-flow-through-the-batch-normalization-layer.html)
#### Other Beginner's Guides
