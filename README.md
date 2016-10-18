# CNN Level Set
CNN Level Set for image segmentation.

### Prerequisite

1. Pascal VOC 2012 dataset, download from: <http://host.robots.ox.ac.uk/pascal/VOC/voc2012/#devkit>

### Setup

1. Install `miniconda`
2. Do `conda env create`
3. Enter the env `source activate cnn-levelset`
4. Install [TensorFlow](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html), or for CPU, run `chmod +x tools/setup_tf.sh && ./setup_tf.sh`
5. Run `python experiment.py`
