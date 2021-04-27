- config

`bash benchmarks/dist_test_svm_pretrain.sh configs/selfsup/moco/r50_v1.py pretrains/moco_r50_v1-4ad89b5c.pth feat5 1  --deterministic`

- score  
Testing pretrain: pretrains/moco_r50_v1-4ad89b5c.pth  
For feature: feat5  
[INFO: test_svm.py:  126]: Mean AP: [0.79176294]  
For feature: feat5  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 31.47 / 27.04 / 34.59 / 2.51  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 38.4 / 35.33 / 41.13 / 1.98  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 49.12 / 47.26 / 52.43 / 1.82  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 58.25 / 57.81 / 58.59 / 0.29  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 65.55 / 64.89 / 66.06 / 0.39  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 71.02 / 70.35 / 71.47 / 0.41  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 74.52 / 74.05 / 75.19 / 0.39  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 76.28 / 75.68 / 76.71 / 0.35  
