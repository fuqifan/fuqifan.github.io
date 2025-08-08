---
title: "Robust Photo-Realistic Hand Gesture Generation: from Single View to Multiple View"
collection: publications
permalink: /publication/2025-08-MUFEN
excerpt: "Hand Gesture Generation"
date: 2025-08-08
venue: 'Proceedings of the 33rd ACM International Conference on Multimedia (ACM MM 2025)'
imageurl: '/images/publications/006MUFEN.PNG'
paperurl: '/files/006_Robust Photo-Realistic_Hand_Gesture_Generation_from_Single_View_to_Multiple_View.pdf'
link: 'https://doi.org/10.1145/3746027.3755828'
citation: '<strong>Q. Fu</strong>, X. Chen, M. Asad, S. Yuan, C. Oh and G. Slabaugh, "Robust Photo-Realistic Hand Gesture Generation: from Single View to Multiple View," in  Proceedings of the 33rd ACM International Conference on Multimedia, doi: 10.1145/3746027.3755828.
'
---
<center><img src = '/images/publications/006MUFEN.PNG'></center>
## Abstract
High-fidelity hand gesture generation represents a significant challenge in human-centric generation tasks. Existing methods typically employ single-view 3D MANO mesh-rendered images prior to enhancing gesture generation quality. However, the complexity of hand movements and the inherent limitations of single-view rendering make it difficult to capture complete 3D hand information, particularly when fingers are occluded. The fundamental contradiction lies in the loss of 3D topological relationships through 2D projection and the incomplete spatial coverage inherent to single-view representations. Diverging from single-view prior approaches, we propose a multi-view prior framework, named Multi-Modal UNet-based Feature Encoder (MUFEN), to guide diffusion models in learning comprehensive 3D hand information. Specifically, we extend conventional front-view rendering to include rear, left, right, top, and bottom perspectives, selecting the most information-rich view combination as training priors to address occlusion completion. This multi-view prior with a dedicated dual stream encoder significantly improves the model's understanding of complete hand features. Furthermore, we design a bounding box feature fusion module, which can fuse the gesture localization features and gesture multi-modal features to enhance the location-awareness of the MUFEN features to the gesture-related features. Experiments demonstrate that our method achieves state-of-the-art performance in both quantitative metrics and qualitative evaluations.

## Files
- [Paper](/files/006_Robust Photo-Realistic_Hand_Gesture_Generation_from_Single_View_to_Multiple_View.pdf)
