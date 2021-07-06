# Image and Video Segmentation

Object detection builds a bounding box for each detected object in the image, but it tells us nothing about the shape of the object. We only get the set of bounding box coordinates.

Instead, IMAGE SEGMENTATION is a technique that creates a pixel-wise mask for each detected object in the image and so can help us to obtain a far more granular understanding of the objects in the image.  This helps in understanding the image at a much lower level, i.e., the pixel level.   
More in detail, when we perform Image Segmentation, each pixel of the image is given a label. 

Furthermore, the same idea is applied in Video Object Segmentation. 

Again, VIDEO OBJECT SEGMENTATION is a binary labeling problem aiming to separate foreground object(s) from the background region of a video.   
The goal is always to automatically segment and generate pixel-wise masks for every detected object in a video.  

Image and Video segmentation has many applications, for instance in self-driving cars, medical imaging and satellite imaging.


![alt text](https://github.com/buropas/Image_Segmentation/blob/main/out_segm.png?raw=true)

Folder content:

- Image Segmentation (Instance Segmentation) with Mask R-CNN (Jupyter Notebook)
- Video Object Segmentation with Mask R-CNN (Jupyter Notebook)
- mask_rcnn_inception_v2_coco_2018_01_28.pbtxt (Mask R-CNN configuration file)
- out_segm.png (output image from Instance Segmentation task)
- segment_img.jpg (input image of Instance Segmentation task)
- test.mp4 (test video to perform Video Object Segmentation)
- segm_out_video.avi (output video from Video Segmentation task)


