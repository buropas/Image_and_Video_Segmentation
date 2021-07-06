# Image Segmentation

Object detection builds a bounding box for each detected object in the image, but it tells us nothing about the shape of the object. We only get the set of bounding box coordinates.

Instead, IMAGE SEGMENTATION is a technique that creates a pixel-wise mask for each detected object in the image and so can help us to obtain a far more granular understanding of the objects in the image.  This helps in understanding the image at a much lower level, i.e., the pixel level. 

Image segmentation has many applications, for instance in self-driving cars, medical imaging and satellite.

![alt text](https://github.com/buropas/Image_Segmentation/blob/main/out_segm.png?raw=true)

Folder content:

- Image Segmentation (Instance Segmentation) with Mask R-CNN (Jupyter Notebook)
- mask_rcnn_inception_v2_coco_2018_01_28.pbtxt (Mask R-CNN configuration file)
- out_segm.png (output image from Instance Segmentation task)
- segment_img.jpg (input image of Instance Segmentation task)
- test.mp4 (test video to perform Video Object Segmentation)


