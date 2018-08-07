# MADDPG on DLAMI
This fork is designed to work on an instance of the AWS Deep Learning AMI, which uses Jupyter Notebook. Due to the nature of the notebook, the `.ipynb` file has forgone command line argument parsing and instead has a set of parameters which are manually tuned within the code.

To connect to the AMI instance, cd into the directory containing the private key, and run the following, replacing the necessary arguments:
```
ssh -L localhost:8888:localhost:8888 -i <private key filename> ubuntu@<instance public DNS>
```
