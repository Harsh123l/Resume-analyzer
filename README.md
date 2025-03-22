A tool which parses information from a resume using natural language processing and finds the keywords, cluster them onto sectors based on their keywords. And lastly show recommendations, predictions, analytics to the applicant / recruiter based on keyword matching.
# Scope 
i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use those data for analytics purposes
ii. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool
iii. And it can increase more traffic to our tool because of user section
iv. It can be used by colleges to get insight of students and their resume before placements
v. Also, to get analytics for roles which users are mostly looking for
vi. To improve this tool by getting feedbacks

# Have these things installed to make your process smooth
Python (3.9.12) https://www.python.org/downloads/release/python-3912/
MySQL https://www.mysql.com/downloads/
Visual Studio Code (Prefered Code Editor) https://code.visualstudio.com/Download
Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe

# Setup & Installation 👀
To run this project, perform the following tasks 
# Download the code file manually or via git
Create a virtual environment and activate it (recommended) by doing so..
# Open your command prompt and change your project directory to AI-Resume-Analyzer and run the following command
# python -m venv venvapp
# cd venvapp/Scripts
# activate
Downloading packages from requirements.txt inside App folder
# cd../..
# cd App
# pip install -r requirements.txt
# python -m spacy download en_core_web_sm
After installation is finished create a Database cv
And change user credentials inside App.py
# AI-Resume-Analyzer/App/App.py
Line 95 in 17e1cdb
# connection = pymysql.connect(host='localhost',user='root',password='root@MySQL4admin',db='cv'
# Go to venvapp\Lib\site-packages\pyresparser folder
# And replace the resume_parser.py with resume_parser.py
# which was provided by me inside pyresparser folder
# I hope that your venvapp is activated and working directory is inside App
# Run the App.py file using
# streamlit run App.py

# Error which may occur :- GeocoderUnavailable error comes up then just check your internet connection and network speed

