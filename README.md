# Orchestrating LLMs using Graphs

This repo is an example on how to use DAGs along with LLMs to orchestrate business flows

## System architecture diagram of the application

![architecture](https://github.com/iamraja7/langchain-app/assets/43564733/8be680ba-91c6-44df-88de-9635f6cc8dfe)

## Execution Instructions

Python version 3.10.4

To create a virtual environment and install requirements in Python 3.10.4 on different operating systems, follow the instructions below:

### For Windows:

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:


cd C:\path\to\project

Create a new virtual environment using the venv module:


python -m venv myenv

Activate the virtual environment:
myenv\Scripts\activate


Install the project requirements using pip:
pip install -r requirements.txt

### For Linux/Mac:
Open a terminal.

Change the directory to the desired location for your project:

cd /path/to/project

Create a new virtual environment using the venv module:

python3.10 -m venv myenv


Activate the virtual environment:
source myenv/bin/activate

Install the project requirements using pip:
pip install -r requirements.txt

These instructions assume you have Python 3.10.4 installed and added to your system's PATH variable.

### Execution Instructions if Multiple Python Versions Installed

If you have multiple Python versions installed on your system, you can use the Python Launcher to create a virtual environment with Python 3.10.4. Specify the version using the -p or --python flag. Follow the instructions below:

For Windows:
Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:

cd C:\path\to\project

Create a new virtual environment using the Python Launcher:

py -3.10 -m venv myenv

Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:


myenv\Scripts\activate


Install the project requirements using pip:

pip install -r requirements.txt


### For Linux/Mac:
Open a terminal.

Change the directory to the desired location for your project:

cd /path/to/project

Create a new virtual environment using the Python Launcher:


python3.10 -m venv myenv


Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:

source myenv/bin/activate


Install the project requirements using pip:

pip install -r requirements.txt


By specifying the version using py -3.10 or python3.10, you can ensure that the virtual environment is created using Python 3.10.4 specifically, even if you have other Python versions installed.


To run the streamlit app

`streamlit run llm_app.py`
