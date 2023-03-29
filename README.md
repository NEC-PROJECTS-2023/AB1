# AB1

1.Manohar Ramisetty
2.srinivas Annaladasu
3.Ramakrishna chintakrindi
4.Gopi Tammisetti

Diabetes is a disease that occurs when your blood glucose is too high. Whenever having too much
glucose in your blood can cause health problems. Now-a-days diabetes become the common disease
in all ages and threatening each and every one in all over the world. Although diabetes has no cure,
we need to take steps to manage diabetes and stay healthy.
Hyperglycaemia, also called raised blood glucose is a common effect of uncontrolled diabetes and
over time leads to serious damage to many of the body's systems, especially the nerves and blood
vessels. The most common types of diabetes are type 1, type 2, and gestational diabetes.
Machine learning allows software applications to become more accurate at predicting outcomes
without being explicitly programmed to do so. That’s why with help of machine learning we are
going to develop a system which can perform early prediction of diabetes risk level of a patient with
high and better accuracy by combining the results of different machine learning techniques.
This project is emphasise on different types of machine learning algorithms like Support vector
machine, Decision Tree, Random Forest etc on dataset taken from the repository of kaggle. Here we
choose the best accuracy and precision prediction algorithm which is coded in python and executed
in Jupyter (python Development Environment) Platform.

Diabetes prediction using Machine Learning<br/>

Flask is a Python-based microweb platform that allows users to add application functionality as if they were built into the framework itself. Below fig shows the basic file structures of the developed application and this development process comprises of four different program modules as follows:

• model.pkl- This contains the machine learning model to predict diabetes. Random forest provided the highest accuracy of 92% with all the features, we will integrate this as predictive model in the model.pkl file.

• app.py- This package includes Flask APIs that receive Diabetes information through GUI or API calls, compute the predicted value using our model, and return it.

•Template- The HTML form (index.html) in this folder allows the user to enter diabetes information and shows the expected outcome.

•Static- This folder contains the css file which has the styling required for our HTML form.

DiabetesPrediction/

	|--------model.pkl

		|--------static

	

	|--------template/

	

		|-----diabetes.html(main)

		

		|-----result.html

		

		|-----risk_score.html

	

	|--------app.py
