
<div align="center">   
  
# Which is Better for Learning with Noisy Labels: The Semi-supervised Method or Modeling Label Noise? 
[![Paper](https://img.shields.io/badge/ICML2023-green)](https://proceedings.mlr.press/v202/yao23a.html)

</div>

https://proceedings.mlr.press/v202/yao23a.html




## environment configuration

The code is only tested on Linux Linux-based system (Ubuntu 20.04). 
The Python version is 3.6.9. The Pytorh version is 1.2.0 with GPU acceleration. 

It is unknown if the code is compatible on Windows or different versions of Pytorh and Python. 
We have not tested to run our code in a CPU environment. 
To avoid errors caused by inconsistent environments, you are encouraged to run our code under the same environment.

For cifar10, the clustering method used is SPICE. We use the pre-trained model SPICE-Self*. The model and source code are downloaded via (https://github.com/niuchuangnn/SPICE)

## quick start

sudo chmod 755 *.sh

#########run xyguassian dataset################

./run_yxguassain.sh

#########run yxguassian dataset################

./run_yxguassain.sh

#########run other uci datasets################

./run_uci.sh

#########run mnist################

./run_mnist.sh


#########run cifar10################

./run_cifar10.sh







