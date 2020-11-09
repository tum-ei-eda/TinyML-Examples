# TinyML-Examples

In this repository you will find a list of submodules that correspond to the following Tiny(M)achine(L)earning examples. 

## Examples' status

<!--
    Shields:
    Online - https://img.shields.io/badge/status-online-brightgreen
    Offline - https://img.shields.io/badge/status-offline-yellow
    WIP - https://img.shields.io/badge/status-WIP-orange
    Not started - https://img.shields.io/badge/status-TODO-red
-->

| Example        | Status           | Contact |
| ------------- |:-------------:| :-------------:|
| Sine (Hello World) | ![hai](https://img.shields.io/badge/status-online-brightgreen)&![hai](https://img.shields.io/badge/status-offline-yellow)| Alex|
| MNIST |  ![hai](https://img.shields.io/badge/status-online-brightgreen)&![hai](https://img.shields.io/badge/status-offline-yellow) | Alex/Philip |
| MicroSpeech |  ![hai](https://img.shields.io/badge/status-online-brightgreen)&![hai](https://img.shields.io/badge/status-offline-yellow) | Alex/Philipp |
| CIFAR10 | ![hai](https://img.shields.io/badge/status-TODO-red) | - |
| CNN | ![hai](https://img.shields.io/badge/status-WIP-orange) | Yu-Kai |
| Graph | ![hai](https://img.shields.io/badge/status-TODO-red) | - |
| Face Recognition | ![hai](https://img.shields.io/badge/status-WIP-orange) | Alex/Teo |
| KWS | ![hai](https://img.shields.io/badge/status-TODO-red) | - |

## Documentation/Notes

### Sine/Hello World

The colab notebook to generate the model is directly taken from the book [*TinyML*](https://www.amazon.de/-/en/TinyML-Learning-TensorFlow-Ultra-Low-Micro-Controllers/dp/1492052043/ref=sr_1_1?dchild=1&keywords=tinyml&qid=1588597546&sr=8-1) and the working implementation is for a STM3240G-EVAL development board.

Working implementation can be found [here](https://github.com/alxhoff/STM3240G-EVAL-TensorFlow-Hello-World).

Offline interpreter example can be found on the [`compiler`](https://github.com/alxhoff/STM3240G-EVAL-TensorFlow-Hello-World/tree/compiler) branch of the implementation repository.

### MNIST

The MNIST example is currently bottlenecked by a large RAM requirement, probably im2col.

Practical implementation is being constructed [here](https://github.com/alxhoff/STM3240G-EVAL-TensorFlow-MNIST).

### MicroSpeech

Wake word example from TinyML book. FP of Philipp van Kempen.

Practical implementation for STM32F769 board.

### CIFAR10

### CNN

### Graph

### Face Recognition

Bachelor thesis topic of Teo Fratiloiu.

Building a data set was part of Teo's IP and led to the development of the [**webscrapper**](https://github.com/munober/webscrapper) which aims to automate the scrapping, validation and preprocessing of image datasets.

Practical implementation is being constructed [here](https://github.com/alxhoff/STM3240G-EVAL-TensorFlow-TinyFace).

### KWS
