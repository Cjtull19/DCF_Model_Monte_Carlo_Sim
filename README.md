# META-DCF-Model-and-Monte-Carlo-Simulation

This Project Enhances a Discounted Cash Flow Model built in Excel with a Monte Carlo Simulation executed in a Jupyter Notebook

<img> </img>
## Languages / Packages Used

1. Python
2. <a href = "https://docs.xlwings.org/en/stable/installation.html" >Xlwings</a>
3. <a href = "https://www.statsmodels.org/stable/index.html" >Statsmodels</a>
4. <a href = "https://pandas.pydata.org/docs/getting_started/index.html" >Pandas</a>
5. <a href = "https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html" >Matplotlib.pyplot</a>
6. <a href = "https://numpy.org/numpy-financial/latest/index.html" >Numpy Financials</a>
7. <a href = "https://scikit-learn.org/stable/" >scikit-learn</a>

> [!NOTE]  
> For ease of use it is reccomended that the code is opened via Jupyter Lab/Notebook using the Anaconda Navigator.

## Financial Data Utilized
- All data was sourced ditecly from the <a href = "https://www.sec.gov/edgar/searchedgar/companysearch" >SEC</a> using the EDGAR tool.
- The Model is currently built with annual 10k information provided by META but can be repurposed for any other organization.


## Instructions

<ol>
  
 <li> Ascertain that the above Packages have been Imported prior to restarting the Kernel.</li>
  <br>
  <li> The Excel Portion of this model needs to be downloaded if changes to working assumptions need to be made (Income Statement CAGR, Fixed Asset / Intangible Asset assumptions etc..) prior to running the Monte Carlo Simulation in Jupyter Notebook /Lab.</li>
  <br>
  <li> Once Assumptions Have been defined Restart the Jupyter Kernal so that the Excel data can be extracted to the Jupyter Note Book.</li>
 <br>
 <li> An instance of the main Class has been already defined. One can initalize a new class instance and change the Standard deviation assumptions for WACC and Terminal Growth Rate.</li>  
  <ol/>
<br>
    
> [!IMPORTANT]  
> It is Highly Recommended that a copy of the Excel model is Taken prior to running the Kernel. This is to avoid any immutable changes to the Original model caused by Xlwings.


  

  
  
   
