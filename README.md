# Machine-Learning-Forecasting
Repo to store all code from machine learning and forecasting module.
### Setup:
#### Clone the repository
Open a new a terminal, and whilst in your homespace (`/home/jovyan`) run:
```
git clone git clone git@github.com:LDMOJ4/Machine-Learning-Forecasting.git
```
#### Create a virtual environment with `venv`
Python users are recommended to use `venv` for package management. To setup a `venv` run the following commands:
```
cd Machine-Learning-Forecasting
python3 -m venv venvMLF
```
To activate your `venv` run:
```
. venvMLF/bin/activate
```
#### Install packages:
Before you install any packages, make sure that your `venv` is activated. 
Then once your `venv` is activated run the following command to install the relevant packages:
```
pip install -r requirements.txt
```
#### Create a jupyter kernel to use the virtual environment:
```
pip install ipykernel
python3 -m ipykernel install --user --name="venvMLF" --display-name="MLF(Python3)"
```
This may take a few minutes for the kernel to install and load in your jupyterlab. If this does not appear after a few minutes, then please refresh your jupyterlab instance.
