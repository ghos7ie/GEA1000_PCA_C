# GEA1000_PCA_C
Pre Course Assignment C
Formulate a few meaningful quantitative questions about the data and use any software of your choice to answer those questions.
Time limit: 2h (Probably spent 2.5h)
Breakdown: 1h spent on setting up :')


Things learnt:

## How to create virtual environment for Jupyter Lab
source: https://www.linkedin.com/pulse/how-use-virtual-environment-inside-jupyter-lab-sina-khoshgoftar
```python
	pip3 install --user virtualenv
	python3 -m venv my-venv
	
	## Activate
	.\my-venv\Scripts\activate
	## Deactivate
	.\my-venv\Scripts\deactivate
	
	pip3 install jupyterlab ipykernel matplotlib numpy (to install whatever you need since you're inside the venv)
	
	python -m ipykernel install --user --name=my-venv
```

- Forgot a lot about using pandas etc. Might come back to try again if I have the time to tackle:
    - Plotting
    - Properly calculating median by exluding all the - values, rather than replacing them with 0 immediately.