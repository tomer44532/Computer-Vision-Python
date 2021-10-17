# Computer Vision - Cars Heat Map
Development enviroment - Anaconda

Programing language - Python




Algorithm:

Croping the video to get rid of the black frame.
In the first frame finding the points that stand out and saving them - using cv2.goodFeaturesToTrack.
On each frame get the current frame and the prev one and compare the points that where found. by using cv2.calcOpticalFlowPyrLK we draw a line of the movings points. Then saving in into new video, which have only the heatmap.
On each frame of the croped video finding the contoures of the cars, using costum size values to find only the cars. Then all the contoured frames into new video.
Combine the contour video and the heatmap video with the croped video.

