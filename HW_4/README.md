The project implements a two-phase experimental approach:

### Phase 1: Intentional Overfitting
- Extended the base model (3 fully-connected layers) by adding 2 convolutional layers
- Deliberately induced overfitting through:
  - Excessive training epochs
  - Achieved train-test accuracy gap > 0.04 (validation threshold)

### Phase 2: Regularization & Optimization
Implemented corrective measures including:
1. **Architectural Improvements**:
   - Added `Dropout` layers
   - Incorporated `BatchNorm` normalization

2. **Training Protocol**:
   - Reduced number of epochs
   - Optimized until train-test accuracy gap < 0.015 (target threshold)

### Validation Metrics
- Tracked delta between training/test accuracy throughout
- Established quantitative benchmarks:
  - Overfit condition: Δaccuracy > 0.04
  - Optimized condition: Δaccuracy < 0.015
