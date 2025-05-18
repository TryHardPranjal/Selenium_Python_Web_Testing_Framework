# Selenium-Python-Example
This repository demonstrates a UI automation testing solution built with Python and Selenium WebDriver, following the Page Object Model (POM) design pattern.

Example Test Case:
A basic search functionality test on DuckDuckGo to verify that search results are properly displayed.

Prerequisites
Python 3.12.3

Latest versions of pip and setuptools

Virtual environment (venv) recommended

Setup Instructions
Clone/download this repository.

Navigate to the project root:

bash
cd selenium-python-example/  
Create & activate a virtual environment:

Linux/Mac:

bash
python3 -m venv .venv  
source .venv/bin/activate  
Windows:

cmd
py -m venv venv  
.\venv\Scripts\activate  
Install dependencies:

bash
pip install -r requirements.txt  
Running Tests
Execute tests with the following command:

bash
pytest -v --html=results/report.html  
Configuration
Default browser: Chrome (headless mode available). Modify settings in /data/config.yaml.

Test Reports
View results in:

/results/report.html  

   
   
