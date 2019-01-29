# Dogs_vs_cats_Exp
+Here I tried use google colab notebook for the classification problem

+Here I classified the images using transfer learning:
  *Resnet50 architecture is used
  *I used the weights which are obtained when the model is trained on the Imagenet data set
  *Keras inbuilt preprocesing techiques are used
+In the first part of the notebook I only used the features obtained from image net and 
removed the fully connected layers(by keeping include_top = False) and added few layers.
  *Trained it for one epoch
  *We can see that train_accuracy reached a value of 95%  and 98% validation accuracy
+In the second part I went bit deep to train the network
  *Trained it for one epoch
  *We see that train accuracy is 97.21% and val_accuray 53%
  From this we observe that  Model overfitted the train data

**Conclusion** : Transfer learning allows to get better results than training a model from scratch.

  
