Software needs to be installed
1. Install Python
2. Install Pycharm
-----------------------------------------------------------
3. Install libs needs (open terminal in pycharm to install):

pip install dash dash-bootstrap-components ipywidgets
pip install folium plotly jupyter-dash fontawesome mpld3
pip install pandas numpy matplotlib seaborn squarify sklearn scikit-learn
-----------------------------------------------------------
4. Run project without doing anything

import folium
from folium.plugins import HeatMap

import ipywidgets as widgets
from IPython.display import display, clear_output

import pandas as pd
from pandas.api.types import CategoricalDtype

import numpy as np

import matplotlib
from matplotlib import pyplot as plt

import ipywidgets as widgets
from IPython.display import display

import seaborn as sns
import squarify
import datetime as dt
from math import sqrt, pow
import seaborn as sns

from sklearn.preprocessing import LabelEncoder,StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

import plotly.express as px
import plotly.graph_objects as go
from plotly.subplots import make_subplots	
import plotly.io as pio
import plotly.offline as py
