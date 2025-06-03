Add these lines to frigate config...

```
model:
  model_type: yolonas
  width: 320
  height: 320
  input_tensor: nchw
  input_pixel_format: bgr
  path: /config/models/320/yolo_nas_s.onnx
  labelmap_path: /config/models/320/coco80.txt
```
