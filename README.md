# Cryptocurrency Clustering

Here we will use unsupervised learning models to find alternative and hopefully optimized methods of assembling cryptocurrency portfolios. We will use the elbow method of finding the optimal number of clusters and PCA (principal component analysis) to find the best methods for grouping.

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, HvPlot, Pathlib, Sklearn
- **Framework:** JupyterLab, can also use VS Code
- **Operating Systems:** Microsoft Windows

---

## *Installation Guide*

****
- **1:** Install Jupyter Labs and run it from the terminal. Make sure that you make sure you have an up-to-date version of Python
 [Install and run JupyterLab:](https://jupyter.org/install)
- **2:** Copy URL of this repo
- **3:** Clone folder to this repo and open in jupyter labs
- **4:** Ensure that you have the imports correctly identified to download

---

## *Usage*

**Jupyter Lab**
- Running the code can be done in one of two ways:
    1. You can click the "play" button at the very top of the notebook.
    2. You can click shift + enter on each block of code to run each batch of code as you go through it. 
<img width="350" alt="run preview" src=https://github.com/supersilver1978/bitcoin_arbitrage/blob/main/Resources/run.png>

  ### *Final Product*
  Our goal is to deliver the optimal portfolio of crypto currencies and in doing so we utilized the elbow method to determine optimal groupings and then KMeans to predict price changes utilizing unsupervised learning statistical models with and without principal component analysis.
  
The Elbow method: As you can see below, both sets of data are optimized by using 4 clusters.
  <img width="680" alt="elbow_curves" src="https://github.com/supersilver1978/crypocurrency_portfolios/assets/126728866/49cbed57-03ca-4f56-898b-5a21288247b8">

Original data versus PCA clusters: The charts below demonstrate the difference in the distributions. The PCA clusters have less variance than the original data.

<img width="590" alt="original_clusters" src="https://github.com/supersilver1978/crypocurrency_portfolios/assets/126728866/d0ef8fc5-8905-4a33-98b7-4e43bad528c3">
<img width="633" alt="PCA_clusters" src="https://github.com/supersilver1978/crypocurrency_portfolios/assets/126728866/d70ccce0-457d-4cf5-b189-0a771c7e926c">

  

## *Contributor*

- Michelle Silver
- supersilver1978@hotmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 
