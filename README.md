# flask-skeleton

A skeleton project to deploy a bare bones environment for Flask development.

You still need to run python -m venv venv --prompt="<projectname>", 
activate the virtual environment (source venv/bin/activate) 
and then install the requirements.txt file (python -r requirements.txt)

The requirements file contains the main modules for Flask plus modules for python-dotenv (https://pypi.org/project/python-dotenv/) to help you separate out any sensitive content like API keys into a .env file
