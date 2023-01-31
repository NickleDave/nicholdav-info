---
title: "hybrid-vocal-classifier: a Python Package to Automate Labeling of Birdsong for Behavioral Experiments"
collection: talks
type: "Talk"
permalink: /talks/2017-07-14-hybrid-vocal-classifier
venue: "SciPy 2017"
date: 2017-07-14
location: "Austin, Texas"
---
Talk on YouTube: <https://youtu.be/BwNeVNou9-s>

## Abstract
Neuroscientists study songbirds to understand how the brain learns and produces motor skills. Like babies learning to talk, songbirds acquire their song socially during a critical period in development. To understand the neural basis of birdsong, neuroscientists carry out behavioral experiments. Often analysis requires labeling the elements of song (known as "syllables") by hand, which consumes many person-hours. Several methods have been proposed to automate labeling syllables, but little work has been done to compare them. Hybrid-vocal-classifier (HVC) is a Python package for comparing methods and automating labeling. It is tested on a large collection of hand-labeled song, now made publicly available. Users can configure HVC with human-readable YAML files. HVC loads data collected with different programs by making use of the SciPy/Numpy stack. It includes previously proposed algorithms, implemented in scikit-learn, as well as artificial neural network models built in Keras. Initial results obtained with HVC suggest convolutional neural networks yield higher accuracy predictions with less training data than the best models previously proposed.
