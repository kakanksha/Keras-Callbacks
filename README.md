<h1>Keras-Callbacks</h1>
This repository will make you familiar with the keras callbacks and will also help you to build your own callbacks which are not available directly in keras.  
We are writing callbacks which will -
<ol>
  <li>Print the micro F1 score and AUC score after each epoch.</li>
  <li> Save model at every epoch if validation accuracy is improved from previous epoch.</li>
  <li> Decay learning rate based on below conditions -</li>
  <ol>
    <li>If validation accuracy at that epoch is less than previous epoch accuracy, decrease the
               learning rate by 10%.</li>
    <li>For every 3rd epoch, decay learning rate by 5%.</li>
   </ol>
  <li>If there are any NaN values(either weigths or loss) while training, terminate the training.</li>
  <li>Stop the training if validation accuracy is not increased in last 2 epochs.</li>
  </ol
