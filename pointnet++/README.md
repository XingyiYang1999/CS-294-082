# PointNet++
The control experiment of 10 groups with the number of input point clouds of 50, 100, 250, 500, 1000, 2000, 3000, 4000 and 5000 was completed, and 100 epochs were trained each time.

# Result

## pointnet2_log
Log file generated during training.

## pointnet2_model 

Model obtained by training. The model is saved in /Pointnet_Pointnet2_pytorch-master/log/classification/ .


# Run the model
~~~
python test_classification.py --log_dir <model dir> --num_points=<input number points>
~~~
For example
~~~
python test_classification.py --log_dir 50_cls_ssg --num_points=50
~~~


# Citation
@misc{Pytorch_Pointnet_Pointnet2,  
&emsp;&emsp;Author = {Xu Yan},  
&emsp;&emsp;Title = {Pointnet/Pointnet++ Pytorch},  
&emsp;&emsp;Journal = {https://github.com/yanx27/Pointnet_Pointnet2_pytorch},  
&emsp;&emsp;Year = {2019}
}