Files already downloaded and verified
Files already downloaded and verified
CUDA Available? True
cuda
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
           Conv2d-28          [-1, 128, 14, 14]          73,728
             ReLU-29          [-1, 128, 14, 14]               0
      BatchNorm2d-30          [-1, 128, 14, 14]             256
          Dropout-31          [-1, 128, 14, 14]               0
           Conv2d-32           [-1, 16, 14, 14]           2,048
           Conv2d-33           [-1, 32, 14, 14]           4,608
             ReLU-34           [-1, 32, 14, 14]               0
      BatchNorm2d-35           [-1, 32, 14, 14]              64
          Dropout-36           [-1, 32, 14, 14]               0
           Conv2d-37             [-1, 64, 7, 7]          18,432
             ReLU-38             [-1, 64, 7, 7]               0
      BatchNorm2d-39             [-1, 64, 7, 7]             128
          Dropout-40             [-1, 64, 7, 7]               0
           Conv2d-41             [-1, 64, 7, 7]             640
           Conv2d-42            [-1, 128, 7, 7]           8,320
             ReLU-43            [-1, 128, 7, 7]               0
      BatchNorm2d-44            [-1, 128, 7, 7]             256
          Dropout-45            [-1, 128, 7, 7]               0
DepthwiseSeparableConv-46            [-1, 128, 7, 7]               0
        AvgPool2d-47            [-1, 128, 1, 1]               0
           Conv2d-48             [-1, 10, 1, 1]           1,280
================================================================
Total params: 167,952
Trainable params: 167,952
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 5.50
Params size (MB): 0.64
Estimated Total Size (MB): 6.15
----------------------------------------------------------------
EPOCH: 0
Loss=1.7189695835113525 Batch_id=390 Accuracy=38.77: 100%|██████████| 391/391 [00:30<00:00, 12.86it/s]

Test set: Average loss: 1.4120, Accuracy: 4764/10000 (47.64%)

Learning Rate = 0.01

EPOCH: 1
Loss=1.0850272178649902 Batch_id=390 Accuracy=52.15: 100%|██████████| 391/391 [00:30<00:00, 12.72it/s]

Test set: Average loss: 1.0884, Accuracy: 6092/10000 (60.92%)

Learning Rate = 0.01

EPOCH: 2
Loss=1.075197458267212 Batch_id=390 Accuracy=58.99: 100%|██████████| 391/391 [00:30<00:00, 13.00it/s]

Test set: Average loss: 1.0592, Accuracy: 6341/10000 (63.41%)

Learning Rate = 0.01

EPOCH: 3
Loss=0.8908108472824097 Batch_id=390 Accuracy=62.99: 100%|██████████| 391/391 [00:30<00:00, 12.98it/s]

Test set: Average loss: 0.8372, Accuracy: 7031/10000 (70.31%)

Learning Rate = 0.01

EPOCH: 4
Loss=0.9221165776252747 Batch_id=390 Accuracy=65.96: 100%|██████████| 391/391 [00:29<00:00, 13.39it/s]

Test set: Average loss: 0.7430, Accuracy: 7388/10000 (73.88%)

Learning Rate = 0.01

EPOCH: 5
Loss=0.5385757684707642 Batch_id=390 Accuracy=67.72: 100%|██████████| 391/391 [00:30<00:00, 12.63it/s]

Test set: Average loss: 0.7203, Accuracy: 7513/10000 (75.13%)

Learning Rate = 0.01

EPOCH: 6
Loss=0.7203976511955261 Batch_id=390 Accuracy=69.53: 100%|██████████| 391/391 [00:32<00:00, 11.91it/s]

Test set: Average loss: 0.6915, Accuracy: 7614/10000 (76.14%)

Learning Rate = 0.01

EPOCH: 7
Loss=0.7643371820449829 Batch_id=390 Accuracy=70.96: 100%|██████████| 391/391 [00:30<00:00, 12.87it/s]

Test set: Average loss: 0.6585, Accuracy: 7735/10000 (77.35%)

Learning Rate = 0.01

