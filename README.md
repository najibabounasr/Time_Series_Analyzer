# Time_Series_Analyer
Using Time-Series models to evaluate user-data, and to identify consumer trends and price trends in the e-commerce space.


##  Background 

You’re a growth analyst at MercadoLibreLinks to an external site.. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.



## Features and Implementation - Vision and Results:

 In a bid to drive revenue, you’ll produce a Jupyter notebook that contains your data preparation, analysis, and visualizations for all the time series data that the company needs to understand. You’ll use text and comments to document your findings, and you’ll answer the question prompts in the instructions. Specifically, this file should contain the following:

Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

An evaluation of how the company’s stock price correlates to its Google Search traffic.

A Prophet forecast model that can predict hourly user search traffic.

Answers to questions in the instructions that you write in your Jupyter Notebook.

(Optional) A plot of a forecast for the company’s future revenue.

Push your final notebook to your GitHub repository so that others can review your work.


## Technologies

### Instructions
First, configure a Google Colab workspace as follows:

Open Google ColabLinks to an external site. and upload your starter notebook.

Run the provided code in the Install and import the required libraries and dependencies section.

The first cell will install the necessary libraries into the Google Colab runtime.
The second cell will import the dependencies for use in the notebook.
With your workspace configured, you can begin the Challenge. The instructions are divided into four steps and an optional fifth step, as follows:

Step 1: Find unusual patterns in hourly Google search traffic

Step 2: Mine the search traffic data for seasonality

Step 3: Relate the search traffic to stock price patterns

Step 4: Create a time series model with Prophet

Step 5 (optional): Forecast revenue by using time series models


### Required Packages :
 


The following python modules are also used in the application. Remember to install these packages via Terminal for MacOS/Linux or GitBash for windows clients. 



