# Level Difficulty in Candy Crush Saga
## Description
[Candy Crush Saga](https://www.king.com/game/candycrush) is a hit mobile game developed by King (part of Activision|Blizzard) that is played by millions of people all around the world.

In this Project, we will get to work with a real Candy Crush dataset and use this data to estimate level difficulty. This project involves manipulating data frames using `dplyr` and make plots using `ggplot2`.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analysis.
## Contents
1. **Candy Crush Saga:** Load in the packages we're going to need for the project.
2. **The data set:** Load in the dataset and display the first couple of rows. 
3. **Checking the data set:** Count how many players are in the dataset and how many days it spans.
4. **Computing level difficulty:** Calculate the probability of winning a level in a single attempt for each level.
5. **Plotting difficulty profile:** Plot a line graph with the difficulty for each level.
6. **Spotting hard levels:** Add points to the plot and a horizontal dashed line at the 10% value.
7. **Computing uncertainty:** Compute the standard error of the difficulty for each level using the given formula.
8. **Showing uncertainty:** Add error bars to the difficulty profile plot.
9. **A final metric:** Calculate how likely is it that a player will complete all the levels in the first attempt.
10. **Should our level designer worry?:** Should our level designer worry that a lot of players will complete the episode in one attempt?