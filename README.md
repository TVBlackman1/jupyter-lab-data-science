To start work with project

1. Create file "tensorflow-gpu-3.yml"

```yaml
name: tensorflow-gpu-3
 
dependencies:
    - python=3.7
    - pip>=19.0
    - jupyterlab=3
    - tensorflow-gpu=2.1.0
    - scikit-learn
    - scipy
    - pandas
    - pandas-datareader
    - matplotlib
    - pillow
    - tqdm
    - requests
    - h5py
    - pyyaml
    - flask
    - boto3
    - pip:
        - bayesian-optimization
        - gym
        - kaggle

```

2. Check your conda envs

```commandline
conda env list
```

3. Create conda env from a file, with absolute path

```commandline
conda env create -v -f C:\Users\vbifm\miniconda3\envs\tensorflow-gpu-3.yml
```

4. Check your conda envs again. Now it must have "tensorflow-gpu-3"
   
5. Start Pycharm project with a selected interpreter.

6. Run in terminal
```commandline
jupyter lab
```