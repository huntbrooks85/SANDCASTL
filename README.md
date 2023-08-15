<h1 align="center" id="title">🏖️ SANDCASTL 🏖️</h1>

<p id="description"> Spectral ANalog of Dwarfs and Computional Analysis of Spectral TempLates (SANDCASTL) is a Python 3 Jupyter Notebook. It allows for a simple input of a reduced spectrum to fit to the newly created SAND model. SANDCASTLE fits for 4 main parameters, including: effective temperature (Teff), surface gravity (Log(g)), metalliticty ([M/H]), alpha enrichment ([α/H]). With 2 additional nuisance parameters of horizontal and veritcal shift. </p>

<h2>🛠️ Installation Steps:</h2>

<p>1. Python </p>

```
-> Python 3.8 or newer is needed for SANDCASTL 
```
* Python 3.8.8 link: https://www.python.org/downloads/release/python-388/
* Python Installation Guide: https://wiki.python.org/moin/BeginnersGuide/Download

<p>2. Packages </p>

* PIP Installation Guide: https://pip.pypa.io/en/stable/installation/
* How to Use PIP: https://packaging.python.org/en/latest/tutorials/installing-packages/
* To Install Required Packages Please Run, "pip install -r requirements.txt", in Your Terminal

<p>3. SPLAT </p>

* The SPLAT Package is required to use this Jupyter Notebook
* To Install SPLAT, Please Use Intructions at: https://github.com/aburgasser/splat

<h2> 🏆 How to Use SANDCASTL: </h2>

*   Note: This package is a Jupyter Notebook and that each piece of code needs to run before preforming the MCMC simulation
*   Note: This package should not be used as a blackbox, please follow and understand this code when using
*   Note: All required variables are put into "Input Requirements" code block
*   Note: Read the comment above each variable for additional notes

```
1) Put input file directory in "input_file" variable
2) Input outfile file name in "output_file" variable
3) Input spectral type estimate in "spt_estimate" variable
4) Input the number of threads in "threads" variable
5) Input the number of walkers in the "walkers" variable
6) Input the number of steps in the "steps" variable
7) Input the number of discards in the "discard" variable
```

* Once the inputs are complete click the "Run All" button (FOLLOW THE CODE)
* Once the notebook is finished running all of the outputs are in the "Output" directory

<h2> 📞 Support </h2>

Mr. Hunter Brooks -> hcb98@nau.edu

<h2> 📖 Acknowledgments </h2>

1) Please Use the SPLAT Acknowledgement at: https://github.com/aburgasser/splat
2) Please Cite Brooks et al, in prep (2023/24)
