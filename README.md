
# Table of Contents

1.  [Project checklist](#org5fb0c9a)



<a id="org5fb0c9a"></a>

# Project checklist

-   [ ] Create a git repository
-   [ ] Make sure that all team members have write access to the github repository
-   [ ] Create a dedicated environment for you project to keep track of your packages (using conda)
-   [ ] Create the initial file structure using cookiecutter
-   [ ] Fill out the \`make<sub>dataset.py</sub>\` file such that it downloads whatever data you need and
-   [ ] Add a model file and a training script and get that running
-   [ ] Remember to fill out the \`requirements.txt\` file with whatever dependencies that you are using
-   [ ] Remember to comply with good coding practices (\`pep8\`) while doing the project
-   [ ] Do a bit of code typing and remember to document essential parts of your code
-   [ ] Setup version control for your data or part of your data
-   [ ] Construct one or multiple docker files for your code
-   [ ] Build the docker files locally and make sure they work as intended
-   [ ] Write one or multiple configurations files for your experiments
-   [ ] Used Hydra to load the configurations and manage your hyperparameters
-   [ ] When you have something that works somewhat, remember at some point to to some profiling and see if
    you can optimize your code
-   [ ] Use wandb to log training progress and other important metrics/artifacts in your code
-   [ ] Use pytorch-lightning (if applicable) to reduce the amount of boilerplate in your code

