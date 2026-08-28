# gdaassesment
Gda assesement

The two output ipynb files are given.

For the first question: all the details are included in the classifier.ipynb file. The markdown and code comments explain all the necessary workflow and model choice for the classifier. The initial step included dataprocessing of both the raster and vector data o check for compatibility and approriate visualization.
For the first question: all the details are included in the classifier.ipynb file. The markdown and code comments explain all the necessary workflow and model choice for the classifier. The initial step included dataprocessing of both the raster and vector data o check for compatibility and approriate visualization.

The two output ipynb files are given.

For the first question: all the details are included in the classifier.ipynb file. The markdown and code comments explain all the necessary workflow and model choice for the classifier. The initial step included dataprocessing of both the raster and vector data o check for compatibility and approriate visualization.

For the model choice, I recommend using randomforest classifier with number of trees set to 300. Random forest calssifier in addition to learning non-linear boundaries, it can also allow for establishing relationship among importance of features/bands to predicting land coverage. This can be seen from the results of the outputs of the accuracy and from the normalized confusion matrix shown. The two models compared are logisitic regression and random forest classifier, with random forest classifier achieving 92% accuracy. 

I used a stratified 5 fold cross validation for evlauation. This allows for ensuring varied distribution of data in folds used for validation and training. 

Lastly, the visualization for the sentinel image shows properties for the categories showing a pattern of water body concentration in the nothern part of the plot while other bodies are distributed in varied ways. This RGB Sentinel image is exported to a geotiff file. 

I also visualized the continuous categorical information and visualized it on top of the rgb raster data. This continuous visualisation shows that the random forest classifier is closer to the ground truth point visualisation from the vector data. 

For the SQL question use sql_test.ipynb file that shows the queries and output of the commands. the output of the final queries can be found on the account_with_orders.csv file.
