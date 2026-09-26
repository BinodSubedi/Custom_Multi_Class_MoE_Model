This Repo contains MoE architecture models, for:<br/>
1.) Car<br/>
2.) Road

-> These are the specialized models for these specific class, and they each are passed through a router mode: road_car_router
  passing in the image with the inference pipeline to only those class models that croses a minimum thresshold, and finally it combines the mask
  to create a multi-class model with great accuracy with respect to number of parameters and speed of whole inferencing time.

<br/>
<p align="center">
  <img src="car_road_MoE_mask_seg.png" alt="MoE Car and Road Segmentation Mask Generated">
</p>
