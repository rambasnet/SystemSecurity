# Ethical Hacking

- Fundamentals of System & Network Exploitation
- Hacking Tricks, Techniques & Tools
- C++, Python, and Bash

# Requirements

- Ubuntu/Debian Linux Bash
- g++
- Jupyter Notebook
- Python 3
- gdb
- peda - https://github.com/longld/peda

# Install Required Tools
- update Linux and install tools
- Install Python 3.x Miniconda for Linux: https://conda.io/en/latest/miniconda.html

```bash
bash update
curl -o Miniconda.sh https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda.sh # pick defaults; python 3 is installed!
conda update conda
conda install notebook # jupyter notebook
conda install -c conda-forge xeus-cling #c++ kernel
```

# Play with Notebooks

- Clone/download this repository
- Compile and run C programs found in demo-programs folder
- Using a terminal cd into the repo folder and run `jupyter notebook`

```bash
jupyter notebook
```
- open the link shown in a browser if it's not opened on its own
- Open 00-Introduction.ipynb chapter and access all the notebooks
