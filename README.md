# tensorflow.js
Creates a model (dense layer, leakyReLu activation and output layer) in tensorflow.js and trains it based on user input regarding mean squared error and sgd optimizer. The resulting prediction/regression as well as the input data is then plotted via Chart.js on a fixed size canvas.
If you want linear regression, just change the first model layers to  
```model.add(tf.layers.dense({units: 1, inputShape: [1]})); // layer 1```
and comment out the other layers.

Click the following link to try it out (click on file/raw won't display the page):

https://rawgit.com/Kogl1n/tensorflow.js/master/tensorflow.js.ex1.html
