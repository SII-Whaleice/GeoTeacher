# GeoTeacher: Geometry-Guided Semi-Supervised 3D Object Detection


<span style="color:gray">arXiv 2025</span>


## Abstract
Semi-supervised 3D object detection~(SS3D), aiming to explore unlabeled data for boosting 3D object detectors, has emerged as an active research area in recent years. 
Some previous methods have shown substantial improvements by either employing heterogeneous teacher models to provide high-quality pseudo labels or enforcing feature-perspective consistency between the teacher and student networks.
However, these methods overlook the fact that the model usually tends to exhibit low sensitivity to object geometries with limited labeled data, making it difficult to capture geometric information, which is crucial for enhancing the student model’s ability in object perception and localization.
In this paper, we propose GeoTeacher to enhance the student model's ability to capture geometric relations of objects with limited training data, especially unlabeled data. 
We design a keypoint-based geometric relation supervision module that transfers the teacher model’s knowledge of object geometry to the student, thereby improving the student’s capability in understanding geometric relations.
Furthermore, we introduce a voxel-wise data augmentation strategy that increases the diversity of object geometries, thereby further improving the student model’s ability to comprehend geometric structures. 
To preserve the integrity of distant objects during augmentation, we incorporate a distance-decay mechanism into this strategy.
Moreover, GeoTeacher can be combined with different SS3D methods to further improve their performance.
Extensive experiments on ONCE and Waymo datasets indicate the effectiveness and generalization of our method and we achieve the new state-of-the-art results. 



## News
2025.12, the paper is released on arXiv, and the code will be made publicly available upon acceptance.

## 📖 Citation

If you find our work useful, please cite:



