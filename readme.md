# HCML - Examining Fairness in ML Models: A Case Study
### A curriculum designed for Human-Centered Machine Learning (Fall 2020) with Dr. Stevie Chancellor at Northwestern University

### by Ally Reith, Aristana Scourtas, Natalie Araujo Melo, Victor Bursztyn, Zane Denmon

# Getting started
The Jupyter notebook for this curriculum was tested with Python 3.7 - 3.8 on MacOS. We recommend the instructor or teaching assistants walk through the installation steps with the students, or complete the installation ahead of classtime. 

## Setup steps on MacOS:
1. Go to the `Applications` folder on your computer, and open `Terminal` to access the commandline
2. Enter the command `brew install graphviz` to use Homebrew to install `graphviz` on Mac OS ([see here](https://brew.sh/) if you don't have Homebrew installed)
3. In the Terminal, navigate to the directory you want to install the workshop files to by running the command `cd <directory_path>`. For example, if I wanted to download everything to my Desktop, I'd run `cd ~/Desktop` 
4. Now you should be in the right directory! Run `pwd` to ensure you're in the directory you want to be in
5. Great! Pull down the workshop files by running `git clone https://github.com/vbursztyn/hcml-fairml-curriculum.git`
6. Run `ls`, this lists the files in the directory you're in. You should see the hcml-fairml-curriculum folder
7. `cd` into the folder by running `cd hcml-fairml-curriculum`
8. Now, run `pip install -r requirements.txt` to install Python dependencies to the environment of your choice. We'd recommend setting up a [virtual environment](https://medium.com/@nrk25693/how-to-add-your-conda-environment-to-your-jupyter-notebook-in-just-4-steps-abeab8b8d084)
9. Run `jupyter nbextension enable --py widgetsnbextension` to make sure interactive widgets are enabled
10. Run `jupyter notebook` to run Jupyter from the main folder
11. Execute notebook `WOKE ML Lab.ipynb` to run the lab and interact with the decision tree


References:
1. https://towardsdatascience.com/interactive-visualization-of-decision-trees-with-jupyter-widgets-ca15dd312084
