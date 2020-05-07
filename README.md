# openvino_quantization

Link to find ResNet_V2_101 model:
https://www.tensorflow.org/lite/guide/hosted_models
Direct link to download this model:
https://storage.googleapis.com/download.tensorflow.org/models/tflite_11_05_08/resnet_v2_101.tgz

To run demo_classification_tf.py:
```bash
python demo_classification_tf.py --graph resnet_v2_101_299_frozen.pb --image example.jpeg
```

To run evaluate_tf.py:
```bash
python3 evaluate_tf.py --graph /<USER_DIRECTORY>/resnet_v2_101_299_frozen.pb --dataset /<USER_DIRECTORY>/ILSVRC2012_img_val/
```
Estimated accuracy:
```bash

```
