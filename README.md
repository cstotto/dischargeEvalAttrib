# Repository purpose
Repository for the visualization of the discharge data needed for 
i) the ISIpedia article on the discharge evaluation paper of Heinicke et al.
ii) the programming exercise on discharge evaluation and attribution.
## Installation
The visualization is demonstrated in a [Jupyter notebook]((https://jupyter.org/)) using the python programming language.
1. **Clone repository:** Clone the repository in a local directory, which we may name **dischargeEvalAttrib**:  
```
git clone git@github.com:cstotto/dischargeEvalAttrib.git dischargeEvalAttrib
```
2. **Install anaconda:** Download and update the latest version of [Anaconda](https://www.anaconda.com/). Execute it.
3. **Dependencies:** The file **dischargeEvalAttrib.yml** in the **dependencies** folder lists the required packages. You can use it to initialize a virtual conda environment. 
Open a terminal, move to the **dischargeEvalAttrib** directory and execute
```
conda env create -f dependencies/dischargeEvalAttrib.yml --name dischargeEnv
```
to create a conda environment with the name **dischargeEnv**.

## Execution
1. Create a folder **discharge_data** in **dischargeEvalAttrib**. Download the zip-archives with the discharge data from [this](https://zenodo.org/records/13839054) zenodo repository and unpack them into the folder **discharge_data**. (You have to be granted access first.)
2. Activate the conda environment with
```
conda activate dischargeEnv
```
2. In the **code** subdirectory you may find the notebook **discharge_visualization.ipynb**. Open it with jupyter-lab, e.g., by execting 
```
jupyter-lab discharge_visualization.ipynb &
```
in the command line.
