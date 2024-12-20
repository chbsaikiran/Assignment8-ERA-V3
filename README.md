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
Loss=1.5444616079330444 Batch_id=390 Accuracy=35.96: 100%|██████████| 391/391 [00:33<00:00, 11.52it/s]

Test set: Average loss: 0.0109, Accuracy: 4808/10000 (48.08%)

Learning Rate = 0.01

EPOCH: 1
Loss=1.2913213968276978 Batch_id=390 Accuracy=49.01: 100%|██████████| 391/391 [00:34<00:00, 11.33it/s]

Test set: Average loss: 0.0094, Accuracy: 5631/10000 (56.31%)

Learning Rate = 0.01

EPOCH: 2
Loss=1.1752831935882568 Batch_id=390 Accuracy=55.26: 100%|██████████| 391/391 [00:34<00:00, 11.49it/s]

Test set: Average loss: 0.0085, Accuracy: 6200/10000 (62.00%)

Learning Rate = 0.01

EPOCH: 3
Loss=1.1211398839950562 Batch_id=390 Accuracy=59.31: 100%|██████████| 391/391 [00:34<00:00, 11.46it/s]

Test set: Average loss: 0.0076, Accuracy: 6674/10000 (66.74%)

Learning Rate = 0.01

EPOCH: 4
Loss=1.1207035779953003 Batch_id=390 Accuracy=61.99: 100%|██████████| 391/391 [00:35<00:00, 11.08it/s]

Test set: Average loss: 0.0079, Accuracy: 6601/10000 (66.01%)

Learning Rate = 0.01

EPOCH: 5
Loss=0.9666910171508789 Batch_id=390 Accuracy=64.55: 100%|██████████| 391/391 [00:37<00:00, 10.38it/s]

Test set: Average loss: 0.0066, Accuracy: 7052/10000 (70.52%)

Learning Rate = 0.01

EPOCH: 6
Loss=1.004012107849121 Batch_id=390 Accuracy=65.74: 100%|██████████| 391/391 [00:34<00:00, 11.23it/s]

Test set: Average loss: 0.0062, Accuracy: 7268/10000 (72.68%)

Learning Rate = 0.01

EPOCH: 7
Loss=0.889618992805481 Batch_id=390 Accuracy=67.62: 100%|██████████| 391/391 [00:36<00:00, 10.73it/s]

Test set: Average loss: 0.0062, Accuracy: 7227/10000 (72.27%)

Learning Rate = 0.01

EPOCH: 8
Loss=0.9831086993217468 Batch_id=390 Accuracy=68.97: 100%|██████████| 391/391 [00:33<00:00, 11.52it/s]

Test set: Average loss: 0.0058, Accuracy: 7417/10000 (74.17%)

Learning Rate = 0.01

EPOCH: 9
Loss=0.8356958627700806 Batch_id=390 Accuracy=69.73: 100%|██████████| 391/391 [00:35<00:00, 10.87it/s]

Test set: Average loss: 0.0053, Accuracy: 7643/10000 (76.43%)

Learning Rate = 0.01

EPOCH: 10
Loss=0.7694214582443237 Batch_id=390 Accuracy=70.64: 100%|██████████| 391/391 [00:33<00:00, 11.74it/s]

Test set: Average loss: 0.0053, Accuracy: 7680/10000 (76.80%)

Learning Rate = 0.01

EPOCH: 11
Loss=0.7712114453315735 Batch_id=390 Accuracy=71.78: 100%|██████████| 391/391 [00:37<00:00, 10.33it/s]

Test set: Average loss: 0.0051, Accuracy: 7755/10000 (77.55%)

Learning Rate = 0.01

EPOCH: 12
Loss=1.0202252864837646 Batch_id=390 Accuracy=71.95: 100%|██████████| 391/391 [00:34<00:00, 11.41it/s]

Test set: Average loss: 0.0049, Accuracy: 7851/10000 (78.51%)

Learning Rate = 0.01

EPOCH: 13
Loss=0.7231109142303467 Batch_id=390 Accuracy=72.83: 100%|██████████| 391/391 [00:35<00:00, 11.06it/s]

Test set: Average loss: 0.0050, Accuracy: 7881/10000 (78.81%)

Learning Rate = 0.01

EPOCH: 14
Loss=0.6041799783706665 Batch_id=390 Accuracy=73.34: 100%|██████████| 391/391 [00:34<00:00, 11.34it/s]

Test set: Average loss: 0.0047, Accuracy: 7950/10000 (79.50%)

