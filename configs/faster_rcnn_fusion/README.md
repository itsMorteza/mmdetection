# Faster R-CNN + Fusion

For training a Faster R-CNN model with  "X" fusion, run:
```
python tools/train.py --config configs/faster_rcnn_fusion/faster_rcnn_r30_fpn_30e_kitti_ADD.py
```
currently, we support the following fusion methods:
- ADD
- CAT
- MUL
- BGF
- MFB 