# driveCNN
### Introduction
Car behavioral cloning based on Nvidia's end-to-end deep learning approach <sup>[\[1\]](#fn1)</sup>. Nvidia proposes a deep architecture that works well for real cars in real world scenarios given that they have enough computing power. Later studies suggest shallower architectures suitable for deployment on slower hardware <sup>[\[2\]](#fn2)</sup> or incorporating a second LSTM network to capture temporal dynamic behavior as well <sup>[\[3\]](#fn3)</sup>. Reinforcement Learning <sup>[\[4\]](#fn4)</sup> is another alternative approach, but it is beyond the scope of this repo.

To test these models, we can use one of the various simulated environments out there, like Udacity's self driving car simulator <sup>[\[5\]](#fn5)</sup>, CARLA <sup>[\[6\]](#fn6)</sup> and AirSim <sup>[\[7\]](#fn7)</sup>. However, we are using an MIT RACECAR <sup>[\[8\]](#fn8)</sup> based platform running Jetson TX2. This repo is inspired by some other works <sup>[\[9\]](#fn9)</sup>.

### Dataset preprocessing
TODO

### Network Architecture
TODO

### Footnotes
<a name="fn1">[1]</a>: End-to-End Deep Learning for Self-Driving Cars | [Blog post](https://devblogs.nvidia.com/deep-learning-self-driving-cars/), [Paper](https://arxiv.org/abs/1604.07316)

<a name="fn2">[2]</a>: [An End-to-End Deep Neural Network for Autonomous Driving Designed for Embedded Automotive Platforms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6539483/)

<a name="fn3">[3]</a>: [Autonomous Vehicle Control: End-to-end Learning in Simulated Urban Environments](https://arxiv.org/abs/1905.06712)

<a name="fn4">[4]</a>: [Distributed Deep Reinforcement Learning for Autonomous Driving](https://github.com/microsoft/AutonomousDrivingCookbook/tree/master/DistributedRL)

<a name="fn5">[5]</a>: [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim)

<a name="fn6">[6]</a>: CARLA: An Open Urban Driving Simulator | [Github repo](https://github.com/carla-simulator/carla), [Paper](https://arxiv.org/abs/1711.03938/)

<a name="fn7">[7]</a>: AirSim | [Github Repo](https://github.com/Microsoft/AirSim), [Autonomous Driving using End-to-End Deep Learning: an AirSim tutorial](https://github.com/microsoft/AutonomousDrivingCookbook/tree/master/AirSimE2EDeepLearning)

<a name="fn8">[8]</a>: [MIT RACECAR](https://mit-racecar.github.io/)

<a name="fn9">[9]</a>: [OpenZeka MARC](https://github.com/openzeka/marc), [naokishibuya](https://github.com/naokishibuya/car-behavioral-cloning/), [hminle](https://github.com/hminle/car-behavioral-cloning-with-pytorch/)
