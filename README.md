# Implementation of Appearance and Relation Network (ARTNET) for the task of action recognition in video classification.

Spatiotemporal feature learning in videos is a fundamental problem in computer vision. Appearance-and-Relation Network(ARTNet), learns video representation in an end-to-end manner. 
ARTNets are constructed by stacking multiple generic building blocks, called as SMART, whose goal is to simultaneously model appearance and relation from RGB input in a separate and explicit manner. 
SMART blocks decouple the spatiotemporal learning module into an appearance branch for spatial modeling and a relation branch for temporal modeling. 
The appearance branch is implemented based on the linear combination of pixels or filter responses in each frame. While the relation branch is designed based on the multiplicative interactions between pixels or filter responses across multiple frames. 
## SMART Block
![SMART block](https://github.com/maryam-fatima/Implementation-of-ARTNet-in-python]/blob/main/images/1.png?raw=true)
## Appearence and Relation Networks
![ARTNets](https://github.com/maryam-fatima/Implementation-of-ARTNet-in-python/blob/main/images/2.png?raw=true)
# Reference:
Wang, L., Li, W., Li, W., & Van Gool, L. (2018). Appearance-and-relation networks for video classification. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 1430-1439).
