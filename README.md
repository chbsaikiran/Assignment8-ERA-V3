Files already downloaded and verified
Files already downloaded and verified
CUDA Available? True
cuda
<pre>
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 16, 32, 32]             432
              ReLU-2           [-1, 16, 32, 32]               0
       BatchNorm2d-3           [-1, 16, 32, 32]              32
           Dropout-4           [-1, 16, 32, 32]               0
            Conv2d-5           [-1, 32, 32, 32]           4,608
              ReLU-6           [-1, 32, 32, 32]               0
       BatchNorm2d-7           [-1, 32, 32, 32]              64
           Dropout-8           [-1, 32, 32, 32]               0
            Conv2d-9           [-1, 64, 16, 16]          18,432
             ReLU-10           [-1, 64, 16, 16]               0
      BatchNorm2d-11           [-1, 64, 16, 16]             128
          Dropout-12           [-1, 64, 16, 16]               0
           Conv2d-13           [-1, 64, 16, 16]             640
           Conv2d-14          [-1, 128, 16, 16]           8,320
             ReLU-15          [-1, 128, 16, 16]               0
      BatchNorm2d-16          [-1, 128, 16, 16]             256
          Dropout-17          [-1, 128, 16, 16]               0
DepthwiseSeparableConv-18          [-1, 128, 16, 16]               0
           Conv2d-19           [-1, 16, 16, 16]           2,048
           Conv2d-20           [-1, 32, 16, 16]           4,608
             ReLU-21           [-1, 32, 16, 16]               0
      BatchNorm2d-22           [-1, 32, 16, 16]              64
          Dropout-23           [-1, 32, 16, 16]               0
           Conv2d-24           [-1, 64, 16, 16]          18,432
             ReLU-25           [-1, 64, 16, 16]               0
      BatchNorm2d-26           [-1, 64, 16, 16]             128
          Dropout-27           [-1, 64, 16, 16]               0
           Conv2d-28           [-1, 64, 16, 16]             640
           Conv2d-29          [-1, 128, 16, 16]           8,320
             ReLU-30          [-1, 128, 16, 16]               0
      BatchNorm2d-31          [-1, 128, 16, 16]             256
          Dropout-32          [-1, 128, 16, 16]               0
DepthwiseSeparableConv-33          [-1, 128, 16, 16]               0
           Conv2d-34           [-1, 16, 16, 16]           2,048
           Conv2d-35           [-1, 32, 16, 16]           4,608
             ReLU-36           [-1, 32, 16, 16]               0
      BatchNorm2d-37           [-1, 32, 16, 16]              64
          Dropout-38           [-1, 32, 16, 16]               0
           Conv2d-39           [-1, 64, 16, 16]          18,432
             ReLU-40           [-1, 64, 16, 16]               0
      BatchNorm2d-41           [-1, 64, 16, 16]             128
          Dropout-42           [-1, 64, 16, 16]               0
           Conv2d-43           [-1, 64, 16, 16]             640
           Conv2d-44          [-1, 128, 16, 16]           8,320
             ReLU-45          [-1, 128, 16, 16]               0
      BatchNorm2d-46          [-1, 128, 16, 16]             256
          Dropout-47          [-1, 128, 16, 16]               0
DepthwiseSeparableConv-48          [-1, 128, 16, 16]               0
           Conv2d-49           [-1, 16, 16, 16]           2,048
           Conv2d-50           [-1, 32, 16, 16]           4,608
             ReLU-51           [-1, 32, 16, 16]               0
      BatchNorm2d-52           [-1, 32, 16, 16]              64
          Dropout-53           [-1, 32, 16, 16]               0
           Conv2d-54           [-1, 64, 14, 14]          18,432
             ReLU-55           [-1, 64, 14, 14]               0
      BatchNorm2d-56           [-1, 64, 14, 14]             128
          Dropout-57           [-1, 64, 14, 14]               0
           Conv2d-58           [-1, 64, 14, 14]             640
           Conv2d-59          [-1, 128, 14, 14]           8,320
             ReLU-60          [-1, 128, 14, 14]               0
      BatchNorm2d-61          [-1, 128, 14, 14]             256
          Dropout-62          [-1, 128, 14, 14]               0
