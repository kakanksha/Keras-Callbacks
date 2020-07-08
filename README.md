<h1>Keras-Callbacks</h1>
This repository will make you familiar with the keras callbacks and will also help you to build your own callbacks which are not available in keras directly.  
We are writing callbacks which will -
<ol>
  <li>print the micro F1 score and AUC score after each epoch.</li>
  <li> Save your model at every epoch if your validation accuracy is improved from previous epoch.</li>
  <li> decay learning based on below conditions </li>
  <ol>
    <li>If your validation accuracy at that epoch is less than previous epoch accuracy, you have to decrese the
               learning rate by 10%.</li>
    <li>For every 3rd epoch, decay your learning rate by 5%.</li>
   </ol>
  <li>If you are getting any NaN values(either weigths or loss) while training, you have to terminate your training.</li>
  <li>You have to stop the training if your validation accuracy is not increased in last 2 epochs.</li>
  </ol
