=======================
*Data*
=======================

This folder contains data for the GermEval shared task on candy speech detection collocated with KONVENS 2025. Link: https://yuliacl.github.io/GermEval2025-Flausch-Erkennung/

	- "trial data" contains an excerpt of the training data.

	- "training data" contains 80% of the data.

	- "test data" contains 20% of the data.

The content creators and communities vary in topic, style, age group, etc. The training and test datasets do not overlap in terms of YouTube videos. Furthermore, the test dataset mostly contains (comments on) videos from content creators that are different from those in the training dataset. The communities commenting on these videos can therefore be expected to differ.

Each folder contains the following three files:

	-  "comments.csv" contains all comments (ids and text) posted by users under the YouTube videos.

	-  "task1.csv" contains the data for the subtask 1 of the shared task 

		This file contains ids of all comments in the comments.csv file. 
		For each comment, information is provided as to whether it contains candy speech or not.

	-  "task2.csv" contains the data for the subtask 2 of the shared task

		This file contains ids of only those comments from the comments.csv file that contain expressions of candy speech. 
		For each comment, the type of candy speech expression and its span (onset and offset in characters) are provided.
		
		
NOTE: The class distribution (i.e. Flausch types) for Task 2 may vary between the training and test data

=======================
*Annotation guidelines*
=======================

The German version of the annotation guidelines was used by the annotators. The English version is a translation thereof.