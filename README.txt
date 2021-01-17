Data used from: https://www.kaggle.com/selfishgene/youtube-faces-with-facial-keypoints
Face bounds were taken from dlib's frontal face detector, which is what this is intended to be used with.

Training MAE: 1.40
Testing MAE: 1.46

Training parameters:

options.tree_depth = 4
options.nu = 0.1
options.cascade_depth = 15
options.feature_pool_size = 1024
options.num_test_splits = 100
options.oversampling_amount = 5
options.oversampling_translation_jitter = 0.3

References:

Lior Wolf, Tal Hassner and Itay Maoz
Face Recognition in Unconstrained Videos with Matched Background Similarity.
IEEE Conf. on Computer Vision and Pattern Recognition (CVPR), 2011.

Adrian Bulat and Georgios Tzimiropoulos.
How far are we from solving the 2D & 3D Face Alignment problem?
(and a dataset of 230,000 3D facial landmarks), arxiv, 2017.