Learning Rate = 0.01

EPOCH: 15
Loss=0.9335792660713196 Batch_id=390 Accuracy=74.02: 100%|██████████| 391/391 [00:35<00:00, 10.99it/s]

Test set: Average loss: 0.0049, Accuracy: 7903/10000 (79.03%)

Learning Rate = 0.01

EPOCH: 16
Loss=0.9133586883544922 Batch_id=390 Accuracy=74.42: 100%|██████████| 391/391 [00:34<00:00, 11.47it/s]

Test set: Average loss: 0.0045, Accuracy: 8091/10000 (80.91%)

Learning Rate = 0.01

EPOCH: 17
Loss=0.5040464401245117 Batch_id=390 Accuracy=74.81: 100%|██████████| 391/391 [00:36<00:00, 10.66it/s]

Test set: Average loss: 0.0043, Accuracy: 8136/10000 (81.36%)

Learning Rate = 0.01

EPOCH: 18
Loss=0.6961399912834167 Batch_id=390 Accuracy=75.27: 100%|██████████| 391/391 [00:34<00:00, 11.44it/s]

Test set: Average loss: 0.0043, Accuracy: 8183/10000 (81.83%)

Learning Rate = 0.01

EPOCH: 19
Loss=0.7452888488769531 Batch_id=390 Accuracy=75.74: 100%|██████████| 391/391 [00:35<00:00, 11.04it/s]

Test set: Average loss: 0.0042, Accuracy: 8165/10000 (81.65%)

Learning Rate = 0.01

EPOCH: 20
Loss=0.6514971256256104 Batch_id=390 Accuracy=75.96: 100%|██████████| 391/391 [00:35<00:00, 11.02it/s]

Test set: Average loss: 0.0043, Accuracy: 8136/10000 (81.36%)

Learning Rate = 0.01

EPOCH: 21
Loss=0.7133843302726746 Batch_id=390 Accuracy=76.64: 100%|██████████| 391/391 [00:35<00:00, 10.93it/s]

Test set: Average loss: 0.0040, Accuracy: 8276/10000 (82.76%)

Learning Rate = 0.01

EPOCH: 22
Loss=0.7067175507545471 Batch_id=390 Accuracy=76.99: 100%|██████████| 391/391 [00:37<00:00, 10.48it/s]

Test set: Average loss: 0.0041, Accuracy: 8236/10000 (82.36%)

Learning Rate = 0.01

EPOCH: 23
Loss=0.705630898475647 Batch_id=390 Accuracy=76.81: 100%|██████████| 391/391 [00:35<00:00, 11.13it/s]

Test set: Average loss: 0.0039, Accuracy: 8321/10000 (83.21%)

Learning Rate = 0.01

EPOCH: 24
Loss=0.5824324488639832 Batch_id=390 Accuracy=77.46: 100%|██████████| 391/391 [00:37<00:00, 10.40it/s]

Test set: Average loss: 0.0040, Accuracy: 8250/10000 (82.50%)

Learning Rate = 0.01

EPOCH: 25
Loss=0.8632115125656128 Batch_id=390 Accuracy=77.46: 100%|██████████| 391/391 [00:35<00:00, 10.95it/s]

Test set: Average loss: 0.0039, Accuracy: 8282/10000 (82.82%)

Learning Rate = 0.001

EPOCH: 26
Loss=0.5867726802825928 Batch_id=390 Accuracy=79.37: 100%|██████████| 391/391 [00:34<00:00, 11.23it/s]

Test set: Average loss: 0.0035, Accuracy: 8490/10000 (84.90%)

Learning Rate = 0.001

EPOCH: 27
Loss=0.5313811898231506 Batch_id=390 Accuracy=80.10: 100%|██████████| 391/391 [00:36<00:00, 10.59it/s]

Test set: Average loss: 0.0035, Accuracy: 8491/10000 (84.91%)

Learning Rate = 0.001

EPOCH: 28
Loss=0.5950283408164978 Batch_id=390 Accuracy=80.21: 100%|██████████| 391/391 [00:36<00:00, 10.75it/s]

Test set: Average loss: 0.0035, Accuracy: 8513/10000 (85.13%)

Learning Rate = 0.001

EPOCH: 29
Loss=0.7690418362617493 Batch_id=390 Accuracy=80.22: 100%|██████████| 391/391 [00:35<00:00, 10.89it/s]

Test set: Average loss: 0.0034, Accuracy: 8512/10000 (85.12%)

