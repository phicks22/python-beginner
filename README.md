# Fundamentals of Python (some of them)
---
## Quick note
This repository is a work-in-progress. If you run into issues, please submit an issue on my github repo page [here](https://github.com/phicks22/python-beginner/issues).

I used MacOS to install and use everything in this repository. There shouldn't be differences between MacOS and Windows here, but submit an issue if you encounter any.

---
## Installing things
You'll need Anaconda and an IDE that can use Jupyter notebook for this.

#### IDE
A good IDE that I use is VSCode. Follow the instructions [here](https://code.visualstudio.com/download) to download.

#### Anaconda
Anaconda is a package manager that allows you to create virtual environments that contain modules that you need to use for a specific repository. This prevents dependency errors and conflicting package versions.

To install conda, go [here](https://www.anaconda.com/products/distribution) and follow the instructions.

---
## Download my repository
Open your terminal and move to the directory where you want this repository to live using the `cd` (change directory) terminal command.

_Side Note_: If you're interested in understanding terminal functions, see this tutorial [here](https://tutorials.codebar.io/command-line/introduction/tutorial.html).

Example:
```bash
cd Documents/some_folder
```

Next, copy the repository address from my repository.

![Cloning](imgs/clone.png)

Run the following in the terminal (git clone + what you copied):
```bash
git clone https://github.com/phicks22/python-beginner.git
```

You now have a copy of my repository on your local machine.

To open the code in VSCode do the following:
* File
* Open Folder
* Open python-beginner

---
## Activating the Anaconda environment
Make sure you're in the main directory of the repository (`'path/to/python-beginner'`).

Next, run this in the terminal:
```bash
conda env create -n python-beginner
```

This will generate a virtual environment with all necessary packages for this repository. Now we have to activate it:
```bash
conda activate python-beginner
```

Your environment should be good to go.

**Note:** Make sure that VSCode is using your environment as the kernel for the Jupyter files.

Follow these instructions:
![kernel setup](imgs/kernel_setup.png)

---
## Complete the modules
In order from `0.data_types.ipynb` to `4.exercises.ipynb`

To run code cells, click the run button.
**Note:** Code cells must be run in order to ensure all downstream variables are generated.

![run code cells](imgs/run_cells.png)
