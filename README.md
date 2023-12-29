# Jason Bike Rental Dashboard ✨

## Setup environment
```
%%writefile dashboard.py
import streamlit as st
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from babel.numbers import format_currency
sns.set(style='dark')
```

## Run steamlit app
```
!streamlit run dashboard.py & npx localtunnel --port 8501
```
