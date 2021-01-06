# Route_Planner

## Introduction
Implematation of the A* Search Algorithm to solve Search problem. One particular search problem is especially relevant to self driving cars: finding the best route from point A to point B. When this lesson is over you will take everything you've learned in this course and actually implement a Google-maps style route planner.

### The A* Search
A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its O(bᵈ) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases. (retrived from Wikipedia.com)


## Technology
- Python 
- Object Oriented Design
- Jupyter Notebook
- Data Visualization
- Machine Learning
- AI
- Localization
- Prediction
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
- The notebook will execute in Markdown form and include some data visualization to show the actual performance of kalmanfilter vs. lidar vs. round truth.

![alt](https://github.com/jackyhuynh/kalmanFilter-app/blob/main/src/picture/1.PNG)
## Deployment

Matrices class can be deploy and ready to work with any sensor, or moving robotic prediction. Idea for localization and/or self-driving car.
It turns out that using multiple sensors like radar and lidar at the same time, will give even better results. Using more than one type of sensor at once is called sensor fusion, which is used in Self-Driving Car applications.
Please refer to my notebook for better understanding.

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
See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

