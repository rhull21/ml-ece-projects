# Engineering Applications of Machine Learning and Data Analytics

## Machine Learning and Deep Learning micro-projects
* Derived projects conducted for the University of Arizona's Engineering Applications of Machine Learning and Data Analytics Course, Spring 2021
	* Full details about the course under `syllabus`, credits to [Gregory Ditzler](http://gditzler.github.io/) for course design.
* All work presented here is original to Robert Hull *from scratch*, with appropriate sources referenced when necessary.
	
## Organization: 

* `projects` - contains project assignments and writeups
* `code` - contains code associated with projects 
* `syllabus` - course syllabus
* `data` - data referenced by code
	
## Project Outline: 

1. [Basic classifiers and probability toolkit](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_01_final.ipynb)
	* 2D classification with a quadratic classifier
	* Bayes Decision Rule Classifiers 
	* Bayes Classifier 
2. [Regression and Density Estimation](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_02_final.ipynb)
	* Linear Regression with Regularization 
	* Stochastic Gradient Descent
	* KNN with a checkerboard  
3. [Support Vector Machines](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_03_final.ipynb)
	* L2 Support Vector Machine 
	* Domain Adaptation Support Vector Machines 
	* Quadratic optimization
4. Deep Learning, a Primer 
	* [Multi Layer Perceptron](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_04_P1.ipynb) on CIFAR dataset 
	* [Adaboost](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_04_P2.ipynb) with weak (decision tree) classifier in two dimensions
	* [Recurrent Neural Networks](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_04_P3.ipynb) for Language Modeling using the Shakespeare dataset
5. Advanced Deep Learning Themes
	* [Self-training and Semi Supervised Learning](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_05.ipynb) on 2D Gaussian Data
	* [Self-training on real-world data with K-fold cross validation](https://github.com/rhull21/ml-ece-projects/blob/main/code/HW_05b_kfold.ipynb)
* Research Investigation 
	* **What is the performance and transferability of Long Short Term Memory (LSTM) prediction of streamflow across different Hydrologic basins?** 
		* [Writeup](https://github.com/rhull21/ml-ece-projects/blob/main/projects/finalproj/Hull_finalproj_final_submission.pdf) 
		* [Codebase](https://github.com/rhull21/ml-ece-projects/blob/main/code/final_proj.ipynb)
		* Abstract


					This study presents a Machine Learning (ML)
					approach to learn streamflow dynamics in the Upper Colorado
					River Basin (UCRB). Long Short-Term Memory (LSTM)
					statistical emulators are used to predict daily streamflow across a
					range of hydrologic conditions for five headwater streams in the
					UCRB. First, we assess how well specialized LSTM models trained
					on only one stream perform on out-of-sample testing datasets that
					come from the same stream. Then, we explore how well the
					specialized models transfer to test datasets that come from other
					streams. Finally, we compare the performance of the specialized
					cases to a generalized LSTM model that is trained on all
					headwater streams together. We find that the best overall
					performances come from the specialized LSTM models tested on
					the same domains upon which they were tested. However, in some
					situations models trained on other domains perform best -
					particularly when predicting outlier (very high and very low flow)
					conditions. Our results are an important test case in showing how
					transfer learning from novel data-driven approaches, like LSTM,
					can be used to make hydrologically relevant predictions.)


