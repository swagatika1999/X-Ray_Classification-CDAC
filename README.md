# X-Ray_Classification-CDAC

X-Ray classification deals with identifying the disease i.e. pneumonia in a person.The objective of this project is to make the work of medical professionals easier  and quicker than earlier to detect pneumonia in a person's body. To fulfill the objective of this project, we need the datasets so as to train the model about the differences between normal person and a person having pneumonia.

#dataset for project: 

link- https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/download

Before running program download the dataset from the link and place the chest_xray folder, containing train, test and val folders, inside X-Ray_Classification-CDAC folder.

#datset for project: 

link- https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/download

#installation process:

git clone https://github.com/prateeksarangi/X-Ray_Classification-CDAC/

cd X-Ray_Classification-CDAC

pip install virtualenv

source bin/activate

pip install -r requirements.txt

#Training dataset on local system: 

python TundNN.py

#Running the webapp backend program:-

python ServerSide.py

#Running the webapp frontend program:-

python exec.py

After executing exec.py, open localhost:5000 in web browser.

