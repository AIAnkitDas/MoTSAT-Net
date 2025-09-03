# MoTSAT-Net
## This work is currently under review, submitted in part fulfilment of the requirements of the Degree of Master of Science at The University of Glasgow.
## We look forward to publishing this original research work - Original code will be available post peer-review process and on receiving a publication decision.

## Mobile Tri-level Scale-aware Attention-guided Transformer-based segmentation Network for Polyp Segmentation in Colonoscopy Frames:-
Prompt diagnosis and elimination of pre-malignant polyps can prevent Colorectal Cancer
in patients. Therefore, semantic segmentation of polyps in colonoscopy frames is vital.
Since endoscopists lack expertise, it is imperative to develop artificially-intelligent vision
paradigms that deliver automatic and accurate polyp segmentation results. In retrospect, nu-
merous Convolutional Neural Networks (CNN) and Vision Transformer (ViT) methods em-
ploying pre-trained backbones have registered state-of-the-art performance. The limitation
of such approaches is their large model size coupled with a significant degree of pretraining
bias. Our aim is to address this research gap by developing a lightweight and end-to-end
trainable deep learning framework. This research presents a CNN-ViT hybrid architecture
called MoTSAT-Net that stands for “Mobile Tri-level Scale-aware Attention-guided Trans-
former Network”. The novel MoTSAT-Net integrates Mobile Vision Transformer (Mobile-
ViT) blocks with Depthwise Separable Convolutions to capture long-range contextual de-
pendencies without sacrificing low-level semantic cues, thereby mitigating the standalone
shortcomings of CNNs and ViTs. The MoTSAT-Net encoder exploits wavelet pooling to
preserve coarse low-frequency polyp details, while suppressing high-frequency noise. Ad-
ditionally, it introduces a novel Tri-Level Scale-aware (TLS) attention scheme to extract ro-
bust, multi-scale polyp-features ranging from channel, spatial, and pixel-level dependencies.
MoTSAT-Net has outperformed relevant state-of-the-art methods in polyp segmentation over
the sophisticated Kvasir-SEG and CVC-ClinicDB datasets, achieving impressive Dice scores
of 0.8689 and 0.9295 respectively. MoTSAT-Net is a parametrically lightweight model with
4.655M parameters, which has undergone extensive quantitative, qualitative, cross dataset
evaluation, along with GradCAM-based explainable analysis, to prove its robustness, inter-
pretability, and generalization capability. 
