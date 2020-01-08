# Give Me Some Credit

Give Me Some Credit Kaggle Challenge.

Down load the datasets from Kaggle: 
https://www.kaggle.com/c/GiveMeSomeCredit

## Setting up your environement

### Option 1 Docker

In the docker directory
- Create a "auth.env" file with your BigML and Kaggle Credencials following the model "auth.env.exemple"
- Build and start the container with

```
$ docker-compose up
```

Open your browser with the link provided

Alternatively you can use the script provided To launch and open jupyter notebook in a single move.

```
$ ./docker-notebook.sh up
```
### Option 2 virtualenv

Install virtualenv and virtualenvwrapper
https://virtualenvwrapper.readthedocs.io/en/latest/install.html

Create your virtual environement:
```
$ mkvirtualenv -a . -r requirements.txt Give-Me-Some-Credits
```

Activate your environement:
```
workon Give-Me-Some-Credits
```

Deactivate with
```
$ deactivate
```
Save your credencials in a ".env" file
and launch the notebook (Linux only) with
```
$ ./notebook.sh start
```

## Project

[01-Dataset Analysis.ipynb](01-Dataset%20Analysis.ipynb)

[02-Dataset Preprocessing.ipynb](02-Dataset%20Preprocessing.ipynb)

[03-Training.ipynb](03-Training.ipynb)

[04-Model Evaluation.ipynb](04-Model%20Evaluation.ipynb)

[05-Submission to Kaggle.ipynb](05-Submission%20to%20Kaggle.ipynb)

[Auc Error plot.ipynb](Auc%20Error%20plot.ipynb)

[Learning Curves.ipynb](Learning%20Curves.ipynb)

[training-XGBoost.ipynb](training-XGBoost.ipynb)

[ensemble-vs-deep.ipynb](ensemble-vs-deep.ipynb)

[Single Prediction.ipynb](Single%20Prediction.ipynb)
