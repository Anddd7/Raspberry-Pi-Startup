# Raspberry Pi Startup

## 0412: Start the Pi

### 通电
- 5V3A type-c charger
- 散热器
    - CPU、GPU、内存
    - 散热风扇：红色接5V 黑色接GND
- HDMI
- 键鼠

### 初始化
- 按Raspberry OS的初始化引导走
- 更新系统和相关软件

### 编程工具
- vscode for debian (Raspberry OS是基于debian的)
- zsh
- docker
- git
- python

### debian apt国内源

- https://mirrors.tuna.tsinghua.edu.cn/help/raspbian/
- raspberry os is not fully supported by debian apt source

### docker in raspberry
https://www.cnblogs.com/kasnti/p/11833778.html

- `curl -fsSL https://get.docker.com -o get-docker.sh`
- `sudo usermod -aG docker $USER`
