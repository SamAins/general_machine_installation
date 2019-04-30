## NVIDIA Drivers And CUDA

```
wget https://developer.download.nvidia.com/compute/cuda/repos/fedora29/x86_64/cuda-repo-fedora29-10.1.105-1.x86_64.rpm
rpm -i cuda-repo-fedora29-10.1.105-1.x86_64.rpm
dnf install cuda -y

```

Download and unpack cudnn from NVIDIA and then:
```
cp cuda/include/* /usr/local/cuda-10.1/include/.
cp cuda/lib64/* /usr/local/cuda-10.1/lib64/.

``` 
