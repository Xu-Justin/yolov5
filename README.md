# patchmentation-yolov5

**DISCLAIMER: This repository is forked from [ultralytics/yolov5](https://github.com/ultralytics/yolov5/). Please refer to the original repository for more detail explanations and questions about the models or implementations.**

***THIS REPOSITORY IS UNDER DEVELOPMENT***

## Docker

TBA

## Training

```
python3 train.py \
    --data data/VOC-patchmentation.yaml --hyp data/hyps/hyp.patchmentation.yaml \
    --weights yolov5s.pt --epochs 300 --batch-size 32 \
    --project runs/patchmentation --name exp
```

## Testing

TBA

---

This project was developed as part of thesis project, Computer Science, BINUS University.