*[tokenize]
(https://docs.python.org/3/library/tokenize.html)
- The tokenize module provides a lexical scanner for Python source code, implemented in Python. The scanner in this module returns comments as tokens as well, making it useful for implementing “pretty-printers”, including colorizers for on-screen displays.

*[datetime]
(https://docs.python.org/3/library/datetime.html)
- The datetime module supplies classes for manipulating dates and times.

While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.



*[fbprophet]
(https://pypi.org/project/fbprophet/)
-Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.


* [pandas](https://github.com/pandas-dev/pandas) 
- pandas is used to interact with data packages, plot data frames, create new dataframes, describe abailable data, and helps traders and fintech proffesionals organize financial data to perform advanced decisionmaking. 

* [pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py) - Allows the user to specify the path to a data frame / any data in a csv file. 

* [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Pandas_API.html)
- If hvplot and pandas are both installed, then we can use the pandas.options.plotting.backend to control the output of pd.DataFrame.plot and pd.Series.plot. This notebook is meant to recreate the pandas visualization docs.

* [numpy]
(https://github.com/numpy/numpy)
- NumPy is the fundamental package for scientific computing with Python. It provides: a powerful N-dimensional array object, sophisticated (broadcasting) functions tools for integrating C/C++ and Fortran code, useful linear algebra, Fourier transform, and random number capabilities. 

* [os]
(https://docs.python.org/3/library/os.html)
- This module provides a portable way of using operating system dependent functionality. If you just want to read or write a file see open(), if you want to manipulate paths, see the os.path module, and if you want to read all the lines in all the files on the command line see the fileinput module. For creating temporary files and directories see the tempfile module, and for high-level file and directory handling see the shutil module..

* [io]
(https://docs.python.org/3/library/io.html)
- The io module provides Python’s main facilities for dealing with various types of I/O. There are three main types of I/O: text I/O, binary I/O and raw I/O. These are generic categories, and various backing stores can be used for each of them. A concrete object belonging to any of these categories is called a file object. Other common terms are stream and file-like object.

* [sys]
(https://docs.python.org/3/library/sys.html)
- This module provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter. It is always available.

* [setuptools]
(https://pypi.org/project/setuptools/)
- setuptools is a pypi component included in the Tidelift Subscription
Tidelift is working with the maintainers of setuptools and a growing network of open source maintainers to ensure your open source software supply chain meets enterprise standards now and into the future.



## Installation Guide

There are four installations neccesary for the program to run. Install all modules and libraries neccesary by first activating your conda dev environment via terminal (for MacOS) or GitBash (Windows/Linux) command : ''' conda activate dev'''. 

After activating the dev environment, install the following libraries via. the command line :

'''python
    pip3 install pandas
    pip3 install numpy
    pip3 install pathlib
    conda install -c pyviz hvplot geoviews
    conda install -c conda-forge voila
    pip install SQLAlchemy
    pip install json
    conda install os
    conda install requests
    pip install alpaca_trade_api
'''

Then, in google colab, import the following modules in the program :

'''
!pip install pystan~=2.14
!pip install fbprophet
!pip install hvplot
!pip install holoviews
!pip install cmdstanpy>=1.0.4
'''
## Usage

In this application, you’ll create charts with hvPlot and use the Facebook Prophet libraryLinks to an external site. to analyze time series data.

The Facebook Prophet library can be difficult to install on some machines, so in this module you'll also get acquainted with Google Colab - an IDE that allows you to run Jupyter Notebooks in the cloud. Before beginning the module, take a moment to watch the following demonstration video showing how to open a notebook in Google Colab, install the necessary libraries and import data.

(https://www.youtube.com/watch?v=nHaDm_CFCwA)



NOTE : remember to be in the application folder (clone) when inputing the command.
---


## Contributors

The sole contributor for this project is:

**NAJIB ABOU NASR**
 no instagram or linkedin yet!
---

## License

Using the 'MIT' license!
--- 

## History

### 
    Here, I documented my command line inputs, to show the changes I had made, and document the debugging and programing process:  
---


## Full List of Installed Libraries and Dependencies :


Name                ,    Version         ,          Build  Channel
_anaconda_depends      ,   2022.10      ,            py39_2  
_ipyw_jlab_nb_ext_conf   , 0.1.0      ,      py39hecd8cb5_1  
alabaster             ,    0.7.12     ,        pyhd3eb1b0_0  
anaconda               ,   custom      ,             py39_1  
anaconda-client        ,   1.11.0     ,      py39hecd8cb5_0  
anaconda-navigator     ,   2.3.2    ,        py39hecd8cb5_0  
anyio                   ,  3.5.0     ,       py39hecd8cb5_0  
appdirs                 ,  1.4.4      ,        pyhd3eb1b0_0  
applaunchservices       ,  0.3.0       ,     py39hecd8cb5_0  
appnope                 ,  0.1.2       ,    py39hecd8cb5_1001  
appscript               ,  1.1.2       ,     py39h9ed2024_0  
argon2-cffi             ,  21.3.0      ,       pyhd3eb1b0_0  
argon2-cffi-bindings    ,  21.2.0      ,     py39hca72f7f_0  
arrow                   ,  1.2.3       ,     py39hecd8cb5_0  
astroid                 ,  2.11.7      ,     py39hecd8cb5_0  
astropy                ,   5.1         ,     py39h67323c0_0  
atomicwrites            ,  1.4.0       ,               py_0  
attrs                   ,  22.1.0      ,     py39hecd8cb5_0  
automat                 ,  20.2.0      ,               py_0  
autopep8                ,  1.6.0       ,       pyhd3eb1b0_1  
babel                     2.11.0      ,     py39hecd8cb5_0  
backcall                  0.2.0       ,       pyhd3eb1b0_0  
backports                 1.1         ,       pyhd3eb1b0_0  
backports.functools_lru_cache 1.6.4    ,          pyhd3eb1b0_0  
backports.tempfile        1.0          ,      pyhd3eb1b0_1  
backports.weakref         1.0.post1    ,              py_1  
bcrypt                    3.2.0         ,,   py39hca72f7f_1  
beautifulsoup4            4.11.1       ,    py39hecd8cb5_0  
binaryornot               0.4.4        ,      pyhd3eb1b0_1  
bitarray                  2.5.1            py39hca72f7f_0  
bkcharts                  0.2              py39hecd8cb5_1  
black                     21.7b0                   pypi_0    pypi
blas                      1.0                         mkl  
bleach                    4.1.0              pyhd3eb1b0_0  
blosc                     1.21.3               hcec6c5f_0  
bokeh                     2.4.3            py39hecd8cb5_0  
boto3                     1.24.28          py39hecd8cb5_0  
botocore                  1.27.59          py39hecd8cb5_0  
bottleneck                1.3.5            py39h67323c0_0  
brotli                    1.0.9                hca72f7f_7  
brotli-bin                1.0.9                hca72f7f_7  
brotlipy                  0.7.0           py39h9ed2024_1003  
brunsli                   0.1                  h23ab428_0  
bzip2                     1.0.8                h1de35cc_0  
c-ares                    1.18.1               hca72f7f_0  
ca-certificates           2023.01.10           hecd8cb5_0  
cctools                   949.0.1             h9abeeb2_25  
cctools_osx-64            949.0.1             hc7db93f_25  
certifi                   2022.12.7        py39hecd8cb5_0  
cffi                      1.15.1           py39hc55c11b_0  
cfitsio                   3.470                hee0f690_6  
chardet                   4.0.0           py39hecd8cb5_1003  
charls                    2.2.0                h23ab428_0  
charset-normalizer        2.0.4              pyhd3eb1b0_0  
click                     8.0.4            py39hecd8cb5_0  
cloudpickle               2.0.0              pyhd3eb1b0_0  
clyent                    1.2.2            py39hecd8cb5_1  
colorama                  0.4.6            py39hecd8cb5_0  
colorcet                  3.0.1            py39hecd8cb5_0  
comm                      0.1.2            py39hecd8cb5_0  
conda                     23.1.0           py39hecd8cb5_0  
conda-build               3.22.0           py39hecd8cb5_0  
conda-content-trust       0.1.3            py39hecd8cb5_0  
conda-env                 2.6.0                         1  
conda-package-handling    2.0.2            py39hecd8cb5_0  
conda-package-streaming   0.7.0            py39hecd8cb5_0  
conda-repo-cli            1.0.27           py39hecd8cb5_0  
conda-token               0.4.0              pyhd3eb1b0_0  
conda-verify              3.4.2                      py_1  
constantly                15.1.0             pyh2b92418_0  
contourpy                 1.0.5            py39haf03e11_0  
cookiecutter              1.7.3              pyhd3eb1b0_0  
cryptography              38.0.4           py39hf6deb26_0  
cssselect                 1.1.0              pyhd3eb1b0_0  
curl                      7.87.0               h6c40b1e_0  
cycler                    0.11.0             pyhd3eb1b0_0  
cython                    0.29.32          py39he9d5cce_0  
cytoolz                   0.12.0           py39hca72f7f_0  
daal4py                   2021.6.0         py39h01d92e1_1  
dal                       2021.6.0           haf03e11_929  
dask                      2022.2.1           pyhd3eb1b0_0  
dask-core                 2022.2.1           pyhd3eb1b0_0  
dataclasses               0.8                pyh6d0b6a4_7  
datashader                0.14.3           py39hecd8cb5_0  
datashape                 0.5.4            py39hecd8cb5_1  
debugpy                   1.5.1            py39he9d5cce_0  
decorator                 5.1.1              pyhd3eb1b0_0  
defusedxml                0.7.1              pyhd3eb1b0_0  
diff-match-patch          20200713           pyhd3eb1b0_0  
dill                      0.3.6            py39hecd8cb5_0  
distributed               2022.2.1           pyhd3eb1b0_0  
docutils                  0.18.1           py39hecd8cb5_3  
entrypoints               0.4              py39hecd8cb5_0  
et_xmlfile                1.1.0            py39hecd8cb5_0  
filelock                  3.9.0            py39hecd8cb5_0  
fire                      0.5.0                    pypi_0    pypi
flake8                    4.0.1              pyhd3eb1b0_1  
flask                     1.1.2              pyhd3eb1b0_0  
flit-core                 3.6.0              pyhd3eb1b0_0  
fonttools                 4.25.0             pyhd3eb1b0_0  
freetype                  2.12.1               hd8bbffd_0  
fsspec                    2022.11.0        py39hecd8cb5_0  
future                    0.18.2           py39hecd8cb5_1  
gensim                    4.3.0            py39hcec6c5f_0  
gettext                   0.21.0               h7535e17_0  
giflib                    5.2.1                h6c40b1e_1  
glib                      2.69.1               h8346a28_1  
glob2                     0.7                pyhd3eb1b0_0  
gmp                       6.2.1                he9d5cce_3  
gmpy2                     2.1.2            py39hd5de756_0  
greenlet                  2.0.1            py39hcec6c5f_0  
gst-plugins-base          1.14.0               h4180768_2  
gstreamer                 1.14.0               h0fc69c2_2  
h5py                      3.7.0            py39h4a1dd59_0  
hdf5                      1.10.6               hdbbcd12_0  
heapdict                  1.0.1              pyhd3eb1b0_0  
holoviews                 1.15.3           py39hecd8cb5_0  
hvplot                    0.8.2            py39hecd8cb5_0  
hyperlink                 21.0.0             pyhd3eb1b0_0  
icu                       58.2                 h0a44026_3  
idna                      3.4              py39hecd8cb5_0  
imagecodecs               2021.8.26        py39h0f85e6e_1  
imageio                   2.19.3           py39hecd8cb5_0  
imagesize                 1.4.1            py39hecd8cb5_0  
importlib-metadata        4.11.3           py39hecd8cb5_0  
importlib_metadata        4.11.3               hd3eb1b0_0  
incremental               21.3.0             pyhd3eb1b0_0  
inflection                0.5.1            py39hecd8cb5_0  
iniconfig                 1.1.1              pyhd3eb1b0_0  
intake                    0.6.6            py39hecd8cb5_0  
intel-openmp              2021.4.0          hecd8cb5_3538  
intervaltree              3.1.0              pyhd3eb1b0_0  
ipykernel                 6.19.2           py39h01d92e1_0  
ipython                   7.31.1           py39hecd8cb5_1  
ipython_genutils          0.2.0              pyhd3eb1b0_1  
ipywidgets                7.6.5              pyhd3eb1b0_1  
isort                     5.9.3              pyhd3eb1b0_0  
itemadapter               0.3.0              pyhd3eb1b0_0  
itemloaders               1.0.4              pyhd3eb1b0_1  
itsdangerous              2.0.1              pyhd3eb1b0_0  
jdcal                     1.4.1              pyhd3eb1b0_0  
jedi                      0.18.1           py39hecd8cb5_1  
jellyfish                 0.9.0            py39hca72f7f_0  
jinja2                    2.11.3             pyhd3eb1b0_0  
jinja2-time               0.2.0              pyhd3eb1b0_3  
jmespath                  0.10.0             pyhd3eb1b0_0  
joblib                    1.1.1            py39hecd8cb5_0  
jpeg                      9e                   hca72f7f_0  
jq                        1.6               h9ed2024_1000  
json5                     0.9.6              pyhd3eb1b0_0  
jsonschema                4.16.0           py39hecd8cb5_0  
jupyter                   1.0.0            py39hecd8cb5_8  
jupyter_client            7.4.8            py39hecd8cb5_0  
jupyter_console           6.4.4            py39hecd8cb5_0  
jupyter_core              5.1.1            py39hecd8cb5_0  
jupyter_server            1.23.4           py39hecd8cb5_0  
jupyterlab                3.5.1              pyhd8ed1ab_0    conda-forge
jupyterlab_pygments       0.1.2                      py_0  
jupyterlab_server         2.10.3             pyhd3eb1b0_1  
jupyterlab_widgets        1.0.0              pyhd3eb1b0_1  
jxrlib                    1.1                  haf1e3a3_2  
keyring                   23.4.0           py39hecd8cb5_0  
kiwisolver                1.4.4            py39hcec6c5f_0  
krb5                      1.19.4               hdba6334_0  
lazy-object-proxy         1.6.0            py39h9ed2024_0  
lcms2                     2.12                 hf1fd2bf_0  
ld64                      530                 h20443b4_25  
ld64_osx-64               530                 h70f3046_25  
ldid                      2.1.2                h2d21305_2  
lerc                      3.0                  he9d5cce_0  
libaec                    1.0.4                hb1e8313_1  
libarchive                3.6.2                h65c5294_0  
libbrotlicommon           1.0.9                hca72f7f_7  
libbrotlidec              1.0.9                hca72f7f_7  
libbrotlienc              1.0.9                hca72f7f_7  
libclang                  12.0.0          default_hbc2896b_2  
libcurl                   7.87.0               ha585b31_0  
libcxx                    14.0.6               h9765a3e_0  
libdeflate                1.8                  h9ed2024_5  
libedit                   3.1.20221030         h6c40b1e_0  
libev                     4.33                 h9ed2024_1  
libffi                    3.3                  hb1e8313_2  
libgfortran               3.0.1                h93005f0_2  
libiconv                  1.16                 hca72f7f_2  
libidn2                   2.3.2                h9ed2024_0  
liblief                   0.12.3               hcec6c5f_0  
libllvm11                 11.1.0               h46f1229_6  
libllvm12                 12.0.0               h9b2ccf5_3  
libllvm14                 14.0.6               he552d86_0  
libnghttp2                1.46.0               ha29bfda_0  
libpng                    1.6.37               ha441bb4_0  
libpq                     12.9                 h1c9f633_3  
libsodium                 1.0.18               h1de35cc_0  
libspatialindex           1.9.3                h23ab428_0  
libssh2                   1.10.0               h0a4fc7d_0  
libtiff                   4.5.0                hcec6c5f_1  
libunistring              0.9.10               h9ed2024_0  
libwebp                   1.2.4                h56c3ce4_0  
libwebp-base              1.2.4                hca72f7f_0  
libxml2                   2.9.14               hbf8cd5e_0  
libxslt                   1.1.35               h5b33f42_0  
libzopfli                 1.0.3                hb1e8313_0  
llvm-openmp               14.0.6               h0dcd299_0  
llvmlite                  0.39.1           py39h8346a28_0  
locket                    1.0.0            py39hecd8cb5_0  
lxml                      4.9.1            py39h65b224f_0  
lz4-c                     1.9.4                hcec6c5f_0  
lzo                       2.10                 haf1e3a3_2  
markdown                  3.4.1            py39hecd8cb5_0  
markupsafe                2.0.1            py39h9ed2024_0  
matplotlib                3.6.2            py39hecd8cb5_0  
matplotlib-base           3.6.2            py39h220de94_0  
matplotlib-inline         0.1.6            py39hecd8cb5_0  
mccabe                    0.7.0              pyhd3eb1b0_0  
mistune                   0.8.4           py39h9ed2024_1000  
mkl                       2021.4.0           hecd8cb5_637  
mkl-service               2.4.0            py39h9ed2024_0  
mkl_fft                   1.3.1            py39h4ab4a9b_0  
mkl_random                1.2.2            py39hb2f4e1b_0  
mock                      4.0.3              pyhd3eb1b0_0  
mpc                       1.1.0                h6ef4df4_1  
mpfr                      4.0.2                h9066e36_1  
mpi                       1.0                       mpich  
mpich                     3.3.2                hc856adb_0  
mpmath                    1.2.1            py39hecd8cb5_0  
msgpack-python            1.0.3            py39haf03e11_0  
multipledispatch          0.6.0            py39hecd8cb5_0  
munkres                   1.1.4                      py_0  
mypy                      0.910                    pypi_0    pypi
mypy_extensions           0.4.3            py39hecd8cb5_1  
navigator-updater         0.3.0            py39hecd8cb5_0  
nbclassic                 0.4.8            py39hecd8cb5_0  
nbclient                  0.5.13           py39hecd8cb5_0  
nbconvert                 6.4.4            py39hecd8cb5_0  
nbformat                  5.7.0            py39hecd8cb5_0  
ncurses                   6.4                  hcec6c5f_0  
nest-asyncio              1.5.6            py39hecd8cb5_0  
networkx                  2.8.4            py39hecd8cb5_0  
nltk                      3.7                pyhd3eb1b0_0  
nose                      1.3.7           pyhd3eb1b0_1008  
notebook                  6.5.2            py39hecd8cb5_0  
notebook-shim             0.2.2            py39hecd8cb5_0  
nspr                      4.33                 he9d5cce_0  
nss                       3.74                 h47edf6a_0  
numba                     0.56.4           py39h07fba90_0  
numexpr                   2.8.4            py39he696674_0  
numpy                     1.21.5           py39h2e5f0a9_3  
numpy-base                1.21.5           py39h3b1a694_3  
numpydoc                  1.5.0            py39hecd8cb5_0  
olefile                   0.46               pyhd3eb1b0_0  
oniguruma                 6.9.7.1              h9ed2024_0  
openjpeg                  2.4.0                h66ea3da_0  
openpyxl                  3.0.10           py39hca72f7f_0  
openssl                   1.1.1s               hca72f7f_0  
packaging                 22.0             py39hecd8cb5_0  
pandas                    1.4.4            py39he9d5cce_0  
pandocfilters             1.5.0              pyhd3eb1b0_0  
panel                     0.14.2           py39hecd8cb5_0  
param                     1.12.3           py39hecd8cb5_0  
parsel                    1.6.0            py39hecd8cb5_0  
parso                     0.8.3              pyhd3eb1b0_0  
partd                     1.2.0              pyhd3eb1b0_1  
patch                     2.7.6             h1de35cc_1001  
pathlib                   1.0.1              pyhd3eb1b0_1  
pathspec                  0.10.3           py39hecd8cb5_0  
patsy                     0.5.3            py39hecd8cb5_0  
pcre                      8.45                 h23ab428_0  
pep8                      1.7.1            py39hecd8cb5_1  
pexpect                   4.8.0              pyhd3eb1b0_3  
pickleshare               0.7.5           pyhd3eb1b0_1003  
pillow                    9.3.0            py39hcec6c5f_2  
pip                       22.3.1           py39hecd8cb5_0  
pkginfo                   1.8.3            py39hecd8cb5_0  
platformdirs              2.5.2            py39hecd8cb5_0  
plotly                    5.9.0            py39hecd8cb5_0  
pluggy                    1.0.0            py39hecd8cb5_1  
ply                       3.11             py39hecd8cb5_0  
poyo                      0.5.0              pyhd3eb1b0_0  
prometheus_client         0.14.1           py39hecd8cb5_0  
prompt-toolkit            3.0.36           py39hecd8cb5_0  
prompt_toolkit            3.0.36               hd3eb1b0_0  
protego                   0.1.16                     py_0  
psutil                    5.9.0            py39hca72f7f_0  
ptyprocess                0.7.0              pyhd3eb1b0_2  
py                        1.11.0             pyhd3eb1b0_0  
py-algorand-sdk           1.8.0                    pypi_0    pypi
py-lief                   0.12.3           py39hcec6c5f_0  
pyasn1                    0.4.8              pyhd3eb1b0_0  
pyasn1-modules            0.2.8                      py_0  
pycodestyle               2.8.0              pyhd3eb1b0_0  
pycosat                   0.6.4            py39hca72f7f_0  
pycparser                 2.21               pyhd3eb1b0_0  
pycryptodomex             3.16.0                   pypi_0    pypi
pyct                      0.5.0            py39hecd8cb5_0  
pycurl                    7.45.1           py39h0a4fc7d_0  
pydispatcher              2.0.5            py39hecd8cb5_2  
pydocstyle                6.3.0            py39hecd8cb5_0  
pyerfa                    2.0.0            py39h9ed2024_0  
pyflakes                  2.4.0              pyhd3eb1b0_0  
pygments                  2.11.2             pyhd3eb1b0_0  
pyhamcrest                2.0.2              pyhd3eb1b0_2  
pyjwt                     2.4.0            py39hecd8cb5_0  
pylint                    2.14.5           py39hecd8cb5_0  
pyls-spyder               0.4.0              pyhd3eb1b0_0  
pynacl                    1.5.0                    pypi_0    pypi
pyobjc-core               8.5              py39hc55c11b_0  
pyobjc-framework-cocoa    8.5              py39h6c40b1e_1  
pyobjc-framework-coreservices 8.5              py39hca72f7f_0  
pyobjc-framework-fsevents 8.5              py39hecd8cb5_0  
pyodbc                    4.0.34           py39he9d5cce_0  
pyopenssl                 22.0.0             pyhd3eb1b0_0  
pyparsing                 3.0.9            py39hecd8cb5_0  
pyqt                      5.15.7           py39he9d5cce_0  
pyqt5-sip                 12.11.0          py39he9d5cce_0  
pyqtwebengine             5.15.7           py39he9d5cce_0  
pyrsistent                0.18.0           py39hca72f7f_0  
pysocks                   1.7.1            py39hecd8cb5_0  
pytables                  3.7.0            py39h59775c6_1  
pyteal                    0.9.1                    pypi_0    pypi
pytest                    7.1.2            py39hecd8cb5_0  
python                    3.9.13               hdfd78df_1  
python-dateutil           2.8.2              pyhd3eb1b0_0  
python-fastjsonschema     2.16.2           py39hecd8cb5_0  
python-libarchive-c       2.9                pyhd3eb1b0_1  
python-lsp-black          1.2.1            py39hecd8cb5_0  
python-lsp-jsonrpc        1.0.0              pyhd3eb1b0_0  
python-lsp-server         1.5.0            py39hecd8cb5_0  
python-slugify            5.0.2              pyhd3eb1b0_0  
python-snappy             0.6.1            py39hcec6c5f_0  
python.app                3                py39hca72f7f_0  
pytz                      2022.7           py39hecd8cb5_0  
pyviz_comms               2.0.2              pyhd3eb1b0_0  
pywavelets                1.4.1            py39h6c40b1e_0  
pyyaml                    6.0              py39h6c40b1e_1  
pyzmq                     23.2.0           py39he9d5cce_0  
qdarkstyle                3.0.2              pyhd3eb1b0_0  
qstylizer                 0.2.2            py39hecd8cb5_0  
qt                        5.15.9               hecd8cb5_0  
qt-main                   5.15.2               h719ae48_7  
qt-webengine              5.15.9               h90a370e_4  
qtawesome                 1.2.2            py39hecd8cb5_0  
qtconsole                 5.3.2            py39hecd8cb5_0  
qtpy                      2.2.0            py39hecd8cb5_0  
qtwebkit                  5.212                h24dc246_4  
questionary               1.10.0                   pypi_0    pypi
queuelib                  1.5.0            py39hecd8cb5_0  
readline                  8.2                  hca72f7f_0  
regex                     2022.7.9         py39hca72f7f_0  
requests                  2.28.1           py39hecd8cb5_0  
requests-file             1.5.1              pyhd3eb1b0_0  
ripgrep                   13.0.0               hc2228c6_0  
rope                      0.22.0             pyhd3eb1b0_0  
rtree                     1.0.1            py39hecd8cb5_0  
ruamel.yaml               0.17.21          py39hca72f7f_0  
ruamel.yaml.clib          0.2.6            py39hca72f7f_1  
ruamel_yaml               0.17.21          py39hca72f7f_0  
s3transfer                0.6.0            py39hecd8cb5_0  
scikit-image              0.19.3           py39hcec6c5f_1  
scikit-learn              1.0.2            py39hae1ba45_1  
scikit-learn-intelex      2021.6.0         py39hecd8cb5_0  
scipy                     1.7.3            py39h8c7af03_0  
scrapy                    2.6.2            py39hecd8cb5_0  
seaborn                   0.12.2           py39hecd8cb5_0  
send2trash                1.8.0              pyhd3eb1b0_1  
service_identity          18.1.0             pyhd3eb1b0_1  
setuptools                65.6.3           py39hecd8cb5_0  
sip                       6.6.2            py39he9d5cce_0  
six                       1.16.0             pyhd3eb1b0_1  
smart_open                5.2.1            py39hecd8cb5_0  
snappy                    1.1.9                he9d5cce_0  
sniffio                   1.2.0            py39hecd8cb5_1  
snowballstemmer           2.2.0              pyhd3eb1b0_0  
sortedcollections         2.1.0              pyhd3eb1b0_0  
sortedcontainers          2.4.0              pyhd3eb1b0_0  
soupsieve                 2.3.2.post1      py39hecd8cb5_0  
sphinx                    5.0.2            py39hecd8cb5_0  
sphinxcontrib-applehelp   1.0.2              pyhd3eb1b0_0  
sphinxcontrib-devhelp     1.0.2              pyhd3eb1b0_0  
sphinxcontrib-htmlhelp    2.0.0              pyhd3eb1b0_0  
sphinxcontrib-jsmath      1.0.1              pyhd3eb1b0_0  
sphinxcontrib-qthelp      1.0.3              pyhd3eb1b0_0  
sphinxcontrib-serializinghtml 1.1.5              pyhd3eb1b0_0  
spyder                    5.3.3            py39hecd8cb5_0  
spyder-kernels            2.3.3            py39hecd8cb5_0  
sqlalchemy                1.4.39           py39hca72f7f_0  
sqlite                    3.40.1               h880c91c_0  
statsmodels               0.13.5           py39hacda100_0  
sympy                     1.11.1           py39hecd8cb5_0  
tabulate                  0.8.10           py39hecd8cb5_0  
tapi                      1000.10.8            ha1b3eb9_0  
tbb                       2021.6.0             ha357a0b_1  
tbb4py                    2021.6.0         py39ha357a0b_1  
tblib                     1.7.0              pyhd3eb1b0_0  
tenacity                  8.0.1            py39hecd8cb5_1  
termcolor                 2.2.0                    pypi_0    pypi
terminado                 0.17.1           py39hecd8cb5_0  
testpath                  0.6.0            py39hecd8cb5_0  
text-unidecode            1.3                pyhd3eb1b0_0  
textdistance              4.2.1              pyhd3eb1b0_0  
threadpoolctl             2.2.0              pyh0d69192_0  
three-merge               0.1.1              pyhd3eb1b0_0  
tifffile                  2021.7.2           pyhd3eb1b0_2  
tinycss2                  1.2.1            py39hecd8cb5_0  
tk                        8.6.12               h5d9f67b_0  
tldextract                3.2.0              pyhd3eb1b0_0  
toml                      0.10.2             pyhd3eb1b0_0  
tomli                     1.2.3                    pypi_0    pypi
tomlkit                   0.11.1           py39hecd8cb5_0  
toolz                     0.12.0           py39hecd8cb5_0  
tornado                   6.2              py39hca72f7f_0  
tqdm                      4.64.1           py39hecd8cb5_0  
traitlets                 5.7.1            py39hecd8cb5_0  
twisted                   22.2.0           py39hca72f7f_1  
typing-extensions         4.4.0            py39hecd8cb5_0  
typing_extensions         4.4.0            py39hecd8cb5_0  
tzdata                    2022g                h04d1e81_0  
ujson                     5.4.0            py39he9d5cce_0  
unidecode                 1.2.0              pyhd3eb1b0_0  
unixodbc                  2.3.11               hb456775_0  
urllib3                   1.26.14          py39hecd8cb5_0  
w3lib                     1.21.0             pyhd3eb1b0_0  
watchdog                  2.1.6            py39h999c104_0  
wcwidth                   0.2.5              pyhd3eb1b0_0  
webencodings              0.5.1            py39hecd8cb5_1  
websocket-client          0.58.0           py39hecd8cb5_4  
werkzeug                  2.0.3              pyhd3eb1b0_0  
wget                      1.21.3               h6dfd666_0  
whatthepatch              1.0.2            py39hecd8cb5_0  
wheel                     0.37.1             pyhd3eb1b0_0  
widgetsnbextension        3.5.2            py39hecd8cb5_0  
wrapt                     1.14.1           py39hca72f7f_0  
wurlitzer                 3.0.2            py39hecd8cb5_0  
xarray                    2022.11.0        py39hecd8cb5_0  
xlrd                      2.0.1              pyhd3eb1b0_0  
xlsxwriter                3.0.3              pyhd3eb1b0_0  
xlwings                   0.27.15          py39hecd8cb5_0  
xz                        5.2.10               h6c40b1e_1  
yaml                      0.2.5                haf1e3a3_0  
yapf                      0.31.0             pyhd3eb1b0_0  
zeromq                    4.3.4                h23ab428_0  
zfp                       0.5.5                he9d5cce_6  
zict                      2.1.0            py39hecd8cb5_0  
zipp                      3.11.0           py39hecd8cb5_0  
zlib                      1.2.13               h4dc903c_0  
zope                      1.0              py39hecd8cb5_1  
zope.interface            5.4.0            py39h9ed2024_0  
zstandard                 0.18.0           py39hca72f7f_0  
zstd                      1.5.2                hcb37349_0  

