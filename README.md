# RL-Laboratory
Official repository for the 2032/2024 Reinforcement Learning Laboratory at the University of Verona.

## Assignments
Following the link to the code snippets for the lessons:

**First Semester**
- [x] Lesson 1: MDP and Gym Environments [Code!](lessons/lesson_1_code.py) [Results!](results/lesson_1_results.txt) [Slides!](slides/slides_lesson_1.pdf)

## Tutorials
This repo includes a set of introductory tutorials to help accomplish the exercises. In detail, we provide the following Jupyter notebook that contains the basic instructions for the lab:
- **Tutorial 1 - Gym Environment:** [Here!](tutorials/tutorial_environment.ipynb)

## First Set-Up (Conda)
1. Download [Miniconda](https://docs.conda.io/en/latest/miniconda.html) for your System.

2.  Install Miniconda
	- On Linux/Mac 
		- Use *./Miniconda3-latest-Linux-{version}.sh* to install.
		- *sudo apt-get install git* (may be required).
	- On Windows
		- Double click the installer to launch.
		- *NB: Ensure to install "Anaconda Prompt" and use it for the other steps.*

3.  Set-Up conda environment:
	- *git clone https://github.com/Isla-lab/RL-lab*
	- *conda env create -f RL-Lab/tools/rl-lab-environment.yml*

## First Set-Up (Python Virtual Environments)
Python virtual environments users (venv) can avoid the Miniconda installation. The following package should be installed:
  - scipy, numpy, gym
  - jupyter, matplotlib, tqdm
  - tensorflow, keras

## Contact information
*  Teaching assistant: **Luca Marzari** - luca.marzari@univr.it
*  Professor: **Alberto Castellini** - alberto.castellini@univr.it
