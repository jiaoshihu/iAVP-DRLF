# ATGPred-FL


# 1 Description
Autophagy is a conservative ‘self-eating’ process during biological evolution. Accurately identification of autophagy proteins (ATGs) is crucially important to reveal their biological functions. Here, we developed the first machine learning-based software that enables the classification of proteins into ATGs or non-ATGs. ATGPred-FL, which identifies ATGs using feature representation learning scheme and support vector machine algorithm. It has the potential to facilitate future computational work in this field.
Webserver and datasets available at:
http://lab.malab.cn/~acy/ATGPred-FL/ 


# 2 Requirements
Before running, please make sure the following packages are installed in Python environment:
python==3.7
numpy==1.20.3
pandas==1.3.5
pandas==1.0.1
rich==9.12.4
pytorch==1.4.0
tape_proteins==0.5
sklearn==1.0.1
lightgbm==3.1.1

For convenience, we strongly recommended users to install the Anaconda Python 3.8.5
(or above) in your local computer.


# 3 Running
Changing working dir to ATGPred-master, and then running the following command:

python ATGPred.py -i test.fasta -o prediction_results.csv

-i: input file in fasta format
-o output file name
