# Biomedical data analysis
Sequenzierpraktikum

### Task 1: Install miniconda for package management of our environment
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3 #Follow the installation instructions
rm ~/miniconda3/miniconda.sh

### Task 2: Create conda environment and activate
cd ~/biomedical_data_analysis_25_practical
conda env create -f biomedical_practical_SS25.yml
conda activate biomedical_practical_SS25.yml

### Task 3: Install Visual Studio Code
wget https://code.visualstudio.com/sha/download\?build\=stable\&os\=linux-x64 -O visual_studio_binary.tar.gz
tar -xvf visual_studio_binary.tar.gz
#To start visual studio code type the following into the console:
VSCode-linux-x64/code 

### Task 4: Install the jupyter-notebook extension in VS Code
With the barmenu on the left you can navigate within vs code to the extensions section. Search for "Jupyter" and download the extension.

### Task 5: Open the notebook of our course
In our github repository you should find the file "SAM_format_introduction.ipynb". Open the file via the vs code dialogue window or type:
code ./SAM_format_introduction.ipynb

### Task 6: Select a the environment when running parts of the notebook
Whenever you want to run some lines of code please press the start button on the upper right corner of the code window. Then select "Python-Umgbeung" / "Python environment" and following that "biomedical_practical_SS25".
You should now be able to run all necessary tools wihtin the jupyter notebook. 

### Task 7: Check the Introduction to tools and data formats necessary for Epitranscriptomic analysis and try to solve the tasks after the introduction in the jupyter notbook file