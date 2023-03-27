Here's how to create a virtual env with miniconda and install the correct versions of FastAPI on 
your machine:

Before you begin, you'll need to have Miniconda installed on your machine.

Create a new virtual environment using the following command:

conda create --name env_name python=3.11

This will create a new virtual environment named "env_name" using Python version 3.11

Activate the virtual environment by running the following command:

conda activate env_name

To ensure consistent development packages for everyone, use the following command:

pip install -r requirements.txt

his will install all the dependencies listed in the requirements.txt file.


