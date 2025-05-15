## Edge & Feature Extraction
- **Edge Detection**: Sobel filter with 3×3 kernels (x/y gradients)
- **Gradient Analysis**: Simplified HOG pipeline:
  - Compute gradient magnitudes/orientations  
  - Bin orientations into 9 histogram channels  
  - (Optional) Block normalization omitted for simplicity
