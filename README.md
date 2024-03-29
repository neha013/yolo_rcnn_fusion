# yolo_rcnn_fusion

***Pedestrian detection*** is one of the important applications of computer vision with key contributions in various
fields of human life such as intelligent vehicles, surveillance,
and advanced robotics. Considerable research has taken place
in protecting vulnerable road users particularly pedestrians due
to the high risk of accidents to ensure safety on roads. The
process of pedestrian detection is often marred by significant
intra-class variance due to varied postures and appearances,
exhibited by humans on roads. Other crucial issues like occlusion,
background complexity, lead to loss of accuracy in final detection
results. Detecting overlapping, occluded, and small objects in a
complex dataset like pedestrians, with acceptable accuracy, has
always been a challenging task. The proposed work unifies two
families of detectors, the first is one stage detector responsible
for precise bounding boxes but low recall value while the other
one is a family of two-stage detectors, giving a high recall value
but an imprecise number of bounding boxes. Adaptive fusion
of two generates enhanced detection accuracy and decreases the
overall *Log Average Miss Rate (LAMR)*. The performance of
the proposed work has been evaluated and assessed on three
publicly available datasets: *ETH*, *INRIA*, and *Central Pedestrian
crossing sequence*, which exhibits superior pedestrian detection
performance over the existing state-of-the-art.

![Capture](https://github.com/neha013/yolo_rcnn_fusion/assets/41139808/41825e7e-11df-4366-b2cd-316b2123809a)

This is python implementation of the paper: [A Deep Unified Pedestrian Detection Framework](https://ieeexplore.ieee.org/document/9753544)
