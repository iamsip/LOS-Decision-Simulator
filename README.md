# LOS Probability Decision Function

This repository contains a MATLAB function `losProbability` that simulates the Line-of-Sight (LOS) decision based on a given probability.

## Function Description
The `losProbability` function simulates the presence or absence of LOS based on a given probability. The function outputs a binary decision (1 for LOS, 0 for Non-LOS) using Monte Carlo sampling to represent the LOS probability distribution.

## Usage
```matlab
result = losProbability(0.7);

In the above example, the function will determine the LOS decision based on a 70% probability of LOS presence.
