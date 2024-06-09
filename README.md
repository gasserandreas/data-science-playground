# DataScience Playground

DataScience Playground to test out various AI/ML ideas.

## To start
1. active conda environment `conda activate mlp`
2. start Jupyter Notebook environment: `jupyter lab --port=8888 --no-browser --NotebookApp.token="local-token"


## Create new conda env and install dependencies
1. Create new conda env: `conda create --name conda-env python=3.8`
2. Activate conda new env: `conda activate conda-env`
3. Install tensorflow dependencies: `conda install -c apple tensorflow-deps`
4. Install Apple Tensorflow dependencies: `pip install tensorflow-macos tensorflow-metal`
5. Add Jupyter to environment: `conda install -c conda-forge -y jupyter`
6. Install basic Python dependencies: `conda install pandas numpy`