- config

` bash benchmarks/dist_test_svm_pretrain.sh selfsup/moco/r50_v2.py pretrains/moco_r50_v2-e3b0c442.pth feat5 1  --deterministic`

- score  
Testing pretrain: pretrains/moco_r50_v2-e3b0c442.pth  
For feature: feat5  
[INFO: test_svm.py:  126]: Mean AP: [0.84264672]  
For feature: feat5  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 45.55 / 42.95 / 49.46 / 2.51  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 54.71 / 50.63 / 60.54 / 3.52  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 63.15 / 61.44 / 65.97 / 1.77  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 70.75 / 69.27 / 72.34 / 1.22  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 76.02 / 75.24 / 77.01 / 0.7  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 79.31 / 78.67 / 80.25 / 0.54  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 81.44 / 81.32 / 81.6 / 0.09  
[INFO: aggregate_low_shot_svm_stats.py:   95]: mean/min/max/std: 82.26 / 82.03 / 82.5 / 0.16  
