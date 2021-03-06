中文|[英文](README_EN.md)

# tools

#### 介绍

Ascend tools，昇腾工具仓库。

**请根据自己的需要进入对应文件夹获取工具，或者点击下面的说明链接选择需要的工具进行使用。**

#### 使用说明

1.  [msame](https://github.com/Huawei-Ascend/tools/tree/master/msame)

    **模型推理工具**：输入.om模型和模型所需要的输入bin文件，输出模型的输出数据文件。

2.  [img2bin](https://github.com/Huawei-Ascend/tools/tree/master/img2bin)

    **bin文件生成工具**：生成模型推理所需的输入数据，以.bin格式保存。

3.  [makesd](https://github.com/Huawei-Ascend/tools/tree/master/makesd)
    
    **制卡工具**：制卡工具包，提供ubuntu下制卡功能。

4.  [faster_install](https://github.com/Huawei-Ascend/tools/tree/master/faster_install)
    
    **快速安装脚本**：环境快速安装脚本。

5.  [configure_usb_ethernet](https://github.com/Huawei-Ascend/tools/tree/master/configure_usb_ethernet)  
     **USB虚拟网卡连接脚本**：配置USB网卡对应的IP地址。
    
6. [pt2pb](https://github.com/Huawei-Ascend/tools/tree/master/pt2pb)  

   **pytorch模型转tensorflow pb模型工具**：输入pytorch权重参数模型，转为onnx，再转为pb模型

7. [dnmetis](https://github.com/Huawei-Ascend/tools/tree/master/dnmetis)  

   **NPU推理精度和性能测试工具**：使用Python封装ACL的C++接口，输入om模型和原始数据集图片、标签，即可执行模型推理，输出精度数据和性能数据
