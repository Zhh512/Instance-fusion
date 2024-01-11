# Instance-fusion
Abstract—Multi-sensor fusion is crucial for accurate 3D ob-
ject detection in autonomous driving, as it directly impacts
subsequent planning and decision-making. We fuse camera and
millimeter-wave radar for 3D object detection, considering the
robustness of radar in adverse weather. However, fusing sparse
geometric information from radar with dense semantic informa-
tion from images is challenging. Most works process radar points
using the voxel feature extraction method following LIDAR,
which is often ineffective and may result in information loss
as the sparsity of radar point clouds. To overcome this, we
propose an instance fusion model to effectively integrate the two
modalities. Leveraging the instance characteristics of queries, we
associate and fuse them with radar voxel instances in geometric
space, which significantly improves the detection accuracy of
objects in velocity measurement, resulting in a 32.9% reduction
in velocity error. In addition, radar data is used to enhance
the perception awareness of the foreground on images in the
data stage. Then, in the feature fusion stage, a cross-attention
is employed to adaptively fuse the features of both modalities,
avoiding the neglect of weak modality information. Through the
above operations, we fully exploited the multi-level information
from radar and validate the effectiveness of fusion at different
stages. Our single-frame radar-camera fusion model achieves an
NDS of 49.7% and a map of 41.5% on the nuScenes dataset. 
![overview](https://github.com/Zhh512/Instance-fusion/assets/73172804/9a697dd8-fda4-4e8e-90de-a673059013fb)


The subsequent code will be updated after the article is published.





