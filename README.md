# PLUS_softwaredev_2024_even_superuniquer
Repo for git practice in the Software Development Course at PLUS.
> [!NOTE]
> This README is also used for trying out Markdown formatting!


# Assignment 2: Environment Recreation Process

This document outlines the process of recreating two Conda environments based on the provided environment files: `software_dev_v1.yml` and `software_dev_v2.yml`. These environment files describe the same environment but differ in specificity and OS dependency.

## Acquisition

1. **Download Files**: Obtained the environment files by forking the provided repository:
   - `software_dev_v1.yml`
   - `software_dev_v2.yml`

![grafik](https://github.com/DavidRMGraf/PLUS_softwaredev_2024_even_superuniquer/assets/50865182/3bea69c5-6acf-4121-b116-8ebfda1711d4)

## Recreated Environments

2. **Using Conda Command Line Recreated Environment 1 (`software_dev_v1.yml`)**:
   - changed directory to the right directory
   - created an environment from the first file, giving it a proper name:

```
cd .\geo-software-dev\A2\
conda env create -f software_dev_v1.yml -n software_dev_env_1
```
![grafik](https://github.com/DavidRMGraf/PLUS_softwaredev_2024_even_superuniquer/assets/50865182/999ff36a-2443-48bb-b70a-e6b23d0e42bd)

That worked just as intended, installed quite some packages in a few minutes.

3. **Using Conda Command Line Recreated Environment 1 (`software_dev_v2.yml`)**:
  - same process as above, changing the file to `software_dev_v2.yml` and choosing a new name: 

```
conda env create -f software_dev_v2.yml -n software_dev_env_2
```
![grafik](https://github.com/DavidRMGraf/PLUS_softwaredev_2024_even_superuniquer/assets/50865182/ae538021-a1fa-4997-b150-cf03fc608ec1)

Again, this worked without issues!


<!--
## Update from Rohit

### Introduction
In this update, I've added two new files to the repository: a notebook file and a Python file.

### Usage of Notebook and Python Files
I typically use Jupyter Notebook to test my code. Whenever I have an idea or want to experiment with code, I first create a Python notebook and try out my ideas there. Once I'm satisfied with the results, I transfer the code to a Python file for further development or production use.

#### Running Python Files
You can run Python files (`.py`) using the Python terminal as follows:

1. **Navigate to the Folder:**
   Open a terminal and go to the folder containing the `.py` file.

2. **Run the File:**
   Use the following command to execute the Python file:
    `rohitSecrets.py`

-->

