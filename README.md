### dog_breed_classifier

Udacity Data Science nanodegree project.  

#### 1. **Installation**

"set-up anaconda environment"

"launch anaconda prompt"

conda deactivate

conda update anaconda-navigator

conda update -n base -c defaults conda

conda create -n tfdogs tensorflow

conda activate tfdogs

conda install -c conda-forge/label/cf202003 keras

conda install -c conda-forge matplotlib

conda install -c anaconda jupyter

conda install -c conda-forge opencv

conda install -c conda-forge ipywidgets

conda install -c conda-forge ipyfilechoosery

conda install -c conda-forge voila

"download model files and move to .keras directory"

https://storage.googleapis.com/tensorflow/keras-applications/resnet/resnet50_weights_tf_dim_ordering_tf_kernels.h5

https://storage.googleapis.com/tensorflow/keras-applications/resnet/resnet50_weights_tf_dim_ordering_tf_kernels_notop.h5

"git clone this repository as needed."

#### 2. **Project Motivation**

This is a Udacity Data Science nanodegree project.

This is a Convolutional Neural Network project with a simple Web App deployment.

#### 3. **File Descriptions**

"dog_app.ipynb" Udacity notebook for this project, includes visuals and report insights.

"report.html" this is an html version of dog_app.ipynb.

"dog_breed_classifier_r1.ipynb" this is a stripped down Jupyter Notebook model inference used for voila web app deployement.

"dognames.pkl" this is a classifier target list used for the web app inference.

"\saved_models\weights.best.Resnet50hdf5" this is the trained model weights used for inference.

"\images\ and \phone\" image directories for jpeg and png images.

"\haarcascades\haarcascade_frontalface_alt.xml" model used for human face detection.

"dogs.bat" sample batch file to launch web app by double clicking from a Win10 PC.

"LICENSE.txt" this is the Udacity License, copywrite 2017.

#### 4. **Project Interaction**

To launch the web app:

a. open an Anaconda Comand prompt.
b. navigate to directory of project,
   cd C:\users\user\desktop\dog_classifier
c. activate the environment,
   conda activate tfdogs
d. launch the web app,
   voila dog_breed_classifier_r1.ipynb
e. after finished close web browser.
f. exit the anaconda prompt
   Ctrl^C to shut down webserver
   Close prompt window.
   
To interact with the app:

A. Follow instructions within the app.

#### 5. **Licensing, Acknowledgments**

A. References:

 Yahoo Finance Downloads to CSV files for imports:

 <https://finance.yahoo.com/quote/IBM/history>

 <https://finance.yahoo.com/quote/%5EGSPC/history>

 Hyperparameter Tuning the Random Forest in Python

 <https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74>         

 CRISP-DM Reference Model

 <https://www.spss.ch/upload/1109179904_CRISP-DM%20Process%20Model.pdf>

B. License, <https://opensource.org/licenses/MIT>

Udacity License, "LICENSE.txt" file., copywrite 2017.

Begin license text.

Copyright <2021> <PATRICK PARKER>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

End license text.