EPOCH: 8
Loss=1.0443222522735596 Batch_id=390 Accuracy=72.17: 100%|██████████| 391/391 [00:29<00:00, 13.12it/s]

Test set: Average loss: 0.6442, Accuracy: 7824/10000 (78.24%)

Learning Rate = 0.01

EPOCH: 9
Loss=0.8592268228530884 Batch_id=390 Accuracy=72.62: 100%|██████████| 391/391 [00:29<00:00, 13.12it/s]

Test set: Average loss: 0.6084, Accuracy: 7913/10000 (79.13%)

Learning Rate = 0.01

EPOCH: 10
Loss=0.9151142239570618 Batch_id=390 Accuracy=73.62: 100%|██████████| 391/391 [00:29<00:00, 13.28it/s]

Test set: Average loss: 0.5724, Accuracy: 8059/10000 (80.59%)

Learning Rate = 0.01

EPOCH: 11
Loss=0.7979899048805237 Batch_id=390 Accuracy=74.32: 100%|██████████| 391/391 [00:29<00:00, 13.07it/s]

Test set: Average loss: 0.5662, Accuracy: 8073/10000 (80.73%)

Learning Rate = 0.01

EPOCH: 12
Loss=0.6217381954193115 Batch_id=390 Accuracy=75.27: 100%|██████████| 391/391 [00:29<00:00, 13.06it/s]

Test set: Average loss: 0.5567, Accuracy: 8113/10000 (81.13%)

Learning Rate = 0.01

EPOCH: 13
Loss=0.6652392148971558 Batch_id=390 Accuracy=75.57: 100%|██████████| 391/391 [00:29<00:00, 13.05it/s]

Test set: Average loss: 0.5320, Accuracy: 8173/10000 (81.73%)

Learning Rate = 0.01

EPOCH: 14
Loss=0.7526963949203491 Batch_id=390 Accuracy=76.01: 100%|██████████| 391/391 [00:32<00:00, 12.08it/s]

Test set: Average loss: 0.5345, Accuracy: 8171/10000 (81.71%)

Learning Rate = 0.01

EPOCH: 15
Loss=0.7423626780509949 Batch_id=390 Accuracy=76.80: 100%|██████████| 391/391 [00:30<00:00, 12.85it/s]

Test set: Average loss: 0.4937, Accuracy: 8313/10000 (83.13%)

Learning Rate = 0.01

EPOCH: 16
Loss=0.5244418978691101 Batch_id=390 Accuracy=76.96: 100%|██████████| 391/391 [00:30<00:00, 12.91it/s]

Test set: Average loss: 0.4980, Accuracy: 8304/10000 (83.04%)

Learning Rate = 0.01

EPOCH: 17
Loss=0.7348312735557556 Batch_id=390 Accuracy=77.51: 100%|██████████| 391/391 [00:29<00:00, 13.17it/s]

Test set: Average loss: 0.4905, Accuracy: 8319/10000 (83.19%)

Learning Rate = 0.01

EPOCH: 18
Loss=0.557018518447876 Batch_id=390 Accuracy=77.96: 100%|██████████| 391/391 [00:29<00:00, 13.05it/s]

Test set: Average loss: 0.4877, Accuracy: 8332/10000 (83.32%)

Learning Rate = 0.01

EPOCH: 19
Loss=0.705111563205719 Batch_id=390 Accuracy=78.18: 100%|██████████| 391/391 [00:30<00:00, 12.94it/s]

Test set: Average loss: 0.4657, Accuracy: 8426/10000 (84.26%)

Learning Rate = 0.01

EPOCH: 20
Loss=0.5907760262489319 Batch_id=390 Accuracy=78.29: 100%|██████████| 391/391 [00:29<00:00, 13.16it/s]

Test set: Average loss: 0.4532, Accuracy: 8441/10000 (84.41%)

Learning Rate = 0.01

EPOCH: 21
Loss=0.5677151679992676 Batch_id=390 Accuracy=78.70: 100%|██████████| 391/391 [00:29<00:00, 13.10it/s]

