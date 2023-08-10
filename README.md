<h1 align="center" id="title">✨ SANDCASTL ✨</h1>

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

*   Note: This package is a Jupyter Notebook and that each piece of code needs to run before preforming the MCMC simulation. 

```
1) Put in the full directory of your input file, remember that this has to be readable by SPLAT.  
2) Put in the output directory for your output file, DO NOT PUT A FILE TYPE.  
3) Input the number of threads you want this code to run on. If you do not know how many your computers have simply input 1.  
4) Input the number of walkers you want to use, the programmer intended for 25 walkers.  
5) Input the number of steps you want the walkers to use, may change on the quality of your spectra.  
6) Finally, input the number of discard you choose, the recommended amount is ~15% the number of steps. 
```

* Once these steps are complete click the "Run All" button to run all code snippets. Follow where the code is running. Note that it may take a few minutes to fully run. 
* Once the code is completed running there will be 9 outputs. One under the "Finds the Best Values and the Errors From the Model" title slide. The second is the output is a total figure of how the walkers explore the parameter space, the observed spectrum compared to the best fit line, and a corner plots with the parameters included. The last 7 are the parameter values and how the walkers explore the parameter space, the best-fit spectrum, and the flatted sample from the MCMC simulation. 

<h2> 📞 Support </h2>

Mr. Hunter Brooks -> hcb98@nau.edu

<h2> 📖 Acknowledgments </h2>

1) Please Use the SPLAT Acknowledgement at: https://github.com/aburgasser/splat
2) Please Cite Brooks et al, in prep (2023/24)
