

## train and test

The model A²S²C-DET is implemented based on [mmdetection](https://github.com/open-mmlab/mmdetection).

- **train (Take the NEU-DET dataset as an example.):**
  
  ```bash
  python train.py configs/MAFDet/mafdet_r50_mffe_daff_fpn_NEU-DET.py
  ```

- **test(Take the NEU-DET dataset as an example.):**
  
  ```bash
  python test.py configs/MAFDet/mafdet_r50_mffe_daff_fpn_NEU-DET.py path_to_checkpoint 
  ```


