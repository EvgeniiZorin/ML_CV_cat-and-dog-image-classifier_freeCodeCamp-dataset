
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0

tensorflow v 2.10.0

# Performance 

Number of images in the dataset for each split:
- Train: 2000
- Validation: 1000
- Test 50


| Model name | Batch size | Epochs | Img height / weight | Data augmentation | Test accuracy |
| - | - | - | - | - | - |
| M1 | 1 | 50 | 300/300 | RandomFlip, RandomRotation, RandomCrop | 0.480 |
| M2 | 10 | | | | 0.520 |
| M3 | 50 | | | | 0.720 |
| M4 | 100 | | | | 0.740 |

