# NASAs-ISS-zeroG-robot

The goal of this project is to create a floating voice assistant robot for use in the International Space Station. This repo is where all of the source code will be held.

## Project's Management

Find the current status of the project [here](https://github.com/Abesuden/NASAs-ISS-zeroG-robot/projects/1)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software. Check out the [requirements.txt](https://github.com/Abesuden/NASAs-ISS-zeroG-robot/requirements.txt) for quick installation

```
Python3
Pip
Python venv
Numpy
OpenCV 3
Keras
```

### Installing

A step by step series of examples that tell you how to get the development environment running

Update your linux environment

```
sudo apt update
```

Download Python3

```
sudo apt install python3
```


Install Pip

```
sudo apt install pip
```

Install Numpy

```
pip install numpy
```


Install OpenCV 3

```
pip install opencv-contrib-python==3.4.5.20
```


Install Keras

```
pip install keras
```

## Deployment

We are deploying the software on a RaspberryPi 4 model B

## Built With

* [Open CV](https://docs.opencv.org/2.4/modules/refman.html) - Used for navigating by creating a continous depth map from the inside of the ISS
* [Keras](https://keras.io/) - Used for training the robot to have face recognition with deep learning

## Versioning

We use [Git](https://git-scm.com/doc) for versioning. For the versions available, see the [tags on this repository](https://github.com/NASAs-ISS-zeroG-robot/tags).

## Authors

* **Alex Besuden** - *Created README* - [@abesuden](https://github.com/abesuden)

See also the list of [contributors](https://github.com/abesuden/NASAs-ISS-zeroG-robot/contributors) who participated in this project.

## License

This project is licensed under the [MIT](LICENSE.md) Creative Commons License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

* [@Alex Besuden](https://github.com/abesuden) (**Software/Hardware Engineer**)
* [@Aaron Zellner](https://github.com/aaron3037) (**Software/Hardware Engineer**)
