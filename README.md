# Deep Learning Notebooks
## Deep Learning with Python  
This repository follows _Deep Learning with Python, Second Edition_ and _Deep Learning with Python, Third Edition_.

## Getting Started

### On Device, VPS, and More 
When I first created this repo, I managed dependencies the old-fashioned way using `%pip`. After taking a 10-month break from the project, I recently returned to continue development—only to find that my environment had completely changed and nothing worked anymore.  

I spent far too long juggling between `pip`, `venv`, `poetry`, and `conda`. Enough is enough. After some research, I found one tool that satisfied all my requirements: [Pixi](https://pixi.sh/latest/).

To get started, follow the [Pixi installation guide](https://pixi.sh/latest/).  
Each folder in this repo is its own Pixi workspace, so you need to `cd` into the folder you want to work in before running commands.

To install dependencies, run:
```bash
pixi install
```

Each folder in this repo contains a `pixi.toml`, this controls pixi workspace. By default, most of workspace only have platform `osx-arm64` enabled. If you are on a different platform, [see this guide to enable your platform](https://pixi.sh/latest/workspace/multi_platform_configuration/)

Make sure you set the correct interpreter for your project. For VSCode, [follow this guide](https://pixi.sh/latest/).

### Google Colab
If you want to run these notebooks on Google Colab. Simply fork this repo, go to `File` -> `Open notebook` -> `Github` and paste url to your fork and select the proper notebook. Colab come with most of dependencies installed so you shouldn't be needing to install yourself.

## The Table of Contents
1. MNIST
2. KerasTensorFlow
3. Generalization
4. KerasDeepDive
5. ComputerVision
6. ConvnetPatterns
7. ImageSegmentation