Test set: Average loss: 0.4544, Accuracy: 8462/10000 (84.62%)

Learning Rate = 0.01

EPOCH: 22
Loss=0.7409203052520752 Batch_id=390 Accuracy=79.15: 100%|██████████| 391/391 [00:31<00:00, 12.27it/s]

Test set: Average loss: 0.4561, Accuracy: 8451/10000 (84.51%)

Learning Rate = 0.001

EPOCH: 23
Loss=0.6016901731491089 Batch_id=390 Accuracy=80.74: 100%|██████████| 391/391 [00:30<00:00, 12.76it/s]

Test set: Average loss: 0.4074, Accuracy: 8612/10000 (86.12%)

Learning Rate = 0.001

EPOCH: 24
Loss=0.7034579515457153 Batch_id=390 Accuracy=81.82: 100%|██████████| 391/391 [00:31<00:00, 12.54it/s]

Test set: Average loss: 0.3974, Accuracy: 8631/10000 (86.31%)

Learning Rate = 0.001

EPOCH: 25
Loss=0.36901330947875977 Batch_id=390 Accuracy=81.90: 100%|██████████| 391/391 [00:30<00:00, 12.90it/s]

Test set: Average loss: 0.3982, Accuracy: 8648/10000 (86.48%)

Learning Rate = 0.001

EPOCH: 26
Loss=0.4636271595954895 Batch_id=390 Accuracy=82.21: 100%|██████████| 391/391 [00:30<00:00, 12.72it/s]

Test set: Average loss: 0.3952, Accuracy: 8658/10000 (86.58%)

Learning Rate = 0.001

EPOCH: 27
Loss=0.4217306971549988 Batch_id=390 Accuracy=82.12: 100%|██████████| 391/391 [00:30<00:00, 12.99it/s]

Test set: Average loss: 0.3952, Accuracy: 8652/10000 (86.52%)

Learning Rate = 0.001

EPOCH: 28
Loss=0.485289990901947 Batch_id=390 Accuracy=82.34: 100%|██████████| 391/391 [00:30<00:00, 12.89it/s]

Test set: Average loss: 0.3956, Accuracy: 8644/10000 (86.44%)

Learning Rate = 0.001

EPOCH: 29
Loss=0.4194835126399994 Batch_id=390 Accuracy=82.33: 100%|██████████| 391/391 [00:30<00:00, 12.82it/s]

Test set: Average loss: 0.3888, Accuracy: 8675/10000 (86.75%)

Learning Rate = 0.001

EPOCH: 30
Loss=0.6461837887763977 Batch_id=390 Accuracy=82.29: 100%|██████████| 391/391 [00:31<00:00, 12.53it/s]

Test set: Average loss: 0.3889, Accuracy: 8681/10000 (86.81%)

Learning Rate = 0.001

EPOCH: 31
Loss=0.5050350427627563 Batch_id=390 Accuracy=82.45: 100%|██████████| 391/391 [00:30<00:00, 12.92it/s]

Test set: Average loss: 0.3896, Accuracy: 8681/10000 (86.81%)

Learning Rate = 0.0001

EPOCH: 32
Loss=0.5209991931915283 Batch_id=390 Accuracy=82.54: 100%|██████████| 391/391 [00:30<00:00, 12.64it/s]

Test set: Average loss: 0.3871, Accuracy: 8696/10000 (86.96%)

Learning Rate = 0.0001

EPOCH: 33
Loss=0.3787476420402527 Batch_id=390 Accuracy=82.50: 100%|██████████| 391/391 [00:31<00:00, 12.37it/s]

Test set: Average loss: 0.3882, Accuracy: 8684/10000 (86.84%)

Learning Rate = 0.0001

EPOCH: 34
Loss=0.5113968253135681 Batch_id=390 Accuracy=82.75: 100%|██████████| 391/391 [00:31<00:00, 12.45it/s]

Test set: Average loss: 0.3866, Accuracy: 8689/10000 (86.89%)

Learning Rate = 0.0001