DepthwiseSeparableConv-63          [-1, 128, 14, 14]               0
        AvgPool2d-64            [-1, 128, 1, 1]               0
           Linear-65                   [-1, 10]           1,290
================================================================
Total params: 137,690
Trainable params: 137,690
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 9.41
Params size (MB): 0.53
Estimated Total Size (MB): 9.94
----------------------------------------------------------------
</pre>
EPOCH: 0
Loss=1.5671484470367432 Batch_id=390 Accuracy=36.39: 100%|██████████| 391/391 [00:31<00:00, 12.32it/s]

Test set: Average loss: 0.0111, Accuracy: 4778/10000 (47.78%)

Learning Rate = 0.01

EPOCH: 1
Loss=1.217728614807129 Batch_id=390 Accuracy=49.14: 100%|██████████| 391/391 [00:30<00:00, 12.68it/s]

Test set: Average loss: 0.0091, Accuracy: 5860/10000 (58.60%)

Learning Rate = 0.01

EPOCH: 2
Loss=1.1368730068206787 Batch_id=390 Accuracy=55.52: 100%|██████████| 391/391 [00:32<00:00, 12.00it/s]

Test set: Average loss: 0.0084, Accuracy: 6246/10000 (62.46%)

Learning Rate = 0.01

EPOCH: 3
Loss=1.0424096584320068 Batch_id=390 Accuracy=59.51: 100%|██████████| 391/391 [00:30<00:00, 12.66it/s]

Test set: Average loss: 0.0073, Accuracy: 6716/10000 (67.16%)

Learning Rate = 0.01

EPOCH: 4
Loss=1.2375929355621338 Batch_id=390 Accuracy=62.40: 100%|██████████| 391/391 [00:31<00:00, 12.51it/s]

Test set: Average loss: 0.0068, Accuracy: 6968/10000 (69.68%)

Learning Rate = 0.01

EPOCH: 5
Loss=0.954128623008728 Batch_id=390 Accuracy=64.49: 100%|██████████| 391/391 [00:31<00:00, 12.61it/s]

Test set: Average loss: 0.0066, Accuracy: 7072/10000 (70.72%)

Learning Rate = 0.01

EPOCH: 6
Loss=0.9377188682556152 Batch_id=390 Accuracy=66.27: 100%|██████████| 391/391 [00:32<00:00, 11.88it/s]

Test set: Average loss: 0.0060, Accuracy: 7341/10000 (73.41%)

Learning Rate = 0.01

EPOCH: 7
Loss=0.762121856212616 Batch_id=390 Accuracy=67.76: 100%|██████████| 391/391 [00:31<00:00, 12.41it/s]

Test set: Average loss: 0.0060, Accuracy: 7371/10000 (73.71%)

Learning Rate = 0.01

EPOCH: 8
Loss=0.7762648463249207 Batch_id=390 Accuracy=69.09: 100%|██████████| 391/391 [00:31<00:00, 12.50it/s]

Test set: Average loss: 0.0055, Accuracy: 7646/10000 (76.46%)

Learning Rate = 0.01

EPOCH: 9
Loss=0.7751310467720032 Batch_id=390 Accuracy=69.82: 100%|██████████| 391/391 [00:31<00:00, 12.43it/s]

Test set: Average loss: 0.0051, Accuracy: 7736/10000 (77.36%)

Learning Rate = 0.01

EPOCH: 10
Loss=0.6914436221122742 Batch_id=390 Accuracy=70.24: 100%|██████████| 391/391 [00:35<00:00, 11.11it/s]

Test set: Average loss: 0.0053, Accuracy: 7707/10000 (77.07%)

Learning Rate = 0.01

EPOCH: 11
Loss=0.8056640625 Batch_id=390 Accuracy=71.67: 100%|██████████| 391/391 [00:31<00:00, 12.39it/s]

Test set: Average loss: 0.0051, Accuracy: 7793/10000 (77.93%)

Learning Rate = 0.01

EPOCH: 12
Loss=0.9273383021354675 Batch_id=390 Accuracy=72.20: 100%|██████████| 391/391 [00:31<00:00, 12.34it/s]

Test set: Average loss: 0.0050, Accuracy: 7840/10000 (78.40%)

Learning Rate = 0.01

