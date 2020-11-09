# HCML - Examining Fairness in ML Models: A Case Study
### Professor Stevie Chancellor, Fall 2020.
### Ally Reith, Aristana Scourtas, Natalie Mello, Victor Bursztyn, Zane Denmon.

Steps:
1. Run `brew install graphviz` to install graphviz on Mac OS
2. Run `pip install -r requirements.txt` to install Python dependencies
3. Run `jupyter nbextension enable --py widgetsnbextension` to make sure interactive widgets are enabled
4. Run `jupyter notebook` to run Jupyter from the main folder
5. Execute notebook `What happens when the data is racially discriminatory?` to interact with the DT
5.1. Place the slider on 1.0 to use the original data
5.2. Place the slider close to 2.0 to distort the data against predominantly African-American communities

P.S. The slider triggers model fitting & rendering for each incremental change, so you may need to wait a bit when making greater changes in the slider.