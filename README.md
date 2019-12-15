# Introduction to Datascience 2019 Project
## [Kaggle Competition - Nomad2018 Predicting Transparent Conductors](https://www.kaggle.com/c/nomad2018-predict-transparent-conductors/)

Transparent, conductive materials are a unique class of compounds, which have both: electrical conductivity and low absorbance in the visible range. These materials can be used in a large number of applications such as energy-conserving windows and solar cells.In spite of appealing properties relatively low number of compounds possess such properties. As the number of possible materials is large, to select compounds for experimental verification, computational screening of candidates is necessary. Lowering the cost of screening and increasing its accuracy,  would benefit the discovery of these materials by reducing the development costs. 

Using machine learning methods we have estimated the band gap and formation energy of materials. The models were trained using attributes, which describe the symmetry of crystal combined with qualities that describe crystal’s chemical environment.

In addition to SKLearn, Pandas, MatPlotLib and NumPy the project uses Atomic Simulation Environment (ASE) python package
    pip install --upgrade --user ase

Project is divided into:
  * Jupyter Notebooks:
    * helper_functions.ipynb - Notebook containing useful functions that are used multiple times
    * Data preparation.ipynb - Notebook for calculating additional features e.g. coordination numbers, partial charges
    * Data exploration.ipynb - Notebook for exploration of data and visualizing it
    * Model Training Heigo.ipynb - Notebook containing preliminary models built by Heigo
    * test_notebook.ipynb - Notebook containing preliminary models built by Taido, can be ignored
    * Model training 2.ipynb - Notebook containing Stacked model
  * .csv files:
    * additionalAttributes.csv - Calculated additional attributes for Training data
    * additionalAttributesTest.csv - Calculated additional attributes for Test data
    * test.csv - Data provided by Kaggle for Test data
    * train.csv - Data provided by Kaggle for Training data
  * Folders:
    * test - Folder containing geometries of materials of Test data
    * train - Folder containing geometries of materials of Training data
    * Figures - Folder containing figures used in poster
