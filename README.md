#EMTF BDT Performance Plotter
This repository contains tools to evaluate the performance of the EMTF BDT after retraining.

## Setup

```
git clone git@github.com:jrotter2/EMTF_BDT_PerformancePlotter.git

pip3 install -r requirements.txt
```
## Structure

The repository is structure so that one could run each individual plotter seperataly or call the general plotter to make multiple different types of performance plots.

Additionally there are helper classes in the `Helpers` directory which can be used to store multiuse functions or useful calculations.

### General Plotter
`plotter.py` is responsible for making general plots.

### Efficiency Plotter
`efficiencyPlotter.py` is responsible for making efficiency plots.

### Occupancy Plotter
`occupancyPlotter.py` is responsible for making occupancy plots.

### Resolution Plotter
`resolutionPlotter.py` is responsible for making resolution plots.

### Helpers
Stored in the `Helpers` directory, are used to store multiuse functions or useful calculations.


