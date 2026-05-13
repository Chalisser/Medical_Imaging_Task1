# Medical_Imaging_Task1

#### Python Virtual Environment Install
- Use the .yml file in the setup folder to create the virtual environment. This file defines the default name pca-env of the environment. All python libraries, the correct python version and dependencies for the respective task will be installed.
  Run:
```bash
conda env create -f [PATH_TO_ENV_FILE].yml python=3.9
```
- Activate the created python environment.
```bash
conda activate [NAME_OF_CREATED_ENVIRONMENT]
```
- Start the jupyter notebook file and now you should be able to start coding
```bash
jupyter notebook [PATH_TO_FILE].ipynb 
```
-  if you prefer to work and run the code in your preferred editor, you need to install the environment as a kernel and select the installed kernel "Python ([NAME_OF_CREATED_ENVIRONMENT]" in your editor’s UI.
```bash
pip install ipykernel 
python -m 
ipykernel 
[NAME_OF_CREATED_ENVIRONMENT] 
install --user --display-name 
([NAME_OF_CREATED_ENVIRONMENT])" --name 
"Python
```
