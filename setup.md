# 1. Create venv environment

python3 -m venv venv

# 2. Activated environment

source venv/bin/activate

# 3. Install Jupyter and ipykernel in your virtual environment

pip install jupyter ipykernel

# 4. Add your virtual environment as a Jupyter kernel

python -m ipykernel install --user --name=venv --display-name="Python (venv)"

# 5. Launch Jupyter from your activated virtual environment

jupyter notebook

# 6. Create requirements.txt and install packages

touch requirements.txt

# 7. Install the packages and include more as you go and keep installing using:

pip install -r requirements.txt
