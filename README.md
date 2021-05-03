Getting the code 
I have hosted the project on GitHub. The entire code can be found in my repository. Link: https://github.com/DhanishJS/Patient 

Step 1: The easiest way is to download the project as ZIP and extract it on your PC. Alternative, you can clone the project by typing the ‘git clone https://github.com/DhanishJS/Patient.git ‘ on your Windows Command prompt or Mac terminal.

Step 2: Install and activate a virtual environment. This can be done in the project directory or outside. Just make sure to move back to the project directory after activating the virtual environment. 
Prerequisites 

My project requires Python 3 to be installed on your system. Mac OS and Unix come with Python preinstalled already. However, if the installed version is not Python 3. You can install the latest Python 3 version from https://www.python.org/downloads/ .  Make sure to select the box “Add Python 3.X to PATH”.

In order install all the dependencies on your system. You will need pip, which is a package manager for Python. pip can be installed from https://pip.pypa.io/en/latest/installing/ . For windows, use py get-pip.py and for Unix/macOS use python get-pip.py. 

Installing and Activating Virtual Environment
Here is the command. (The name of the virtual environment can anything)
Windows 	                        Unix/macOS
pip install virtualenv	            pip install virtualenv
virtualenv P 	                    virtualenv P
P\Scripts\activate	                source P\bin\activate

Now move to the directory extracted project folder “Patient”.	Now move to the directory extracted project folder “Patient”.
pip install -r requirements.txt	pip install -r requirements.txt

If any problems arise, you can refer to the https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/ . 

The final step is to check if manage.py file is located in your current working directory. Then run the command: python manage.py runserver 

Development server will run at http://127.0.0.1:8000/. Copy and past the link into browser and AtEase application is now open.

Username and Password for current account in the database are provided in the Final Report Appendix.