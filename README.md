# EDG Sound Classification Process

The following describes everything that you'll need to know to start classifying sound data using Tensorflow with no prior coding experience necessary. Please email kafkaloff@berkeley.edu if you have any questions.

## Getting Started

These instructions will help you download all necessary software and files to start running the python template on your local machine for development.

### Installations

Necessary files and software that you need to install/download and how to install/download them.

#### Command Line Installations

Run the following commands in your terminal:

```
pip install tensorflow
pip install librosa
```

#### Downloads

* [Download Python 3](https://www.python.org/downloads/)
* Download sound_classification_template.py
* [Download sample sound sets](https://drive.google.com/drive/folders/14DmBB15mLApoZCy9pjt0y1hjFr-XVZ-H?usp=sharing)

### Running Python Files

To run a python file (*.py), enter the following in your terminal from the same directory as the python file:

```
python3 <file name>.py
```

## Training with Sample Sound Data

To get started, you need to have the sound_classification_template.py and sample sound sets (under Downloads) in the same directory. From there, you can run the following (processing the sound data will take around 5-10 min):

```
python3 sound_classification_template.py
```

Expect to see a graph and data similar to the following:

```
Class 0: 
	 accuracy: 1.000000 
	 most confused with: None
Class 1: 
	 accuracy: 0.000000 
	 most confused with: 0
Class 2: 
	 accuracy: 0.500000 
	 most confused with: 0
```

Currently, the accuracy per class and the class that it confused its test data with the most are displayed by visualize_results. Please email kafkaloff@berkeley.edu to request further features. 

To play around with more data, you can download the [Urban Sound Data set](https://urbansounddataset.weebly.com/). 

## Training Your Neural Network

### Template Configuration

### Formatting/Preparing Your Sound Data

## Understanding the ML Sound Classification Process

This is a step-by-step walk-through of the code to help any user develop an understanding of what the code is doing.

## Acknowledgments

* [Aaqib Saeed](http://aqibsaeed.github.io/2016-09-03-urban-sound-classification-part-1/)
* [Urban Sound](https://urbansounddataset.weebly.com/)
