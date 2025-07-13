# cintel-04-local

# Add files & packages
.gitignore
.app.py - copied from CC3

# requirements.txt
faicons
palmerpenguins
pandas
pyarrow
plotly
seaborn
shiny
shinylive
shinywidgets

# verify Python version in PowerShell
python --version
py --version
py -m pip --version

# install Python newest version Python 3.13.5  (as needed)

# Project Setup in VS Code
## Clone the Repository
git clone https://github.com/bfuemmeler/cintel-04-local.git
cd cintel-04-local

## Create & Activate Virtual Environment
python -m venv venv
.\venv\Scripts\Activate.ps1

## Install Required Packages
pip install -r requirements.txt

## Run the Shiny App
python app.py

## Install newest Git using PowerShell
git update-git-for-windows
at prompt asking to download & install new version, type Y

# Verify version of Git
git --version

# Verify Git configuration
git config --global --get user.name
git config --global --get user.email

# In VS Code, go to Documents folder
cd ~\Documents

# Git Clone from GitHub repo
git clone https://github.com/bfuemmeler/cintel-04-local.git

# Create Virtual Environment
py -m venv .venv

# Verify .gitignore file has .venv

# Activate Virtual Environment
.venv\Scripts\Activate

# Install Dependencies
py -m pip install --upgrade pip setuptools
py -m pip install --upgrade -r requirements.txt








