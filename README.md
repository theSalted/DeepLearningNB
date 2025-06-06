# Deep Learning Notebooks
## Deep Learning with Python  
This repository follows _Deep Learning with Python, Second Edition_ and _Deep Learning with Python, Third Edition_.

## Getting Started

When I first created this repo, I managed dependencies the old-fashioned way using `%pip`. After taking a 10-month break from the project, I recently returned to continue development—only to find that my environment had completely changed and nothing worked anymore.  

I spent far too long juggling between `pip`, `venv`, `poetry`, and `conda`. Enough is enough. After some research, I found one tool that satisfied all my requirements: [Pixi](https://pixi.sh/latest/).

To get started, follow the [Pixi installation guide](https://pixi.sh/latest/).  
Each folder in this repo is its own Pixi workspace, so you need to `cd` into the folder you want to work in before running commands.

To install dependencies, run:
```bash
pixi install
```

Make sure you set the correct interpreter for your project. For VSCode, [follow this guide](https://pixi.sh/latest/).

## The Table of Contents
1. MNIST
2. KerasTensorFlow
3. Generalization
4. KerasDeepDive
5. ComputerVision
6. ConvnetPatterns
7. ImageSegmentation
