# Biomedical data analysis
## Epitranscriptomics

Hey there ! Welcome to the epitranscriptomics lesson of Summer Semester 2025 !
If you haven't heard of epitranscriptomics until last week this is nothing unusual. Modification analysis on the RNA in a large scale is just on the rise nowadays.
Why is that so ? 
Well before the Nanopore directRNA sequencing technology there have only been indirect ways to sequence RNA modifications via chemical conversion of RNA bases (Bisulfite-Seq) or non-sequencing based methods like mass spectrometry to determine RNA modifications. This was due to the fact that sequencing by synthesis only allows the detection of the base identity while complementary DNA (cDNA) is synthesized. In Nanopore Sequencing the native RNA strand, which carries the chemical modifications, is translocated through the pore and is manifested in a characteristic current signal track.

In this course you will learn how to use this modification information to analyse cancer risk genes on striking differences in the modification pattern. You will work with healthy human cell lines as control and a model cancer cellline to assess these differences. Please notice you will generate a real scientific output here, since such an analysis has not been published until now. Let's get this started ! 

Please follow this quick installation quide on your linux machine to get ready for the coding session:

### Task 1: Install miniconda for package management of our environment

```
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
```

Follow the installation instructions

```
rm ~/miniconda3/miniconda.sh
```

### Task 2: Create conda environment and activate

```
cd ~/biomedical_data_analysis_25_practical
conda env create -f biomedical_practical_SS25.yml
conda activate biomedical_practical_SS25
```

### Task 3: Install Visual Studio Code

```
wget https://code.visualstudio.com/sha/download\?build\=stable\&os\=linux-x64 -O visual_studio_binary.tar.gz
tar -xvf visual_studio_binary.tar.gz
```

To start visual studio code type the following into the console:

```
VSCode-linux-x64/code 
```

### Task 4: Install the jupyter-notebook extension in VS Code
With the barmenu on the left you can navigate within VS code to the extensions section. Search for "Jupyter" and download the extension.

### Task 5: Open the notebook of our course
In our github repository you should find the file "SAM_format_introduction.ipynb". Open the file via the vs code dialogue window or type:

```
code ./SAM_format_introduction.ipynb
```

### Task 6: Select the environment when running parts of the notebook
Whenever you want to run some lines of code please press the start button on the upper right corner of the code window. Then select "Python-Umgebung" / "Python environment" and following that "biomedical_practical_SS25".
You should now be able to run all necessary tools wihtin the jupyter notebook. 

### Task 7: Check the Introduction to tools and data formats necessary for Epitranscriptomic analysis and try to solve the tasks after the introduction in the jupyter notebook file
