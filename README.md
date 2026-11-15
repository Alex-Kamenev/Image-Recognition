# Image recognition experiments

Historical TensorFlow/Keras cats-versus-dogs notebook comparing custom convolutional
networks with InceptionV3 and VGG16 transfer learning.

Run Jupyter from `image_recognition/`; its `data/` directory contains train, validation
and test splits. CPU-only machines now skip GPU memory configuration safely. This
notebook uses legacy `ImageDataGenerator` APIs; use a compatible TensorFlow/Keras
legacy environment when reproducing the experiments. It also imports NumPy,
scikit-learn, Matplotlib and OpenCV. No dependency environment was originally pinned.

The saved outputs are historical, not a newly reproduced benchmark. Training can be
expensive and some exploratory cells deliberately reuse models or depend on earlier
cells. Review the experiment order before running the complete notebook. No retraining
was performed during maintenance; portability and test-directory selection were fixed.
