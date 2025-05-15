This implementation covers the complete panorama stitching pipeline from scratch, featuring:

_**Core Components**_
- **Feature Detection & Description**  
  `extract_key_points()` - SIFT-based keypoint and descriptor extraction
- **Feature Matching**  
  `match_key_points_numpy()` - Pure NumPy implementation of brute-force matching with cross-check (BFMatcher equivalent)
- **Homography Estimation**  
  `dlt_homography_normalized()` - Normalized Direct Linear Transform (DLT) implementation in NumPy
- **Panorama Pipeline**  
  `panorama_pipeline()` - Complete stitching workflow using OpenCV functions
