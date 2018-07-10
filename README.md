# genre_classification1

Description

Train and evaluate Support Vector Machine (SVM) for prediction of genre. Use Essentia's MusicExtractor to compute summarized descriptor values (no frames). Use Scikit-learn for SVM classifier. It will be useful to pre-process all features first, standardizing them to zero mean and unit variance.

Write a report in form of a python notebook. This script should:

Analyze all audio in the dataset using MusicExtractor and store aggredated analysis results in json files
Load descriptors computed for all files, and load genre annotations (all audio files are inside folder names that correspond to genres)
You can first convert json to CSV if you like
Use lowlevel.*, rhythm.*, and tonal.* descriptors
For summarized descriptors only consider *.mean and *.stdev
Ignore non-numerical descriptors
Standardize all features
Split dataset into two balanced subsets: 80% for training, 20% for testing (make sure that the testing subset contains equal amount of tracks by each genre)
Train model on training subset
Predict genre for testing subset and evaluate accuracy of predictions (% of correct predictions). Compute classification accuracy and the confusion matrix.
Report and discuss evaluation results.

Deliverable

A python notebook with code and report. Include text explaining all your steps, decisions, and discussion of results (submissions with code only and no explanation are not enough!)

Download links

Dataset: https://www.dropbox.com/s/gljckh3nff55r9c/Essentia_genre_task.zip?dl=0

Alternative link for download: http://essentia.upf.edu/documentation/tmp/Essentia_genre_task.zip

MIR Course Docker image including Essentia python wrapper: https://github.com/MTG/MIRCourse

