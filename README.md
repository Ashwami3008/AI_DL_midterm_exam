# AI_DL_midterm_exam


Midterm exam is going to be based on building a real-time Mask R-CNN using Detectron. You can use either computer-installed webcam or a consumer graded one for capturing the vide stream.
The task is to implement a simple solution to run Detectron Mask R-CNN algorithm for object detection and instance segmentation with webcam. 


****Runtime Requirements are as follows****:
•	Installing Detectron
•	CUDA 8 and above
•	cuDNN 6 and above
•	OpenCV 3.4
Datasets which can be used:
COCO
COCO minival
PASCAL VOC 2007
Kavsir


****Basic step overview :****
To set and get Camera use OpenCV using the VideoCapture(). Now fetch the images form Camera and have them in the RGB format for visualization. The default format will be in PDF, convert all of them to JPG. After this use matplotlib for visualization purpose (do some research on how matplotlib supports webcam). 
Note: Use mid shoulder/ mid hip first for better visualization. 
Now draw/blend the keypoints and then show them. Visualize the matplotlib figure. Post that Convert a matplotlib figure to a NumPy array with RGBA channels and return it. 
Note: Be sure to draw the canvas before starting. 



****Submission:****
Every student is required to create a GitHub repository and only post the GitHub link on Canvas. The student is allowed to add all the resources to the created repository. One work document documenting the steps and either screenshots or video of the working project is a must. Kindly ****DO NOT**** make any file submissions on Canvas. The submission is supposed to be made under the “Assignment/Mid-Term Exam” section.
