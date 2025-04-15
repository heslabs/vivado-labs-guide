# Vivado Labs Guide

---
### Xilinx Tools Installation

* Vivado 2022.2 Installation
    * https://github.com/heslabs/vivado-labs-guide/tree/main/2022p2
* Vivado 2022.4 Installation
    * https://github.com/heslabs/vivado-labs-guide/tree/main/2024p2


---
### Setup Xilinx License

* Create New license and Manage Licenses
   * https://github.com/heslabs/vivado-labs-guide/edit/main/license/readme.md


---
### Vitis installation problem in ubuntu O/S

Vitis 2022.2 Installer final processing is stalling on generating installed device list
Executing the following command and fixed the problem
$ sudo apt-get install libtinfo5


```
sudo apt update
sudo apt install libtinfo-dev
sudo ln -s /lib/x86_64-linux-gnu/libtinfo.so.6 /lib/x86_64-linux-gnu/libtinfo.so.5
```

```
sudo apt-get install ocl-icd-libopencl1
sudo apt-get install ocl-icd-opencl-dev
sudo apt-get install opencl-headers
sudo apt install libstdc++6
sudo apt install libncurses5
```
 
```
Can you please try downloading and installing All OS SFD installer for Vitis 2020.2, once downloaded it has all the files in it and doesn't require any internet connection, making it ready to install as it is:
https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vitis/2020-2.html
```
