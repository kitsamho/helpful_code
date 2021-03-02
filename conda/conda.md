# Conda Commands
---
### create a new conda environment with specificed python version
conda create -n <environment_name> python=x.x anaconda

### activate environment
conda activate <environment_name>

### deactivate environment
conda activate <environment_name>

### view environments
conda env list

### remove an environment
conda env remove --name <environment_name>

### install requirements but skip failed libraries
cat <requirements.txt>| xargs -n 1 pip install

### check version of library / package
pi freeze | grep <libary>
