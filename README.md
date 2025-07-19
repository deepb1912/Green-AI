**Clean Water & Sanitation – Green AI Project**

**Overview**  
This project leverages energy-efficient machine learning (Green AI) to detect and segment water bodies from aerial imagery. It contributes to SDG 6 by promoting sustainable monitoring of water resources.

**Affiliation**  
Ajeenkya D Y Patil University  
Presented by: Sahil Dethe, Parth Patil, Deep Bhandari

**Objectives**  
- Segment lakes, rivers, and ponds from aerial images  
- Reduce environmental impact of ML training  
- Provide insights for sustainable water resource management

**Dataset**  
- Name: AIWR: Aerial Image Water Resource  
- Source: arXiv 2024, Wikipedia  
- Size: 800 annotated aerial images from NE Thailand  
- Features: RGB images + ground-truth masks; variation in water body shapes

**Methodology**  
- Platform: Jupyter Notebook  
- Model: Lightweight UNet  
- Optimization: Use ≤ 4-depth network, early stopping, tuned batch size  
- Preprocessing: Resize, normalize, and augment (flips, rotations)  
- Evaluation: Dice Loss, IoU; visualize results with side-by-side maps

**Results**  
Efficient segmentation with reduced resource use, demonstrating how AI can help manage water sustainably.

**References**  
- UN SDG 6: [https://unstats.un.org/sdgs/report/2025/Goal-06/](https://unstats.un.org/sdgs/report/2025/Goal-06/)  
- WHO Sanitation Guidelines: [https://apps.who.int/iris/bitstream/handle/10665/274939/9789241514705-eng.pdf](https://apps.who.int/iris/bitstream/handle/10665/274939/9789241514705-eng.pdf)  
- Springer SDG Encyclopedia: [https://link.springer.com/referencework/10.1007/978-3-319-70061-8](https://link.springer.com/referencework/10.1007/978-3-319-70061-8)

