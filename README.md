# gswpy
## Introduction
## Install 
```
pip install gswpy
```
## Usage
```python
from gswpy import GSW
lat = np.array([38])
lon = np.array([122])
gsw = GSW().get(lat, lon)
print(gsw)
```