EPOCH: 13
Loss=0.8041922450065613 Batch_id=390 Accuracy=73.22: 100%|██████████| 391/391 [00:32<00:00, 12.14it/s]

Test set: Average loss: 0.0048, Accuracy: 7931/10000 (79.31%)

Learning Rate = 0.01

EPOCH: 14
Loss=0.6137233972549438 Batch_id=390 Accuracy=73.61: 100%|██████████| 391/391 [00:33<00:00, 11.51it/s]

Test set: Average loss: 0.0047, Accuracy: 7970/10000 (79.70%)

Learning Rate = 0.01

EPOCH: 15
Loss=0.9143632650375366 Batch_id=390 Accuracy=74.20: 100%|██████████| 391/391 [00:32<00:00, 11.87it/s]

Test set: Average loss: 0.0047, Accuracy: 7993/10000 (79.93%)

Learning Rate = 0.01

EPOCH: 16
Loss=0.7836505174636841 Batch_id=390 Accuracy=74.60: 100%|██████████| 391/391 [00:31<00:00, 12.49it/s]

Test set: Average loss: 0.0047, Accuracy: 7988/10000 (79.88%)

Learning Rate = 0.01

EPOCH: 17
Loss=0.5944662094116211 Batch_id=390 Accuracy=74.86: 100%|██████████| 391/391 [00:31<00:00, 12.49it/s]

Test set: Average loss: 0.0043, Accuracy: 8103/10000 (81.03%)

Learning Rate = 0.01

EPOCH: 18
Loss=0.7383915185928345 Batch_id=390 Accuracy=75.42: 100%|██████████| 391/391 [00:31<00:00, 12.51it/s]

Test set: Average loss: 0.0042, Accuracy: 8190/10000 (81.90%)

Learning Rate = 0.01

EPOCH: 19
Loss=0.7411434650421143 Batch_id=390 Accuracy=75.46: 100%|██████████| 391/391 [00:32<00:00, 12.05it/s]

Test set: Average loss: 0.0041, Accuracy: 8223/10000 (82.23%)

Learning Rate = 0.01

EPOCH: 20
Loss=0.6207647323608398 Batch_id=390 Accuracy=76.09: 100%|██████████| 391/391 [00:30<00:00, 12.80it/s]

Test set: Average loss: 0.0043, Accuracy: 8108/10000 (81.08%)

Learning Rate = 0.01

EPOCH: 21
Loss=0.8034059405326843 Batch_id=390 Accuracy=76.57: 100%|██████████| 391/391 [00:30<00:00, 12.64it/s]

Test set: Average loss: 0.0042, Accuracy: 8211/10000 (82.11%)

Learning Rate = 0.001

EPOCH: 22
Loss=0.7415013909339905 Batch_id=390 Accuracy=78.92: 100%|██████████| 391/391 [00:30<00:00, 12.79it/s]

Test set: Average loss: 0.0036, Accuracy: 8434/10000 (84.34%)

Learning Rate = 0.001

EPOCH: 23
Loss=0.7515274286270142 Batch_id=390 Accuracy=79.04: 100%|██████████| 391/391 [00:32<00:00, 12.03it/s]

Test set: Average loss: 0.0036, Accuracy: 8430/10000 (84.30%)

Learning Rate = 0.001

EPOCH: 24
Loss=0.6697172522544861 Batch_id=390 Accuracy=79.04: 100%|██████████| 391/391 [00:30<00:00, 12.76it/s]

Test set: Average loss: 0.0035, Accuracy: 8465/10000 (84.65%)

Learning Rate = 0.001

EPOCH: 25
Loss=0.6671388745307922 Batch_id=390 Accuracy=79.31: 100%|██████████| 391/391 [00:30<00:00, 12.73it/s]

Test set: Average loss: 0.0035, Accuracy: 8477/10000 (84.77%)

Learning Rate = 0.001

EPOCH: 26
Loss=0.5406225919723511 Batch_id=390 Accuracy=79.50: 100%|██████████| 391/391 [00:30<00:00, 12.73it/s]

Test set: Average loss: 0.0035, Accuracy: 8481/10000 (84.81%)

Learning Rate = 0.001

EPOCH: 27
Loss=0.6047564744949341 Batch_id=390 Accuracy=79.73: 100%|██████████| 391/391 [00:32<00:00, 11.99it/s]

