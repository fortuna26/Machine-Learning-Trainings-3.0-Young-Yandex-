## Edge & Feature Extraction
- **Edge Detection**: Sobel filter with 3×3 kernels (x/y gradients)
- **Gradient Analysis**: Simplified HOG pipeline:
  1. Compute gradient magnitudes/orientations  
  2. Bin orientations into 9 histogram channels  
  3. (Optional) Block normalization omitted for simplicity
