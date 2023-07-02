```cmd
# Cls -clear
# code . - Open VS code from Cmd

# activate base enviorment CTRL+SHIFT+P (base)
    conda activate base 
# create virtual enviorment 
 ``` conda create --prefix venv python=3.8 -y(prefix used to create the env in the required location rather than defulat location)
 To activate this environment, use
#
# $ conda activate "C:\Users\Delhivery\OneDrive - Delhivery Private Limited\Documents\Certification\Projects_2023\Walter_Fault_Discussion\sensor_project\venv"
#
# To deactivate an active environment, use
#
#     $ conda deactivate
# Kernal installtion pip install ipykernel
# python setup.py install(check for the author details before installing the setup.py)
#pip list
# pip install -r requirements.txt
#download git so that use git bash
# git --version
#.git repository can be seen in hidden form in local windows

echo "# Sensor_Fault_Detection" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/TheAbhishekraj/Sensor_Fault_Detection.git
git push -u origin main


git remote add origin https://github.com/TheAbhishekraj/Sensor_Fault_Detection.git
git branch -M main
git push -u origin main

git add .
git status
