
# Table of Contents

1.  [Project checklist](#orgdbcc5c1)
    1.  [Week 1](#org9164bf2)
    2.  [Week 2](#org27a5d55)
    3.  [Week 3](#orga757fcf)
    4.  [Additional](#org487ce4a)
2.  [Project package list](#orgae04bd7)

How do we go about it? Read the checklist -> branch out -> fix the task -> create pull request.


<a id="orgdbcc5c1"></a>

# Project checklist


<a id="org9164bf2"></a>

## Week 1

-   [X] Create a git repository
-   [X] Make sure that all team members have write access to the github repository
-   [ ] Create a dedicated environment for you project to keep track of your packages (using conda)
-   [X] Create the initial file structure using cookiecutter
-   [ ] Fill out the \`make<sub>dataset.py</sub>\` file such that it downloads whatever data you need and
-   [ ] Add a model file and a training script and get that running
-   [ ] Remember to fill out the \`requirements.txt\` file with whatever dependencies that you are using
-   [ ] Remember to comply with good coding practices (\`pep8\`) while doing the project
-   [ ] Do a bit of code typing and remember to document essential parts of your code
-   [ ] Setup version control for your data or part of your data
-   [X] Construct one or multiple docker files for your code
-   [X] Build the docker files locally and make sure they work as intended
-   [ ] Write one or multiple configurations files for your experiments
-   [ ] Used Hydra to load the configurations and manage your hyperparameters
-   [ ] When you have something that works somewhat, remember at some point to to some profiling and see if
    you can optimize your code
-   [ ] Use wandb to log training progress and other important metrics/artifacts in your code
-   [ ] Use pytorch-lightning (if applicable) to reduce the amount of boilerplate in your code


<a id="org27a5d55"></a>

## Week 2

-   [ ] Write unit tests related to the data part of your code
-   [ ] Write unit tests related to model construction
-   [ ] Calculate the coverage.
-   [ ] Get some continuous integration running on the github repository
-   [ ] (optional) Create a new project on \`gcp\` and invite all group members to it
-   [ ] Create a data storage on \`gcp\` for you data
-   [ ] Create a trigger workflow for automatically building your docker images
-   [ ] Get your model training on \`gcp\`
-   [ ] Play around with distributed data loading
-   [ ] (optional) Play around with distributed model training
-   [ ] Play around with quantization and compilation for you trained models


<a id="orga757fcf"></a>

## Week 3

-   [ ] Deployed your model locally using TorchServe
-   [ ] Checked how robust your model is towards data drifting
-   [ ] Deployed your model using \`gcp\`
-   [ ] Monitored the system of your deployed model
-   [ ] Monitored the performance of your deployed model


<a id="org487ce4a"></a>

## Additional

-   [ ] Revisit your initial project description. Did the project turn out as you wanted?
-   [ ] Make sure all group members have a understanding about all parts of the project
-   [ ] Create a presentation explaining your project
-   [ ] Uploaded all your code to github
-   [ ] (extra) Implemented pre\*commit hooks for your project repository
-   [ ] (extra) Used Optuna to run hyperparameter optimization on your model


<a id="orgae04bd7"></a>

# Project package list

Heres a small list of packages that could be usefull during this project,

-   pre-commit, to automatically run black, mypy, nbdev etc.. on commits
-   conda environment
-   nbdev, to avoid notebook merge conflicts
-   dvc, vc for large files
-   flake8, check code according to pep8
-   black, fix code formatting according to pep
-   isort, sort imports
-   mypy, static type checker
-   pipreqs, generate python requirements

