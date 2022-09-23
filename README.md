# CycleGAN and pix2pix in Jittor
This is basicly a copy of [CycleGAN and pix2pix in PyTorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix). The only difference is that it runs with [Jittor:a Just-in-time(JIT) deep learning framework](https://github.com/Jittor/jittor),if you have trouble installing Jittor, please checkout [their website](https://cg.cs.tsinghua.edu.cn/jittor/).And the training method and testing method is excatly the same with the torch implementation.


For training,run the next in terminal:
```shell
python train.py --dataroot ./datasets/facades --name facades_pix2pix --model pix2pix --direction BtoA
```

For testing,run the next in terminal:
```shell
python test.py --dataroot ./datasets/facades --direction BtoA --model pix2pix --name facades_pix2pix
```
See the pix2pix.ipynb file for a more detailed example for training and testing.