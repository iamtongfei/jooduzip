# JOODU: Joint Out-of-Distribution Detection and Uncertainty Estimation

This repository contains the implementation for the IROS 2023 paper on joint out-of-distribution detection and uncertainty estimation for trajectory prediction.

## Project Structure

```
joodu/
├── ood_detection/          # Out-of-distribution detection models
│   └── 000_lgmm/          # Large Gaussian Mixture Model
│       └── model/         # Model files (see README.md for details)
├── traj_pred/             # Trajectory prediction models
│   └── 000_enc_dec/       # Encoder-Decoder architecture
│       └── model/         # Model files (see README.md for details)
└── uncertainty_estimation/ # Uncertainty estimation models
    └── 000_e_reg/         # E-regression model
        └── model/         # Model files (see README.md for details)
```

## Model Files

Due to the large size of the trained models, the actual model files are not included in this repository. Each model directory contains a README.md file with information about the expected model file and its specifications.

### Available Models

1. **Out-of-Distribution Detection (LGMM)**
   - File: `lgmm_iros_2023.joblib`
   - Size: ~2.3MB
   - Purpose: Detect out-of-distribution samples

2. **Trajectory Prediction (Encoder-Decoder)**
   - File: `enc_dec_iros_2023.ckpt`
   - Size: ~30MB
   - Purpose: Predict future trajectories

3. **Uncertainty Estimation (E-regression)**
   - File: `e_reg_iros_2023.ckpt`
   - Size: ~69KB
   - Purpose: Estimate prediction uncertainty

## Getting Started

1. Clone this repository
2. Download the model files from the provided source (if available)
3. Place the model files in their respective directories
4. Follow the usage instructions in each module's documentation

## Citation

If you use this code in your research, please cite our IROS 2023 paper:

```bibtex
@inproceedings{joodu_iros2023,
  title={Joint Out-of-Distribution Detection and Uncertainty Estimation for Trajectory Prediction},
  author={Your Name},
  booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2023}
}
```

## License

[Add your license information here]

## Contact

For questions and issues, please contact [your email]. 