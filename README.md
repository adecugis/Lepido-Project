# Lepido-Project
Characterizing patterns of butterfly coloration based on altitude and geolocation. 

1. Take out background of images
2. Apply model - imageomics/butterfly_segmentation_yolo_v8:yolov8m_shear_10.0_scale_0.5_translate_0.1_fliplr_0.0_best.pt
3. From generated masks, make a left-wing backgroundless image of the butterfly
4. Normalize the image pigmentation
