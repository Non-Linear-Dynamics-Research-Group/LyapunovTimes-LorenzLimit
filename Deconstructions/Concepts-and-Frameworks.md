# Concepts & Frameworks

###### tags: `Lyapunov`

## Content
[TOC]

&nbsp; 

## Reservoir Computing

:::info
The following papers would be great to look at - but we don't have access:
- [Physics-informed machine learning: case studies for weather and climate modelling](https://royalsocietypublishing.org/doi/epdf/10.1098/rsta.2020.0093)
- [Time-series forecasting with deep learning: a survey](https://royalsocietypublishing.org/doi/epdf/10.1098/rsta.2020.0209)
- [Learning earth system models from observations: machine learning or data assimilation?](https://royalsocietypublishing.org/doi/epdf/10.1098/rsta.2020.0089)
:::

## About Reservoir Computing
`much of the information represented by neural networks is not static but dynamic. As a biological example, a songbird’s representation of song is inherently time-varying and can be continuously sped up and slowed down through external perturbations.12 In artificial networks, recurrent neural networks (RNNs) can store a history of temporal information such as language, dynamical trajectories, and climate to more accurately classify and predict future events.`
Resource: https://aip.scitation.org/doi/10.1063/5.0075572

### Glossary
| Abbreviation | Long Text | Resource |
| -------- | -------- | ------|
| BPTT    | backpropagation through time     | [Resource](https://www.sciencedirect.com/science/article/pii/S0959438818302009?via%3Dihub)|
| RNN    | recurrent neural networks    | |
| LSTM |long short-term memory|[Resource](https://doi.org/10.1162/neco.1997.9.8.1735)|


### Github Resources
- [Reservoirpy](https://github.com/reservoirpy/reservoirpy) and its [tutorials](https://github.com/reservoirpy/reservoirpy/tree/master/tutorials)
- [ChyPP Combined Hybrid-Parallel Prediction](https://github.com/awikner/CHyPP)
- [Echo State Network, ANN, LSTM, Lorenz96](https://github.com/ashesh6810/RCESN_spatio_temporal) plus [Research Paper](https://npg.copernicus.org/articles/27/373/2020/npg-27-373-2020.pdf)
- [Reservoir_with_a_Parameter_Channel](https://github.com/lw-kong/Reservoir_with_a_Parameter_Channel_PRR2021) and the updated version [here](https://github.com/lw-kong/Reservoir_with_a_Parameter_Channel_JPC2021)
- [Keras is a deep learning API written in Python](https://github.com/keras-team/keras)
- [RNN architectures trained with Backpropagation through time (BPTT) and Reservoir Computing (RC) for high-dimensional time-series forecasting](https://github.com/pvlachas/RNN-RC-Chaos)
- [Fog Prediction](https://github.com/conrad-blucher-institute/FogNet)
- [Hamiltonian Neural Networks](https://github.com/ayushgarg31/HNN-Neurips20190)

### Tutorials
- [Data Driven Modeling of Complex Systems: A Reservoir Computing Tutorial](https://towardsdatascience.com/data-driven-modeling-of-complex-systems-8a96dc92abf9)
- [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/)
- [ modeling of extreme events in complex dynamical systems](https://arxiv.org/pdf/1803.03365.pdf) and [Github Portfolio](https://github.com/zhong1wan/data-assisted)

### Research Papers Resources
- **The Project Share at Google Drive named** [Reservoir Computing and Lyapunov Papers](https://drive.google.com/drive/folders/1k8CK4sZdLH_wBURhgpL9KALrrVdhGjbQ?usp=sharing) contains the following:
  * [Referenced papers](https://drive.google.com/drive/folders/1TiNeHFyYzE4GM_c3pWGFj6iFEGDmh_1F?usp=sharing) of the [Quanta Magazine Article](https://www.quantamagazine.org/machine-learnings-amazing-ability-to-predict-chaos-20180418/) of which the project got inspired  by  
  * [Reservoir Computing books](https://drive.google.com/drive/folders/1KjsVNSTHzqYjPzX4l_9fDCL8IwwKsoJj?usp=sharing)
  * [Papers](https://drive.google.com/drive/folders/1sTSDBxfW_rJ-CRqvDRx-ehzndIQ6ORbK?usp=sharing) which cited the original *12X-Lyapunov Times* paper (short: [orginal paper](https://drive.google.com/open?id=1AkVMKwpyp6LLu3-jyaQMLp8KPVgKuEgb&authuser=matthias.frenzl%40gmail.com&usp=drive_fs)) until April 2022. 
Some papers have added their github repositories containing their code and documentation and shared the used data at Zenodo. One can find the links in the particular paper and partly already downloaded and stored in a directory within this share, for instance:   
    * [Stochastic ensemble climate forecast with an analogue model](https://drive.google.com/drive/folders/16vZgIEJMNFCo-7YqbwcsJLOJWpbqQaMk?usp=sharing)
    * [Machine Learning Emulation of Urban Land Surface Processes](https://drive.google.com/drive/folders/17-ZVWbmnbI99x7HqhLv3-q-La6O7uQA7?usp=sharing)
    * [Data-driven predictions of a multiscale Lorenz 96 chaotic system
using machine-learning methods: reservoir computing, artificial
neural network, and long short-term memory network](https://drive.google.com/drive/folders/176W3693wfgYKQqTRpxPB37W5aaHoPF3r?usp=sharing)
    * [Applying Machine Learning to Improve Simulations of a
Chaotic Dynamical System Using Empirical Error
Correction](https://drive.google.com/drive/folders/16YYqqmd_R7qVpN9ZROX3NqQ1KTl7mfR2?usp=sharing)
 * **Original Paper** [Hybrid forecasting of chaotic processes Using machine learning in conjunction with a knowledge-based model](https://drive.google.com/open?id=1AkVMKwpyp6LLu3-jyaQMLp8KPVgKuEgb&authuser=matthias.frenzl%40gmail.com&usp=drive_fs)
![](https://hackmd.io/_uploads/HJQN4ZHUq.png)

  * **A start to get into the topic** [1 Start here -  When machine learning meets complex systems - Networks, chaos, and nonlinear dynamics](https://drive.google.com/file/d/19GQTl6J7zLEYXzGBaBWzmbKZXHOhFDzp/view?usp=sharing)


![](https://hackmd.io/_uploads/B1HBH-S89.png)


* Maybe also very useful could be the following (kind of) [reference implementation of Reservoir comuputing](https://drive.google.com/drive/folders/16w-Ft6alYtYL0GJw59R6NJQfCnXngfCt?usp=sharing)

## Echo State Approach
- [ ]  Open for deconstruction: [The “echo state” approach to analysing and training recurrent neural networks](https://drive.google.com/file/d/1-2zf47O9JLtJ8zEUUQK-IQ2eXgbS-ZZ4/view?usp=sharing)
## Bayesian optimization

## Recurrent Neural Network [RNN]
