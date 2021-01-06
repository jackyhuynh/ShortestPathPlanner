# Route_Planner
 Implematation of the A* Search Algorithm to solve Mapping problem.


## Introduction
Implematation of the A* Search Algorithm to solve Search problem. One particular search problem is especially relevant to self driving cars: finding the best route from point A to point B. The application will implement a Google-maps style route planner. The full lesson and step by step explaination can be learn at [Udacity.com](https://classroom.udacity.com/nanodegrees/nd113/dashboard/overview).

### The A* Search
A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its O(bᵈ) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases. (retrived from Wikipedia.com)

Image retrived from Udacity.com

![alt](https://github.com/jackyhuynh/Route-Planner/blob/main/src/picture/map.PNG)

## Technology
- Python 
- Object Oriented Design
- Jupyter Notebook
- Data Visualization
- Machine Learning
- AI
- Localization
- Data Structures

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them
- Jupyter Notebook: If you want just test the code, simply go to google and search for jupiter notebook or another Python online IDE. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. 
- Anacoda Navigator: Install Anaconda Navigator if you want to develop data sciences using python or R. Anaconda Navigator is a desktop graphical user interface included in Anaconda that allows you to launch applications and easily manage conda packages, environments and channels without the need to use command line commands. 

### Installing

A step by step series of examples that tell you how to get a development enviroment running

* [Install Anacoda Navigator](https://docs.anaconda.com/anaconda/navigator/install/#:~:text=Installing%20Navigator%20Navigator%20is%20automatically%20installed%20when%20you,install%20anaconda-navigator.%20To%20start%20Navigator,%20see%20Getting%20Started.) - If you haven't downloaded and installed Anacoda Navigator yet, here's how to get started.
* [Jupyter Notebook](https://jupyter.org/try) - Click here to go to the online free Jupiter Notebook.


## Running the tests

Explain how to run the automated tests for this system:
- There is no download IDE need, all you need is download all the src to your machine and run it.
- Using Jupiter Notebook
- Navigate to the file Kahman_Filter_Implementation.ipynb
- hit:

```
Ctrl + Enter
```
- If this happen (most likely it is going to happen). I sucessful run this code in a virtual machine. However, when I download it to my computer and deploy it to GitHub, I experienced this issues.
```
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-8-10b645f07abd> in <module>
      1 # Run this cell first!
      2 
----> 3 from helpers import Map, load_map_10, load_map_40, show_map
      4 import math
      5 

~\python-workspace\Route_Planner\helpers.py in <module>
      2 import networkx as nx
      3 import pickle
----> 4 import plotly.plotly as py
      5 import random
      6 from plotly.graph_objs import *

ModuleNotFoundError: No module named 'plotly'
```
- Fixxed: If you are using Anaconda, open Anaconda Navigator and launch cmd prompt (cmd.exe) from there. Then run 'pip install plotly'.
```
pip install plotly
```
- If this not fix your issues, please do a search. Here is some good information: [GitHub](https://github.com/plotly/plotly.py/issues/1660) or [plotly](https://plotly.com/python/troubleshooting/)

- The notebook will execute in Markdown form and include the visualization of the map.

![alt](https://github.com/jackyhuynh/Route-Planner/blob/main/src/picture/map.PNG)

- The program was working perfectly fine when I code it in the Udacity.com workspace. You may try it [here](https://classroom.udacity.com/nanodegrees/nd113/parts/ff875ac7-e7c7-40ec-8a79-8fce37d93bb2/modules/e3ba7f5e-56e5-4a40-9b21-0f7a130d3074/lessons/b1e11f40-418c-4292-af6f-56ac2603e868/concepts/498d1011-019d-4768-bd46-f476b68c2c4b) if you are member of Udacity. 

## Deployment

Route PLanner class can be deploy and ready to work with any sensor, or moving robotic prediction. Idea for localization and/or GPS application. This is actually what we use for driving direction everyday. According to Sebastian, this technology have been around for 15 years, and still helping human each day.
Please refer to my notebook for a better understanding of implementation.

## Built With

* [Jupyter Notebook](https://jupyter.org/try) 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Udacity.com for design an outstanding program for Students.

