# Vins Course
**作者**：贺一家，高翔，崔华坤，赵松

**描述**：
这是一个用于深蓝学院教学的代码，她基于 VINS-Mono 框架，但不依赖 ROS, Ceres, G2o。这个代码非常基础，目的在于演示仅基于 Eigen 的后端 LM 算法，滑动窗口算法，鲁棒核函数等等 SLAM 优化中常见的算法。

### Licence
The source code is released under GPLv3 license.

We are still working on improving the code reliability. For any technical issues, please contact Yijia He <	heyijia2016@gmail.com> , Xiang Gao <<https://github.com/gaoxiang12>> or Huakun Cui<<https://github.com/StevenCui>>.

For commercial inquiries, please contact Song Zhao <?>

### 安装依赖项：

2. pangolin: <https://github.com/stevenlovegrove/Pangolin>

   用于 GUI 显示

2. opencv

3. Eigen

### 编译代码

```c++
mkdir build 
cd build
cmake ..
make -j4
../bin/run_euroc /home/dataset/EuRoC/MH-05/mav0/ ../config/
```

### 运行结果

![vins](doc/vins.gif)

### 感谢

我们使用了港科大沈老师组的 [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) 作为基础代码，非常感谢该组的工作。

