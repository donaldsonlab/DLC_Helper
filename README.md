# DLC_Helper
Designed to making setting up a markerless pose estimation of user-defined features with deep learning for all animals, including humans

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
Run in a windows 10 environment using Anaconda 4.7.5 and python 3.7.3

- DeepLabCut
  - [Repo found here](https://github.com/AlexEMG/DeepLabCut)

- Python 3
  - [Download](https://www.python.org/downloads/)

- Anaconda
  - [Download](https://www.anaconda.com/distribution/)

### Installing

#### Setting up the Anaconda environment-

1. [Follow these instructions](https://github.com/AlexEMG/DeepLabCut/blob/master/docs/installation.md)

## Running the Script
**Important**: At anytime the script can be paused by clicking into the window, hit enter to resume

1. Open anaconda prompt

2. Type ```activate name_of_environment```

3. Change direcotries using ``cd Downloads\``` 

4. Run the script by typing ```python DLC_Helper.py```

5. In the script:
    * Enter the project title ```ex. TestProject```
    * Enter the experimenter's name ```ex. Chase or Chase Dudas```
    * *wait*
    * Type in the name of the video ```ex. Vole 1159 side video 1```
    * Eneter the full path leading to the selected video ```ex. C:\Users\Behavior Scoring\Downloads\Vole 1159 side video 1.mpg```
    * Enter the working directory ```ex. C:\Users\Behavior Scoring\Desktop\DeepLabCutProjects```
    * Done! Now sit back and let the magic happen

## Deployment

Additional notes about how to deploy this on a live system
```
Python 3.7.3
conda 4.7.5
```

## Built With

* [Anaconda](https://www.anaconda.com/) - Platform
* [Visual Studio](https://visualstudio.microsoft.com/) - IDE
* [Python](https://www.python.org/) - Code Language 
* [deeplabcut](https://github.com/AlexEMG/DeepLabCut) - Pose Estimator w/ Machine Learning


## Versioning

We use species for versioning. For the versions available, see the [tags on this repository](https://github.com/donaldsonlab/UI-lab-capture/tags). 

## Authors

* Chase Dudas - *Script* - [Personal GitHub](https://github.com/ChaseD13)
* **alex** - *Script* - [Git](https://github.com/AlexEMG)

## License

This project is not licensed

## Acknowledgments

