# DataScienceBowl17

There were originally around 1400 dicom image slices of various patients lung scan.


For validating purpose only 110 samples were processed.


Preprocessing is done according to https://www.kaggle.com/sentdex/first-pass-through-data-w-3d-convnet by sentdex.

Simple 1 layer net, 3 layer fully connected net with dropout and thus finally proposed architecture with cnn is tested.They gave around 71% and  85% accuracy respectively

The cnn architecture is as follows: convLayer-AvgPooling-convLayer-AvgPooling-fc layer

python notebook contains all code.
