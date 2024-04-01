<p align="center">
    <img src="freemocap/assets/pics/1711338866664.png" height="300" alt="Project Logo">
</p> 


<h3 align="center">MoveSync</h3>
<h4 align="center"> Introducing an open-source, hardware-agnostic, cost-effective motion capture system and platform, designed for decentralized scientific research, education, and training, ensuring accessibility and flexibility across diverse disciplines.</h2>


<p align="center">


  </a>


</p>





--
## QUICKSTART

#### 0. Create a a Python 3.9 through 3.11 environment (python3.11 recommended)¶
#### 1. Install software via [pip](https://pypi.org/project/freemocap/#description):

```
pip install freemocap
```

#### 2. Launch the GUI by entering the command:

```
freemocap
``` 

####  3. A GUI should pop up that looks like this: 

   <img width="1457" alt="image" src="freemocap/assets/pics/main window.PNG">

#### 4. Have fun! It might break!  Work in Progress lol





___
## Install/run from source code (i.e. the code in this repo)

Open an [Anaconda-enabled command prompt]() (or your preferred method of environmnet management) and enter the following commands:

1) Create a `Python` environment (Recommended version  is python3.11)

```bash
conda create -n movesync-env python=3.11
```

2) Activate that newly created environment

```bash
conda activate movesync-env
```

3) Clone the repository

```bash
git clone https://github.com/movesync/movesync
```

4) Navigate into the newly cloned/downloaded `movesync` folder

```bash
cd movesync
```

5) Install the package via the `pyproject.toml` file

```bash
pip install -e .
```

6) Launch the GUI (via the freemocap.__main__.py entry point)

```bash
python -m freemocap
```

A GUI should pop up!

___

## Documentation 

Our documenation is hosted at: https://github.com/movesync/movesync


