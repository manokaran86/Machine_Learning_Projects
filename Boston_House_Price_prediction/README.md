# Boston House Pricing Prediction

### Software and Tools Requirements

1. [Github Account]
2. [HerokuAccount]
3. [VSCodeIDE]
4. [GitCLI]

1. Create a new environment
   conda create -p venv python==3.7 -y

# To activate this environment, use
#     $ conda activate C:\Users\Manokaran\OneDrive\AI_Projects\Machine_Learning_Projects\Boston_House_Price_prediction\venv
# To deactivate an active environment, use
#     $ conda deactivate

2. Activate the virtual environment using the above command
3. Create the requirement file
4. To install the required packages in the virtual environment, run the below command
    pip install -r requirements.txt
5. Wait for all the required packages are installed 
6. In order to push all the codes and files to the GIT repository, follow the below steps
   git config --global user.name "Manokaran"
   git config --global user.email "manokaran286@gmail.com"
7. Adding all the files to the GIT repository
   git add .   ---> This will add all the files
   git status   --> To get to know the status about the repository
   git commit -m "This commit includes all the development files"   ---> Git commit with the messages 
   git push origin main  --> pushing the codes to github repository

8.Creation of docker file



Running cells with 'Python 3.7.0 (conda)' requires ipykernel package.
Run the following command to install 'ipykernel' into the Python environment.
   conda install -p c:\Users\Manokaran\OneDrive\AI_Projects\Machine_Learning_Projects\Boston_House_Price_prediction\venv ipykernel --update-deps --force-reinstall