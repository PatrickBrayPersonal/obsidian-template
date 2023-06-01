# Properties
1. modular
2. configurable
3. separable
	1. I should be able to run part of the pipeline
		1. or the whole thing if I want
5. standardized

# Design 20230506
## Modules
### Data
- read
	- read data from sources
- write
	- write data to destinations
- transform
### features
- build
	- takes config
### models
- models
- train
- predict
### visualization
- visualizations
### interactive
streamlit.py
### evaluate
only interaction with mlflow
don't use autolog. its too slow
