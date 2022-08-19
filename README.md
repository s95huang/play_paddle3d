# play_paddle3d
goal is to deploy some paddle paddle algorithms to ROS1/2

## env setup
install paddle 3d
```
python -m pip install paddlepaddle-gpu==2.3.2
git clone https://github.com/PaddlePaddle/Paddle3D
cd Paddle3D && pip install -r requirements.txt
pip install .     # regular install

```


## versions (essential ones only)
```

numba                         0.53.1
numpy                         1.19.5
nuscenes-devkit               1.1.9
opencv-python                 4.6.0.66
paddle-bfloat                 0.1.7
paddle3d                      0.5.0
paddledet                     2.4.0
paddlepaddle-gpu              2.3.2
paddleseg                     2.6.0

```
