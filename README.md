# Applied Statistics Winter 2025/26
Author: Kirstin Barnett

Hands-on notebook covering core statistical concepts.

## Purpose
This repository contains all the work relating to the Atlantic Technological University module Applied Statistics run in Winter 2025/26. The main file is a Jupyter notebook called [problems.ipynb](https://github.com/kknb1982/applied_statistics/blob/main/problems.ipynb) that works through four problems set out in the module:
1. Extending the lady tasting tea experiment - looks at combinations, permutations and null hypotheses.
2. Normal distribution - looks at what is a normal distribution and the effects of sample size.
3. t-tests - investigates a way of statistically shows a difference in means between datasets and how often the null hypothesis is rejected incorrectly with different intervals between the means.
4. ANOVA - demonstrates ANOVA and why it is preferred over running several t-tests.

## Repository contents
* [problems.ipynb](https://github.com/kknb1982/applied_statistics/blob/main/problems.ipynb): Main notebook with four problems, relevant plots and analysis.
* [requirements.txt](https://github.com/kknb1982/applied_statistics/blob/main/requirements.txt): Python dependencies required for running the code in the problems notebook.
* [.gitignore](https://github.com/kknb1982/applied_statistics/blob/main/.gitignore): Standard list of files to be ignored for Python and Jupyter notebooks.
* [problems.ipynb](https://github.com/kknb1982/applied_statistics/blob/main/problems.ipynb): Main notebook with four problems, relevant plots and analysis.
* [requirements.txt](https://github.com/kknb1982/applied_statistics/blob/main/requirements.txt): Python dependencies required for running the code in the problems notebook.
* [.gitignore](https://github.com/kknb1982/applied_statistics/blob/main/.gitignore): Standard list of files to be ignored for Python and Jupyter notebooks.

## How to install and run the project
### Prerequisites
* Python 3.12 or higher

### Steps
This project only uses the packages listed in [requirements.txt](https://github.com/kknb1982/applied_statistics/blob/main/requirements.txt)
1.  Open a terminal or command prompt 
2. Clone the repository [https://github.com/kknb1982/applied_statistics.git](https://github.com/kknb1982/applied_statistics.git)
3. Check `pip` is present and up-to-date `python -m pip install --upgrade pip`
4. If `pip` is not installed, download it from [https://pypi.org/project/pip/](https://pypi.org/project/pip/). Following the steps in the [installation guide](https://pip.pypa.io/en/stable/installation/)
5. In the command line run `python -m pip install -r requirements.txt`

```
# Clone and enter
git clone https://github.com/kknb1982/applied_statistics.git
cd applied_statistics

# Install dependencies
python -m pip install --upgrade pip
python -m pip install -r requirements.txt

# Open the notebook in VS Code
code problems.ipynb

# OR open with Jupyter
jupyter notebook problems.ipynb
```

## How to use the project
Once the environment is set up, all the code for the problems, explanations and links to further resources is contained within [problems.ipynb](https://github.com/kknb1982/applied_statistics/blob/main/problems.ipynb). The code has been pre-run. The random generators have not been seeded, so re-running the cells produce different results, making it is easy to explore multiple outcomes.

## Credits
Once the environment is set up, all the code for the problems, explanations and links to further resources is contained within [problems.ipynb](https://github.com/kknb1982/applied_statistics/blob/main/problems.ipynb). The code has been pre-run. The random generators have not been seeded, so re-running the cells produce different results, making it is easy to explore multiple outcomes.

**Optional:** For reproducible results, add `np.random.seed(42)` at the start of the notebook.

## Troubleshooting
- **"Module not found" error**: Run `python -m pip install -r requirements.txt`
- **Kernel issues in VS Code**: Command Palette → "Python: Select Interpreter"
- **Plots not displaying**: Ensure `%matplotlib inline` is in the first cell.

# End