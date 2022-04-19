# PointNet
The control experiment of 10 groups with the number of input point clouds of 50, 100, 250, 500, 1000, 2000, 3000, 4000 and 5000 was completed, and 100 epochs were trained each time.

# Result

## pointnet_log
Log file generated during training.

## pointnet_model 
Model obtained by training.

# Run the model
~~~
python pointnet.pytorch/utils/test_classification.py --model ./../pointnet_mode/100_model.pth --dataset <ModelNet40's path> --num_points=100 --feature_transform
~~~


# Citation
@misc{pointnet.pytorch,  
 &emsp;&emsp;author = {fxia22},  
 &emsp;&emsp;title = {PointNet.pytorch},  
 &emsp;&emsp;year = {2019},  
 &emsp;&emsp;url = {https://github.com/fxia22/pointnet.pytorch}  
}