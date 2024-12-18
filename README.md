Downloading https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz to ./data/cifar-10-python.tar.gz
100%|██████████| 170M/170M [00:18<00:00, 9.16MB/s]
Extracting ./data/cifar-10-python.tar.gz to ./data
Files already downloaded and verified
CUDA Available? True
cuda
/usr/local/lib/python3.10/dist-packages/torch/utils/data/dataloader.py:617: UserWarning: This DataLoader will create 4 worker processes in total. Our suggested max number of worker in current system is 2, which is smaller than what this DataLoader is going to create. Please be aware that excessive worker creation might get DataLoader running slow or even freeze, lower the worker number to avoid potential slowness/freeze if necessary.
  warnings.warn(
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
           Conv2d-13          [-1, 128, 16, 16]          73,728
             ReLU-14          [-1, 128, 16, 16]               0
      BatchNorm2d-15          [-1, 128, 16, 16]             256
          Dropout-16          [-1, 128, 16, 16]               0
           Conv2d-17           [-1, 16, 16, 16]           2,048
           Conv2d-18           [-1, 32, 16, 16]           4,608
             ReLU-19           [-1, 32, 16, 16]               0
      BatchNorm2d-20           [-1, 32, 16, 16]              64
          Dropout-21           [-1, 32, 16, 16]               0
           Conv2d-22           [-1, 64, 16, 16]          18,432
             ReLU-23           [-1, 64, 16, 16]               0
      BatchNorm2d-24           [-1, 64, 16, 16]             128
          Dropout-25           [-1, 64, 16, 16]               0
           Conv2d-26          [-1, 128, 14, 14]          73,728
             ReLU-27          [-1, 128, 14, 14]               0
      BatchNorm2d-28          [-1, 128, 14, 14]             256
          Dropout-29          [-1, 128, 14, 14]               0
           Conv2d-30           [-1, 16, 14, 14]           2,048
           Conv2d-31           [-1, 32, 14, 14]           4,608
             ReLU-32           [-1, 32, 14, 14]               0
      BatchNorm2d-33           [-1, 32, 14, 14]              64
          Dropout-34           [-1, 32, 14, 14]               0
           Conv2d-35             [-1, 64, 7, 7]          18,432
             ReLU-36             [-1, 64, 7, 7]               0
      BatchNorm2d-37             [-1, 64, 7, 7]             128
          Dropout-38             [-1, 64, 7, 7]               0
        AvgPool2d-39             [-1, 64, 1, 1]               0
           Conv2d-40             [-1, 10, 1, 1]             640
================================================================
Total params: 222,864
Trainable params: 222,864
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 4.86
Params size (MB): 0.85
Estimated Total Size (MB): 5.72
----------------------------------------------------------------
EPOCH: 0
Loss=1.4654209613800049 Batch_id=390 Accuracy=42.44: 100%|██████████| 391/391 [00:24<00:00, 16.10it/s]

Test set: Average loss: 1.2918, Accuracy: 5180/10000 (51.80%)

Learning Rate = 0.01

EPOCH: 1
Loss=1.1335591077804565 Batch_id=390 Accuracy=59.42: 100%|██████████| 391/391 [00:23<00:00, 16.62it/s]

Test set: Average loss: 1.0987, Accuracy: 6044/10000 (60.44%)

Learning Rate = 0.01

EPOCH: 2
Loss=0.8952425718307495 Batch_id=390 Accuracy=65.82: 100%|██████████| 391/391 [00:24<00:00, 16.06it/s]

Test set: Average loss: 0.9399, Accuracy: 6624/10000 (66.24%)

Learning Rate = 0.01

EPOCH: 3
Loss=1.1296963691711426 Batch_id=390 Accuracy=70.37: 100%|██████████| 391/391 [00:24<00:00, 16.20it/s]

Test set: Average loss: 0.7931, Accuracy: 7258/10000 (72.58%)

Learning Rate = 0.01

EPOCH: 4
Loss=0.6174470782279968 Batch_id=390 Accuracy=73.68: 100%|██████████| 391/391 [00:24<00:00, 16.15it/s]

Test set: Average loss: 0.7296, Accuracy: 7406/10000 (74.06%)

Learning Rate = 0.01

EPOCH: 5
Loss=0.6244825124740601 Batch_id=390 Accuracy=75.98: 100%|██████████| 391/391 [00:23<00:00, 16.47it/s]

Test set: Average loss: 0.6859, Accuracy: 7658/10000 (76.58%)

Learning Rate = 0.01

EPOCH: 6
Loss=0.6385086178779602 Batch_id=390 Accuracy=77.78: 100%|██████████| 391/391 [00:23<00:00, 16.58it/s]

Test set: Average loss: 0.6440, Accuracy: 7754/10000 (77.54%)

Learning Rate = 0.01

EPOCH: 7
Loss=0.597440779209137 Batch_id=390 Accuracy=78.95: 100%|██████████| 391/391 [00:22<00:00, 17.01it/s]

Test set: Average loss: 0.5998, Accuracy: 7948/10000 (79.48%)

Learning Rate = 0.01

EPOCH: 8
Loss=0.5482750535011292 Batch_id=390 Accuracy=79.97: 100%|██████████| 391/391 [00:23<00:00, 16.97it/s]

Test set: Average loss: 0.5654, Accuracy: 8058/10000 (80.58%)

Learning Rate = 0.01

EPOCH: 9
Loss=0.4579469561576843 Batch_id=390 Accuracy=81.18: 100%|██████████| 391/391 [00:22<00:00, 17.06it/s]

Test set: Average loss: 0.5622, Accuracy: 8054/10000 (80.54%)

Learning Rate = 0.01