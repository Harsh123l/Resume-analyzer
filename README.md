A tool designed to extract information from resumes through natural language processing identifies keywords and categorizes them into sectors based on their relevance. Ultimately, it provides recommendations, predictions, and analytics to both applicants and recruiters based on keyword alignment.

# Scope 
i. This tool can convert all resume data into a structured tabular format, including CSV, enabling organizations to utilize this data for analytical purposes.  
ii. By offering recommendations, predictions, and an overall score, users can enhance their resumes and continuously test them using our tool.  
iii. The user section can drive increased traffic to our tool.  
iv. Colleges can leverage this tool to gain insights into students and their resumes prior to placement opportunities.  
v. It can also provide analytics regarding the roles that users are predominantly interested in.  
vi. Feedback can be utilized to enhance the tool's functionality.

# Required Installations for a Smooth Process
- Python (3.9.12) [Download here](https://www.python.org/downloads/release/python-3912/)  
- MySQL [Download here](https://www.mysql.com/downloads/)  
- Visual Studio Code (Recommended Code Editor) [Download here](https://code.visualstudio.com/Download)  
- Visual Studio Build Tools for C++ [Download here](https://aka.ms/vs/17/release/vs_BuildTools.exe)  

# Setup & Installation 👀
To execute this project, follow these steps:  
1. Download the code file either manually or via Git.  
2. Create and activate a virtual environment (recommended) by executing the following commands in your command prompt:  
   - Navigate to your project directory, AI-Resume-Analyzer, and run:  
     - `python -m venv venvapp`  
     - `cd venvapp/Scripts`  
     - `activate`  
3. Download the necessary packages from the requirements.txt file located in the App folder:  
   - `cd ../..`  
   - `cd App`  
   - `pip install -r requirements.txt`  
   - `python -m spacy download en_core_web_sm`  
4. After the installation is complete, create a database named 'cv' and update the user credentials in App.py:  
   - Navigate to `AI-Resume-Analyzer/App/App.py`  
   - Modify line 95 as follows:  
     - `connection = pymysql.connect(host='localhost', user='root', password='root@MySQL4admin', db='cv')
IMP NOTE :-
# Go to venvapp\Lib\site-packages\pyresparser folder
# And replace the resume_parser.py with resume_parser.py
# which was provided by me inside pyresparser folder
# I hope that your venvapp is activated and working directory is inside App
Last Step
# Run the App.py file using
- `streamlit run App.py`
# Error which may occur :- GeocoderUnavailable error comes up then just check your internet connection and network speed

