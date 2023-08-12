# python-data-analysis
Python for Data Analysis -- Data Wrangling with Pandas, NumPy &amp; Jupyter, 3rd rdition



## Environment

1. Necessary Packages

```shell
#conda config --add channels conda-forge
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/
#conda config --set channel_priority strict
```

2. a new conda env

```shell
conda create -y -n pydata-book python=3.10
conda activate pydata-book
# optional 
## update conda (may need admin priviledge)
conda update -n base -c defaults conda
## or
conda install conda=23.7.2

```

3. install essential pkg 

```shell
 conda install -y pandas jupyter matplotlib
 ## or install all packages
 conda install lxml beautifulsoup4 html5lib openpyxl \
               requests sqlalchemy seaborn scipy statsmodels \
               patsy scikit-learn pyarrow pytables numba
               
        
```

4. code console output settingas

```shell
import numpy as np
import pandas as pd
pd.options.display.max_columns = 20
pd.options.display.max_rows = 20
pd.options.display.max_colwidth = 80
np.set_printoptions(precision=4, suppress=True)
```

5. import conventions

```shell
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import statsmodels as sm
```



