# The Conurbation Algorithm
This project is aimed at developing a fully functional featured city without disrupting the ecological density of the city.It is a further modification of the initial [city generation model](https://github.com/josauder/procedural_city_generation).

## [![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/kritika-srivastava/Random-Password-Generator/blob/master/LICENSE)![Project Status](https://img.shields.io/badge/ProjectStatus-Completed-orange)[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
## ![Python Badge](https://img.shields.io/badge/Python-3.5%7C3.6%7C3.7-success)![Dependency](https://img.shields.io/badge/Dependencies-NumPy%20%7C%20PyQt5%20%7C%20Blender%20%7C%20Scipy%20%7C%20Matplotlib-ff69b4)

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/Bl%204.PNG" width="1200" height = 700>

### Challenges :
- Migrating the the code from PyQt4 to PyQt5 and updating the code with the new dependencies.
- Automating the Blender Scripts to run directly from the PyQt5 GUI.
- Cleaning the code to remove all the version conflicts.
- Generating the new map to run the test scripts.
- Updating and modifying the codes for growth rules.

### Input -
The input to the conurbation algorithm is the map generated from the project [Land Stratification](https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/README.md).        

<img src="https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/Binary_mosaic.png" width="300">

The growth rule image defines the formation of road network of the town. Blue color implies a radial growth rule, red colour indicates grid growth rule and green colour depicts organic(random) growth rule.

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/11.png" width="300">

### Dependencies -
- Python 3.x
- Numpy
- matplotlib
- Blender
- PyQt5
- Scipy

### Workflow -

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/workflow.PNG">

### Steps to replicate the Program
- Clone this repository
- Change all the paths in the files [GUI.py](https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/src/GUI.py) and [blenderize.py](https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/src/procedural_city_generation/visualization/blenderize.py).
- Remove all the __pycache__ files from the cloned folder if present.
- Check all the installed dependencies.
- Install and add blender to the environment path.
- Run the script [GUI.py](https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/src/GUI.py).


#### *If everything worked so far, the PyQt5 window should openup and the algorithm should generate the city with the clicks.Make sure to run all the tabs in order,i.e., Roadmap Generation-> Polygon Extraction -> Building Generation ->Visualise in Blender.*

Feel free to experiment with [growth rule images](https://github.com/kritika-srivastava/The-Conurbation-Algorithm/tree/master/src/procedural_city_generation/inputs/rule_pictures) and [Density images](https://github.com/kritika-srivastava/The-Conurbation-Algorithm/tree/master/src/procedural_city_generation/inputs/density_pictures) and open a pull request for further modification of the project.
## Sample Outputs-
### 1. Roadmap Generation

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/1.PNG" width="500">

### 2. Polygon Extraction

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/2.PNG" width="500">

### 3. Building Generation

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/3.PNG" width="500">

### 4. 3D Visualisation of Buildings in Blender

<img src="https://github.com/kritika-srivastava/The-Conurbation-Algorithm/blob/master/img/Bl%204.PNG" width="900" height= "500">

### References -
- [Blender](https://docs.blender.org/api/current/index.html)
- [PyQt5](https://doc.bccnsoft.com/docs/PyQt5/)
- [City generation Algorithm](https://github.com/josauder/procedural_city_generation)
