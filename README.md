# driveCNN
### Introduction
Car behavioral cloning based on Nvidia's end-to-end deep learning approach <sup>[\[1\]](#fn1)</sup>.
Nvidia proposes a deep architecture that works well for real cars in real world scenarios given that they have enough computing power. Later studies suggest shallower architectures suitable for deployment on slower hardware <sup>[\[2\]](#fn2)</sup> or incorporating a second LSTM network to capture temporal dynamic behavior as well <sup>[\[3\]](#fn3)</sup>. The testing environments for these models varies from simulations like Udacity's self driving car simulator <sup>[\[4\]](#fn4)</sup> and CARLA <sup>[\[5\]](#fn5)</sup> to real world tracks with mini-cars. We are using an MIT RACECAR <sup>[\[6\]](#fn6)</sup> based platform running Jetson TX2. This repo is inspired by some other works <sup>[\[7\]](#fn7)</sup>.

### Dataset preprocessing
TODO

### Network Architecture
TODO

### Footnotes
<a name="fn1">[1]</a>: End-to-End Deep Learning for Self-Driving Cars | [Blog post](https://devblogs.nvidia.com/deep-learning-self-driving-cars/), [Paper](https://arxiv.org/abs/1604.07316)

<a name="fn2">[2]</a>: [An End-to-End Deep Neural Network for Autonomous Driving Designed for Embedded Automotive Platforms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6539483/)

<a name="fn3">[3]</a>: [Autonomous Vehicle Control: End-to-end Learning in Simulated Urban Environments](https://arxiv.org/abs/1905.06712)

<a name="fn4">[4]</a>: [Udacity Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim)

<a name="fn5">[5]</a>: CARLA: An Open Urban Driving Simulator | [Github repo](https://github.com/carla-simulator/carla), [Paper](https://arxiv.org/abs/1711.03938/)

<a name="fn6">[6]</a>: [MIT RACECAR](https://mit-racecar.github.io/)

<a name="fn7">[7]</a>: [OpenZeka MARC](https://github.com/openzeka/marc), [naokishibuya](https://github.com/naokishibuya/car-behavioral-cloning/), [hminle](https://github.com/hminle/car-behavioral-cloning-with-pytorch/)
