# Thruster Design Tool
[![GitHub version](https://badge.fury.io/gh/runphilrun%2FThrusterDesign.svg)](https://badge.fury.io/gh/runphilrun%2FThrusterDesign)
[![GitHub issues](https://img.shields.io/github/issues/runphilrun/ThrusterDesign.svg)](https://github.com/runphilrun/ThrusterDesign/issues)
[![GitHub forks](https://img.shields.io/github/forks/runphilrun/ThrusterDesign.svg)](https://github.com/runphilrun/ThrusterDesign/network)
[![GitHub stars](https://img.shields.io/github/stars/runphilrun/ThrusterDesign.svg)](https://github.com/runphilrun/ThrusterDesign/stargazers)
[![License](https://img.shields.io/github/license/runphilrun/ThrusterDesign.svg?style=flat-square)](https://github.com/runphilrun/ThrusterDesign/blob/master/LICENSE.md)

Tool to aid in design of small monopropellant thrusters.

> *[View this project on STEMN](http://stemn.com/projects/thruster-design-tool)*

```bash
$ python setup.py build
$ python setup.py install
$ thruster-designer --help
```

## Abstract
The thruster's nozzle, propellant, and chamber conditions each have a huge impact on performance. The fluid mechanics that model engine effectiveness are pretty complicated, unfortunately. The purpose of this script is to make it easy to see how tweaks in nozzle geometry, propellants, and chamber conditions affect performance in order to find the optimal design solution.

## Features
* Simulate the performance of a thruster in space for a given set of parameters and output performance metrics.
* Output simulation data in a useful manner.
* Allow the user to easily tweak parameters.

## Usage
Run `ThrusterDesign.py` and input parameters when prompted.

## About & Documentation
Please refer to the [Project Wiki](https://github.com/runphilrun/ThrusterDesign/wiki) for details on the code structure, more information about the project, and general theory.

> *If you encounter any bugs, please report them in the [Issue Tracker](https://github.com/runphilrun/ThrusterDesign/issues)!*

## Useful Resources
- https://github.com/pytest-dev/pytest/
- http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/quickstart.html
