## Prerequisites
- **Python version:** 3.12.3
  
## Contents 
1. Creating a new virtual “20th_century”
2. Activating the virtual environment
3. Installing the ipykernel library inside the virtual environment
4. Deactivating the virtual environement and launching JupyterLab
5. Creating random data using the pd.DataFrame() function in the new notebook
6. Creating new columns

**1. Creating a new virtual “20th_century”**
   
   ```python
conda create --name 20th_century
   ```
**2. Activating the virtual environment**
```python 
conda activate 20th_century
```
**3. Installing the ipykernel library inside the virtual environment**
```python 
conda install ipykernel
```

**4.  Deactivating the virtual environement and launching JupyterLab**
```python 
conda deactivate
jupyter lab
```
**5. Creating random data using the pd.DataFrame() function in the new notebook**
```python 
conda activate 20th_century
conda install pandas numpy
```
**6.  Creating new columns**
### Explore the ipynb Notebook:
You can explore the full code in the [Notebook](./Task3.ipynb)
