# Automatic Power Pole Segmentation in Adverse Weather Conditions from Vehicle-based RGB images using Deep Learning

As an attempt to substantially automate the manual labour of critical electrical infrastructure maintenance, automatic segmentation of power poles is required. Various Deep Learning methods have shown learning capabilities for the same, for both UAV and ground-based imagery. This research study particularly focuses on the semantic segmentation of utility power poles from ground-based images taken under adverse weather conditions. The pre-trained High-Resolution Network (HRNet) architecture is used for dataset analysis and further finetuned using Google Street View (GSV) images with arctic weather scenery from the Iqaluit region in Nunavut, Canada, and the Canadian Adverse Driving Conditions (CADC) Dataset with ground-based imagery with adverse weather conditions from the Waterloo region in Ontario, Canada. Segmentation of poles in images with higher occlusion due to poor weather conditions proved to be the more difficult task. The HRNet model, which is trained for scene segmentation of ground-based imagery for multiple objects including poles, exhibits adaptability to learning semantic segmentation of poles in the GSV arctic urban images but significantly showcases a decrease in segmentation accuracy, even when examples of such images were included in the fine-tuning datasets.


## You can find the fine-tuned weights in the "weights" tag.

poles_hrnet_iqaluit: Pretrained HRNet with Cityscapes dataset further finetuned with 207 GSV images from the Iqaluit Region

poles_hrnet_iqaluit_southernontario: Pretrained HRNet with Cityscapes dataset & GSV images from Southern Ontario further finetuned with 207 GSV images from the Iqaluit Region

poles_hrnet_waterloo: Pretrained HRNet with Cityscapes dataset further finetuned with 208 LIDAR images from the Waterloo Region
