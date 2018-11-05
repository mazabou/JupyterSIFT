## SIFT
This is an implementation (for educational purposes only) of the SIFT paper, adapted from [PythonSIFT](https://github.com/rmislam/PythonSIFT). 

It contains a step-by-step analysis of the algorithm as well as some experiments and benchmarking. Hopefully, the notebooks will be helpful to anyone reading! 


## Requirements
- Python 3
- Numpy
- SciPy
- Pillow

## Citation
```
@Article{Lowe2004,
author="Lowe, David G.",
title="Distinctive Image Features from Scale-Invariant Keypoints",
journal="International Journal of Computer Vision",
abstract="This paper presents a method for extracting distinctive invariant features from images that can be used to perform reliable matching between different views of an object or scene. The features are invariant to image scale and rotation, and are shown to provide robust matching across a substantial range of affine distortion, change in 3D viewpoint, addition of noise, and change in illumination. The features are highly distinctive, in the sense that a single feature can be correctly matched with high probability against a large database of features from many images. This paper also describes an approach to using these features for object recognition. The recognition proceeds by matching individual features to a database of features from known objects using a fast nearest-neighbor algorithm, followed by a Hough transform to identify clusters belonging to a single object, and finally performing verification through least-squares solution for consistent pose parameters. This approach to recognition can robustly identify objects among clutter and occlusion while achieving near real-time performance.",
}
```