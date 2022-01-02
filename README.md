How to use the artifact: </br>
The artifact is based on Google Colab computing engine. To run a certain version of the artifact, you can follow below steps: </br>
1-	Sign-in to Google Colab using a google account</br>
2-	Upload all the dependent module to Google Colab “Files”</br>
3-	Open one of the artifact versions on Google Colab</br>
4-	Mount your google drive which contains a folder named “Colab Notebooks” and its subfolder named “SIT723”. Inside “SIT723” folder, you create 3 subfolders for each dataset, namely “FER2013”, “CKplus”, and “JAFFE”. Each subfolder should be the location where you save/store all the datasets according their categories.
For example, the training images and labels of FER2013 should look like:</br>
“Colab Notebooks/SIT723/FER2013/x_train.csv”</br>
“Colab Notebooks/SIT723/FER2013/y_train.csv”</br>
5-	Now, run the artifact in the top-down order to avoid missing any dependent python packages</br>
NOTE:</br>
The process of running the artifact may vary based on the internet speed, the fluctuation of GPU available, and the Google account type.
