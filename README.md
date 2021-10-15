# Video-Data Pipelines for Machine Learning Applications 

## Submitted for review to MLSYS 2022 conference.

## Project Description
Computer Vision applications rely of large volumes of video data to be processed to learn the patterns related to the objects/regions of interest. From robotic vision to object detection and real-time object tracking applications for autonomous drive, there is a need to isolate _quality_ image frames from long sequence of videos that can then train respective machine learning (ML) applications. The video-data processing pipeline can be combined with modeling and deployment pipelines specifically for video/image-based ML applications. 
<img src=".media\Process-Overview.png" alt=".media\Process-Overview.png"></img>

## YAML Data Output
The `yaml` file contains the following metadata of the video:
- Number of original frames in the Video File when first split
- The frames removed during the Laplacian filter
- Laplacian variance spread of frames sent through the Laplacian filter
- The frames removed during the Structural Similarity filter
- Structural similarity spread of frames sent through the Structural Similarity filter
- Ratio and absolute number of frames removed during the Laplacian filter
- Ratio and absolute number of frames removed during the Structural Similarity filter
- Number of detected objects and classification counts of detected objects on the filtered frames by frame
- Scene classification of each frame

**Examples of the Output File can be found [HERE](https://github.com/James-Yuichi-Sato/MLSYS-2022-Video-Pipeline/Output-Examples/)**

<img src="media\yaml.png" alt="media\yaml.png"></img>

Example of `yaml` output

Please get in touch with me at jamesysato@gmail.com if you have any questions or inquiries.