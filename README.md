# Homework 4: Model Assessment and Comparison

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the repository for Homework 4 for [BEE 4850](https://viveks.me/simulation-data-analysis), taught at [Cornell University](https://cornell.edu) in Spring 2026 by [Vivek Srikrishnan](https://viveks.me).

If enrolled in the class, a PDF of the completed assignment, **with all cells evaluated if a notebook**, should be submitted to Gradescope *no later* than the due date at 9:00pm. The assignment will be penalized 50% if it is submitted up to 24 hours late.

## Learning Objectives

After completing this assignments, students will be able to:

* use cross-validation to assess the generalizability of models and compare model performance;
* use information criteria to compare model predictive skill and draw conclusions about the appropriateness of models.


## Repository Overview

The repository consists of the following files:

- `hw04.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`, `Manifest.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `hw04.qmd`: Source file for Jupyter notebook generation. You shouldn't need to or want to touch this; everything is in the `.ipynb` file.
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `.github/`: This folder contains workflow files which generate the notebook. Again, you shouldn't need to touch this.
- `data/`: This folder contains several .csvs and other data files to complete the projects.

