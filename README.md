# magic_home

magichome custom component for Home Assistant based on：[magichome-python](https://github.com/adamkempenich/magichome-python)

## Installation
Copy magic_home folder with all files inside to the custom_components directory in your home assistant installation dir.
Add the following entry to your configuration.yaml
```yml
light:
  - platform: magic_home
    ip: 10.0.1.254 #your_device_ip
    dev_type: 5  #your_device_type (from magichome-python)
```
---

# magic_home
magichome灯光控制器接入home assistant插件
参考与引用：[magichome-python](https://github.com/adamkempenich/magichome-python)
## 安装方法
将magic_home目录复制到config/custom_components/下
在configuration.yaml文件中增加配置：
```
light:
  - platform: magic_home
    ip: 10.0.1.254 #your_device_ip
    dev_type: 5  #your_device_type
```
