# Kernel
1. 下载  
[源码](https://mirrors.edge.kernel.org/pub/linux/kernel/)
2. *指定硬件架构**
```
# export ARCH=x86
```
3. 配置
```
# make xxx_defconfig
# make menuconfig
```
4. 编译
```
# make -j
```

5. 编译完成  
内核路径：arch/x86_64/boot/bzImage