Learning Rate = 0.001

EPOCH: 30
Loss=0.6467881798744202 Batch_id=390 Accuracy=80.53: 100%|██████████| 391/391 [00:39<00:00,  9.95it/s]

Test set: Average loss: 0.0034, Accuracy: 8516/10000 (85.16%)

Learning Rate = 0.001

EPOCH: 31
Loss=0.8064430952072144 Batch_id=390 Accuracy=80.47: 100%|██████████| 391/391 [00:35<00:00, 11.07it/s]

Test set: Average loss: 0.0034, Accuracy: 8548/10000 (85.48%)

Learning Rate = 0.001

EPOCH: 32
Loss=0.6808415651321411 Batch_id=390 Accuracy=80.67: 100%|██████████| 391/391 [00:35<00:00, 11.05it/s]

Test set: Average loss: 0.0034, Accuracy: 8550/10000 (85.50%)

Learning Rate = 0.001

EPOCH: 33
Loss=0.6715977787971497 Batch_id=390 Accuracy=80.98: 100%|██████████| 391/391 [00:36<00:00, 10.58it/s]

Test set: Average loss: 0.0034, Accuracy: 8532/10000 (85.32%)

Learning Rate = 0.001

EPOCH: 34
Loss=0.3836727440357208 Batch_id=390 Accuracy=80.77: 100%|██████████| 391/391 [00:35<00:00, 11.08it/s]

Test set: Average loss: 0.0034, Accuracy: 8529/10000 (85.29%)

Learning Rate = 0.001

EPOCH: 35
Loss=0.638141930103302 Batch_id=390 Accuracy=80.71: 100%|██████████| 391/391 [00:35<00:00, 11.02it/s]

Test set: Average loss: 0.0034, Accuracy: 8538/10000 (85.38%)

Learning Rate = 0.001

EPOCH: 36
Loss=0.386534720659256 Batch_id=390 Accuracy=81.07: 100%|██████████| 391/391 [00:37<00:00, 10.41it/s]

Test set: Average loss: 0.0034, Accuracy: 8524/10000 (85.24%)

Learning Rate = 0.001

EPOCH: 37
Loss=0.7344803810119629 Batch_id=390 Accuracy=80.91: 100%|██████████| 391/391 [00:34<00:00, 11.40it/s]

Test set: Average loss: 0.0034, Accuracy: 8529/10000 (85.29%)

Learning Rate = 0.001

EPOCH: 38
Loss=0.3976342976093292 Batch_id=390 Accuracy=80.88: 100%|██████████| 391/391 [00:34<00:00, 11.47it/s]

Test set: Average loss: 0.0034, Accuracy: 8529/10000 (85.29%)

Learning Rate = 0.0001

EPOCH: 39
Loss=0.5361093282699585 Batch_id=390 Accuracy=81.37: 100%|██████████| 391/391 [00:34<00:00, 11.28it/s]

Test set: Average loss: 0.0034, Accuracy: 8538/10000 (85.38%)

Learning Rate = 0.0001

EPOCH: 40
Loss=0.5013116598129272 Batch_id=390 Accuracy=81.41: 100%|██████████| 391/391 [00:33<00:00, 11.52it/s]

Test set: Average loss: 0.0033, Accuracy: 8547/10000 (85.47%)

Learning Rate = 0.0001

EPOCH: 41
Loss=0.5299443006515503 Batch_id=390 Accuracy=81.59: 100%|██████████| 391/391 [00:34<00:00, 11.30it/s]

Test set: Average loss: 0.0034, Accuracy: 8544/10000 (85.44%)

Learning Rate = 0.0001

EPOCH: 42
Loss=0.43941718339920044 Batch_id=390 Accuracy=81.28: 100%|██████████| 391/391 [00:39<00:00,  9.97it/s]

Test set: Average loss: 0.0034, Accuracy: 8544/10000 (85.44%)

Learning Rate = 0.0001

EPOCH: 43
Loss=0.5760367512702942 Batch_id=390 Accuracy=81.41: 100%|██████████| 391/391 [00:38<00:00, 10.09it/s]

Test set: Average loss: 0.0033, Accuracy: 8547/10000 (85.47%)

Learning Rate = 0.0001

EPOCH: 44
Loss=0.5156272053718567 Batch_id=390 Accuracy=81.04: 100%|██████████| 391/391 [00:39<00:00,  9.78it/s]

Test set: Average loss: 0.0033, Accuracy: 8544/10000 (85.44%)

Learning Rate = 0.0001