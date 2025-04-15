# Vivado 2022.2

---
### Download Vitis 2022.2 [[Website]](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vitis/archive-vitis.html)

* Vitis Core Development Kit - 2022.2  Full Product Installation
  * Xilinx Unified Installer 2022.2: Linux Self Extracting Web Installer (BIN - 271.02 MB)
* Vitis Core Development Kit Update 2 - 2022.2  Product Update
  * Xilinx Unified 2022.2.2 : All OS installer Single-File Download (TAR/GZIP - 18.88 GB)
    
---
### Download Installer
<img src="https://github.com/user-attachments/assets/c09a0a02-4c7a-49f0-886c-63a784a6d73a" width=750>

---
### Installation Destination Directory
<img src="https://github.com/user-attachments/assets/b99e8e5e-1667-478a-8c31-a6e5a4c7ac21" width=650>

---
### Download and Install files

<img src="https://github.com/user-attachments/assets/73cc5629-d146-4b5c-8502-a73a939c4d46" width=650>

 
---
### Final Processing

<img src="https://github.com/user-attachments/assets/35a8ecc6-d781-497f-a416-3b44803d81ca" width=650>
 

---
## Troubleshooting

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
