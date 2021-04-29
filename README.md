# Computer-Vision-Facial-attribute-classification
This is an end to end computer vision project which solves 5 multi-class classification tasks. Each task represents a specific facial attribute. Each attribute has either 2 or more than 2 classes (Maximum 9). Project includes Data Annotation (annotation tool is provided), Preparation, Preprocessing, Training, Testing and Evaluation stages.

'Images', 'video.mp4' and 'video.mov' link: https://drive.google.com/drive/folders/1x8ELbevBXA7x-W83GjyXWA0_k7WVE-xs?usp=sharing


Project outline (Read report 'AML report' for full understanding of project): 

 1 - Creating 'video.mp4' of 'images' using 'merge_images_to_video.py' script. Note that the provided 'video.mp4' has 2000 images, but for this project I used only 1000 annotated images. If you will run this script again using the provided 'images' folder, it will only create the video for the given 1000 images. In my case I had 2000 images in 'images' folder thats why my video.mp4 turned out to have 2000 images.
 
 2 - Converting 'video.mp4' to 'video.mov'. Can be done using any reasobly good video player.
 
 3 - Importing 'video.mov' into the provided annotation tool.
 
 4 - Annotating the 1000 images. If you are using the given 'video.mov' then you need to manually stop after annotating the 1000th image. But if you created your own video.mp4' and 'video.mov' using the 'images', then you do not have to worry about stopping after 1000th image and your 'video.mov' will contain total 1000 images from the beginning. 
 
 5 - Downloading the 'AU_video.txt' file from annotation tool.
 
 6 - Using training.ipynb file for training the 5 models/DNNs. If you will be using the given 'AU_video.txt' then you would not face any issues or errors as I have tested it myself.
 
 7 - You will need 'image_names.txt' file for help in training.ipynb. Export 5 trained models using training.ipynb.
 
 8 - Use testing.ipynb for testing the trained models using 'new images'. As 'new images' only contain 10 images, you can manually annotate these inside testing.ipynb like I have done. You do not need to follow the whole annotation cycle for just 10 images. 
 
 9 - Evaluate your model using testing.ipynb.
 
 10 - Plan future work on this project.
 

NOTE: This project was developed for my university coursework in the beginning but it has been used as whole or partly on numerous occasions.   
