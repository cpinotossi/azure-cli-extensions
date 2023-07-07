# Azure Cost Estimator

based on: https://github.com/Azure/azure-cli-dev-tools#setting-up-your-development-environment

~~~bash
python --version # Python 3.10.8
python -m venv env # create virtual environment for python
source env/bin/activate # activate env virtual environment
sudo apt install gcc python3-dev # install for azdev
python -m pip install -U pip # upgrade pip
pip install azdev
azdev setup --repo /workspaces/azure-cli-extensions
~~~