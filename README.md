# Module-10

Crypto Analysis using Machine Learnings (KMeans, Scaling and PCA)
In this project we use machine learning techniques (KMeans, StandardScaler, and Principal Component Analysis) to scale, reduce the dimensionality, and cluster our data. Below is a simple explanation of what these processes aim to accomplish:

KMeans - Clusters the data into group that share similar characteristics
Elbow analysis - Process to determine which number of clusters are the most efficient by studying the inertia
Standard Scaler - Processes the data to have and equal scale, a necessary before applying our ML models since unscaled data can be skewed and alter our results
Principal Component Analysis - Reduces the dimensionality of our data, that is remove data that does not affect our results in a significant manner. This not only reduces our data but can make the ML models more efficient/faster.
Explained Variancy Analysis - To determine which percentage of the original data each component holds and the aggregate of these.
Technologies
The following technologies were used to build and deploy this application:

Python - Version 3.9.7
Anaconda (Which includes Jupyter Lab and Pandas)
Path (from pathlib)
hvPlot
sklearn
Installation and Usage Guide
1. Install Python 3.9.7
For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link

Anaconda Installation Files
If you require assistance installing it, you can follow the following videos for guidance

Youtube Video Python Installation Guide - Windows
Youtube Video Python Installation Guide - Mac
2. Install Anaconda
For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link

Python Installation Guide
If you require assistance installing it, you can follow the following videos for guidance

Youtube Video Anaconda Installation Guide - Windows
Youtube Video Anaconda Installation Guide - Mac
3. Installing Required Librabries
For installing the sklearn library please follow the following link

sklearn Installation
For installing the hvPlot library please follow the following link

hvPlot Installation Guide
3. Downloading the Crypto Analysis using Machine Learnings (KMeans, Scaling and PCA) Repository
Navigate to your desired location where you would like to save the documents for this application. You can do this by using the cd command followed by a space and the file path inside quotations " file path ". In my example I have gone to Desktop.

image

Clone this project's repository from GitHub using the following command

https://github.com/epocaterrasus/CryptoCurrenciesKMeansPCA.git

4. Opening the notebook
Being in the folder created when you downloaded the repository type jupyter lab, this will open the Jupyter Lab

Images
Elbow Analysis, before and after Principal Component Analysis Application image

Scatter plots using 4 Clusters (Optimal Number as shown in Elbow Analysis) before and after Principal Component Analysis Application image

Contributors
Maxwell Snyder

License
MIT License

Copyright (c) 2022 epocaterrasus

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
