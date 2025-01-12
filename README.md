# Hands-On-Neural-Networks

A collections of resources to understand Neural Network.

Presentation: https://drive.google.com/drive/folders/1qvF70ZiciQM4BbDqOWqmSE7E5H2uv2fX?usp=sharing

## Getting Started

### Slides

https://drive.google.com/drive/u/1/folders/1d2KK9VzWeueTnDu3x6mddWFZFF8JQrvG

### Prerequisites

Install conda https://docs.anaconda.com/anaconda/install/ for python 3.6.

Make sure you have added theforge channel: 

```
conda config --append channels conda-forge
```

Then in the projec directory run:

```
conda env create --name dl_env python=3.6 --file dl_env.yml
```

This will create our conda enviroment.

If conda does not find all the packages please add :

```
conda config --env --add channels conda-forge
```

### Run
To activate the enviroment you can run in a shell

```
conda activate dl_env
```

To run tensorboard simply type:

```
tensorboard --logdir logs
```

## Contributing

Feel free to contribute with a pull request.

### Meetups

https://www.meetup.com/LondonArtificialIntelligence/
https://www.meetup.com/London-Reinforcement-Learning/
