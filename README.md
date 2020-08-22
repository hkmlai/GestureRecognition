Build a model which recognise/classify five different gestures performed by the user which will help users control the TV without using a remote.

Thumbs up:  Increase the volume, Thumbs down: Decrease the volume, Left swipe: 'Jump' backwards 10 seconds, Right swipe: 'Jump' forward 10 seconds, Stop: Pause the movie

The training data consists of 663 videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is a sequence of 30 frames(images).

The data is in a zip file. The zip file contains one 'train' folder, one 'val' folder and two CSV files(one for each folder). 
These folders are in turn divided into subfolders where each subfolder represents a video(30 frames(images)) of a particular gesture. 

Note that all images in a particular subfolder have the same dimensions but different subfolders may have different dimensions. 
Specifically, videos have two types of dimensions - either 360x360 or 120x160 (depending on the webcam used to record the videos). 

Each row of given CSV file represents one video and contains three main pieces of information - the name of the subfolder containing the 30 images of the video, the name of the gesture and the numeric label (between 0-4) of the video.