Test set: Average loss: 0.0035, Accuracy: 8490/10000 (84.90%)

Learning Rate = 0.001

EPOCH: 28
Loss=0.7221367359161377 Batch_id=390 Accuracy=79.47: 100%|██████████| 391/391 [00:30<00:00, 12.69it/s]

Test set: Average loss: 0.0035, Accuracy: 8477/10000 (84.77%)

Learning Rate = 0.001

EPOCH: 29
Loss=0.7506778240203857 Batch_id=390 Accuracy=79.53: 100%|██████████| 391/391 [00:30<00:00, 12.74it/s]

Test set: Average loss: 0.0035, Accuracy: 8491/10000 (84.91%)

Learning Rate = 0.001

EPOCH: 30
Loss=0.5372615456581116 Batch_id=390 Accuracy=79.70: 100%|██████████| 391/391 [00:30<00:00, 12.79it/s]

Test set: Average loss: 0.0035, Accuracy: 8505/10000 (85.05%)

Learning Rate = 0.001

EPOCH: 31
Loss=0.6778744459152222 Batch_id=390 Accuracy=79.72: 100%|██████████| 391/391 [00:30<00:00, 12.80it/s]

Test set: Average loss: 0.0035, Accuracy: 8504/10000 (85.04%)

Learning Rate = 0.0001

EPOCH: 32
Loss=0.7876355051994324 Batch_id=390 Accuracy=80.13: 100%|██████████| 391/391 [00:32<00:00, 12.11it/s]

Test set: Average loss: 0.0035, Accuracy: 8498/10000 (84.98%)

Learning Rate = 0.0001

EPOCH: 33
Loss=0.6537963151931763 Batch_id=390 Accuracy=80.43: 100%|██████████| 391/391 [00:30<00:00, 12.90it/s]

Test set: Average loss: 0.0034, Accuracy: 8502/10000 (85.02%)

Learning Rate = 0.0001

EPOCH: 34
Loss=0.48237496614456177 Batch_id=390 Accuracy=80.37: 100%|██████████| 391/391 [00:30<00:00, 12.89it/s]

Test set: Average loss: 0.0035, Accuracy: 8513/10000 (85.13%)

Learning Rate = 0.0001

<pre>
Epoch    Training Loss    Training Accuracy (%)    Test Loss    Test Accuracy (%)
0        1.5671           36.39                    0.0111       47.78
1        1.2177           49.14                    0.0091       58.60
2        1.1369           55.52                    0.0084       62.46
3        1.0424           59.51                    0.0073       67.16
4        1.2376           62.40                    0.0068       69.68
5        0.9541           64.49                    0.0066       70.72
6        0.9377           66.27                    0.0060       73.41
7        0.7621           67.76                    0.0060       73.71
8        0.7763           69.09                    0.0055       76.46
9        0.7751           69.82                    0.0051       77.36
10        0.6914           70.24                    0.0053       77.07
11        0.8057           71.67                    0.0051       77.93
12        0.9273           72.20                    0.0050       78.40
13        0.8042           73.22                    0.0048       79.31
14        0.6137           73.61                    0.0047       79.70
15        0.9144           74.20                    0.0047       79.93
16        0.7837           74.60                    0.0047       79.88
17        0.5945           74.86                    0.0043       81.03
18        0.7384           75.42                    0.0042       81.90
19        0.7411           75.46                    0.0041       82.23
20        0.6208           76.09                    0.0043       81.08
21        0.8034           76.57                    0.0042       82.11
22        0.7415           78.92                    0.0036       84.34
23        0.7515           79.04                    0.0036       84.30
24        0.6697           79.04                    0.0035       84.65
25        0.6671           79.31                    0.0035       84.77
26        0.5406           79.50                    0.0035       84.81
27        0.6048           79.73                    0.0035       84.90
28        0.7221           79.47                    0.0035       84.77
29        0.7507           79.53                    0.0035       84.91
30        0.5373           79.70                    0.0035       85.05
31        0.6779           79.72                    0.0035       85.04
32        0.7876           80.13                    0.0035       84.98
33        0.6537           80.43                    0.0034       85.02
34        0.4823           80.37                    0.0035       85.13
</pre>