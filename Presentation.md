



# Extract useful data from RNA-seq results in WT and transgenic tomato fruits

              
              
              Haiping Liu Ph.D

## Introduction
Material

RNA-seq results from amiR396 (miR396 overexpressed) and STTM396 (miR396 being silenced) tomato fruits

Objective

Visualization of RNA-seq data, especially extract differentially expressed genes I am interested in.

## Overview

1. Import CVS file
2. Evaluation the quality of RNA-seq results (histogram and PCA)
3. Display how many genes are differentially expressed (how many up- or down-regulated).
4. Display genes with annotation including targeted words


## Load the libraries

```
import matplotlib.pyplot as plt
import seaborn as sns
import os
import pandas as pd
import numpy as np

```

## Write functions

```
#Read cvs file named 'DEG_ anno.csv''
df = pd.read_csv('/Users/haipingliu/Desktop/BiOF309/Final_project/DEG_ anno.csv')

```

![Read columns](/Users/haipingliu/Desktop/BiOF309/Final_project/keyes.jpg)








