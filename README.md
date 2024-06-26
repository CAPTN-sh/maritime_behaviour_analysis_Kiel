# Enhancing Maritime Behaviour Analysis through Novel Feature Engineering and Digital Shadow Modelling: A Case Study in Kiel Fjord



## Introduction
This repository contains an implementation of an extension and utilisation of
the Surface Vessel Nautical Behaviour Analysis (SV-NBA) framework for
in-depth spatio-temporal analysis of maritime surface vessels’ behaviour
in Kiel Fjord. 

![Behaviour Definition](images_and_description/behaviour_definition_w.png)

## Requirements
To install all the requirements, one needs to first install:

+ conda
+ poetry

A detailed list of the required libraries can be found in:

+ poetry.toml

The proper installation must then be done with poetry and conda.

## Datasets
The collected data comprises of AIS signals received in a monitoring period from 24.03.22 to 30.06.2023. Of those days there were 296 for which all outgoing AIS messages in the Kiel Fjord region were recorded.

**The data used in the experiment has a time resolution of 10 seconds, while the data in the `data/assets` are sample data obtained through downsampling, with a resolution of 10 minute.**

## Contributing
![DAE Framework](images_and_description/DAE_framework_new.png)

This framework illustrates a transformer-based autoencoder that takes input data X, transforms it into an intermediate representation Y through an encoder, and then reconstructs it into output Z using a decoder. During this process, a loss function Loss(X, Z) is used to optimize the model for accurate reconstruction of the input data. Finally, the intermediate representation Y is utilized for behavior analysis, categorizing data points into different behavior types.

## Authors and acknowledgment
[gaf, sga, lha]@informatik.uni-kiel.de

## License
We use the MIT license, see

+ LICENSE


## Citation
