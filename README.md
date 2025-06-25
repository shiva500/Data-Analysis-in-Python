Instructions to Open and Run Jupyter 
Notebooks 
Prerequisites 
• Conda: Make sure you have Conda installed.  
• Jupyter Notebook: Install via Conda environment setup. 
• Dataset link: https://www.kaggle.com/datasets/vjchoudhary7/customer
segmentation-tutorial-in-python 
Steps 
1. Create a Directory 
Open Command Prompt (Windows) or Terminal (Mac/Linux) and create a directory to store 
your notebooks: 
mkdir my_notebooks 
2. Place the Notebooks in the Directory 
Move your .ipynb files to the my_notebooks directory. 
3. Create and Activate Conda Environment 
Navigate to the directory where your environment.yml file is located and create a new Conda 
environment: 
conda env create --name foo_env --file=environment.yml 
Activate the environment: 
conda activate foo_env 
4. Open Jupyter Notebook 
Open Command Prompt (Windows) or Terminal (Mac/Linux) and change the directory to where 
the .ipynb files are placed: 
cd path/to/my_notebooks 
Start Jupyter Notebook: 
jupyter notebook 
5. Run All Cells in the Notebooks 
In the Jupyter Notebook interface that opens in your web browser, you will see a list of files in 
the my_notebooks directory. Click on the notebook file you want to open. 
To run all cells in the notebook: 
• Click on Cell in the menu bar. 
• Click Run All. 
