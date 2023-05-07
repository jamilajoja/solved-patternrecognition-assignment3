Download Link: https://assignmentchef.com/product/solved-patternrecognition-assignment3
<br>
<ol>

 <li>Consider the 128- dimensional feature vectors (d=128) given in the “<strong>gender_feature</strong></li>

</ol>

<strong>_vectors.csv</strong>” file. (2 classes, male and female)

<ol>

 <li>Use PCA to reduce the dimension from d to d’. (Here d=128)</li>

 <li>Display the eigenvalue based on increasing order, select the d’ of the corresponding eigenvector which is the appropriate dimension d’ ( select d’ S.T first 95% of λ values of the covariance matrix are considered).</li>

 <li>Use d’ features to classify the test cases (any classification algorithm taught in class like Bayes classifier, minimum distance classifier, and so on)</li>

</ol>

<strong>Dataset Specifications:</strong>

Total number of samples = 800

Number of classes = 2 (labeled as “male” and “female”)

Samples from “1 to 400” belongs to class “male”

<table>

 <tbody>

  <tr>

   <td width="76"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Samples from “401 to 800” belongs to class “female”

Number of samples per class = 400 Number of dimensions = 128

<strong>Use the following information to design classifier:</strong>

Number of test cases ( first 10 in each class)  = 20

Number of training feature vectors ( remaining 390 in each class) = 390

Number of reduced dimensions = d’ (map 128 to d’ features vector)

<ol start="2">

 <li>For the same dataset (2 classes, male and female)

  <ol>

   <li>Use LDA to reduce the dimension from d to d’. (Here d=128)</li>

   <li>Choose the direction W to reduce the dimension d’ (select appropriate d’).</li>

   <li>Use d’ features to classify the test cases (any classification algorithm will do, Bayes classifier, minimum distance classifier, and so on).</li>

  </ol></li>

 <li>Give the comparative study for the above results w.r.t to classification accuracy in terms of the confusion matrix.</li>

 <li><strong>Eigenfaces</strong>-Face classification using PCA (40 classes)

  <ol>

   <li>Use the following “<strong>csv” </strong>file to classify the faces of 40 different people.</li>

   <li>Do not use the in-built function for implementing PCA.</li>

   <li>Use appropriate classifier taught in class (any classification algorithm taught in class like Bayes classifier, minimum distance classifier, and so on )</li>

   <li>Refer to the following link for a description of the dataset: <a href="https://towardsdatascience.com/eigenfaces-face-classification-in-python-7b8d2af3d3e">https://towardsdatascience.com/eigenfaces-face-classification-in-python-7b8d2af3d3e</a></li>

  </ol></li>

 <li><strong>Fisherfaces</strong>– Face classification using LDA (40 classes)

  <ol>

   <li>Use the following “<strong>csv” </strong>file to classify the faces of 40 different people.</li>

   <li>Do not use the in-built function for implementing LDA.</li>

   <li>Use appropriate classifier taught in class (any classification algorithm taught in class like Bayes classifier, minimum distance classifier, and so on )</li>

   <li>Refer to the following link for a description of the dataset:</li>

  </ol></li>

</ol>

<a href="https://towardsdatascience.com/eigenfaces-face-classification-in-python-7b8d2af3d3e">https://towardsdatascience.com/eigenfaces-face-classification-in-python-7b8d2af3d3e</a>