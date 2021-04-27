- config  
`bash benchmarks/dist_test_svm_pretrain.sh configs/selfsup/simclr/r50_bs256_ep200.py pretrains/simclr_r50_bs256_ep200-4577e9a6.pth feat5 1  --deterministic`  
- score
Testing pretrain: pretrains/simclr_r50_bs256_ep200-4577e9a6.pth  
For feature: feat5  
[INFO: test_svm.py:  126]: Mean AP: [0.78950864]  
For feature: feat5  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 34.53 / 30.56 / 37.12 / 2.23  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 40.82 / 38.07 / 45.11 / 2.34  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 50.14 / 47.85 / 52.48 / 1.63  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 59.23 / 58.04 / 60.11 / 0.73  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 65.24 / 64.53 / 66.57 / 0.69  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 70.28 / 69.31 / 71.18 / 0.63  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 73.65 / 73.27 / 74.05 / 0.28  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 75.44 / 75.12 / 75.74 / 0.22  
