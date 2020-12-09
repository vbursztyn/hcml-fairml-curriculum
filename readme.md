# HCML - Examining Fairness in ML Models: A Case Study
### Professor Stevie Chancellor, Fall 2020.
### Ally Reith, Aristana Scourtas, Natalie Araujo Melo, Victor Bursztyn, Zane Denmon.

Setup steps on MacOS:
1. Go to the `Applications` folder on your computer, and open `Terminal` to access the commandline
2. Enter the command `brew install graphviz` to install graphviz on Mac OS
3. In the terminal, navigate to the directory you want to install the workshop files to by running the command `cd <directory_path>`. For example, if I wanted to download everything to my Desktop, I'd run `cd ~/Desktop` 
4. Now you should be in the right directory! Run `pwd` to check if you're in the right directory.
5. Great! Pull down the workshop files by running `git clone https://github.com/vbursztyn/hcml-fairml-curriculum.git`
6. Run `ls`, this lists the files in the directory you're in. You should see the hcml-fairml-curriculum folder
7. `cd` into the folder by running `cd hcml-fairml-curriculum`
8. Now, run `pip install -r requirements.txt` to install Python dependencies
9. Run `jupyter nbextension enable --py widgetsnbextension` to make sure interactive widgets are enabled
10. Run `jupyter notebook` to run Jupyter from the main folder
11. Execute notebook `What happens when the data is racially discriminatory?` to interact with the DT


References:
1. https://towardsdatascience.com/interactive-visualization-of-decision-trees-with-jupyter-widgets-ca15dd312084
