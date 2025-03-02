# GPU 环境检测脚本使用指南

## 🚀 快速使用
##1：gpu_env_check.sh：普通版 ubuntu系统、硬件自检脚本
##2：gpu_check_plus.sh ：Plus版 深度学习环境自检脚本
### 1. 克隆仓库
```bash
git clone https://github.com/DeepBuleLake/Automatic-script-check.git
cd Automatic-script-check
```

### 2. 运行检测脚本
----------------------------------------------------------------------------------------------------------------------------------
#### ✅ 深度学习环境检测（推荐）
```bash
chmod +x gpu_check_plus.sh
./gpu_check_plus.sh
```
检测完成后，查看报告：
```bash
cat system_report_*.txt
```
----------------------------------------------------------------------------------------------------------------------------------
#### 🛠 普通检测
```bash
dos2unix gpu_env_check.sh
./gpu_env_check.sh
cat system_report_*.txt
```
----------------------------------------------------------------------------------------------------------------------------------

#### ####📊 检测报告示例（深度学习环境自检）
**深度学习环境检测报告（2025-03-02 17:45）**

### 硬件信息
- **CPU**: AMD Ryzen 9 5950X 16-Core Processor
- **内存**: 31Gi
- **GPU**: NVIDIA GeForce RTX 2080 Ti

### 系统信息
- **操作系统**: Ubuntu 22.04.1 LTS
- **内核版本**: 5.15.167.4-microsoft-standard-WSL2

### CUDA 环境
- **编译器路径**: /home/bulidoge/miniconda3
- **系统 CUDA 版本**: 未安装
- **PyTorch CUDA 版本**: 12.1
- **cuDNN 版本**: 未检测到
- **计算能力**: 7.5

### Python 环境
- **Python 版本**: 3.12.9
- **Conda 版本**: 25.1.1
- **PyTorch 版本**: 2.5.1
----------------------------------------------------------------------------------------------------------------------------------

#### ####📊 检测报告示例（普通ubuntu环境自检）
📊 报告样例
系统检测报告 2025-03-02 17:16

[硬件信息]
CPU: AMD Ryzen 9 5950X 16-Core Processor
内存: 31Gi
GPU: NVIDIA GeForce RTX 2080 Ti

[系统信息]
操作系统: Ubuntu 22.04.1 LTS
内核版本: 5.15.167.4-microsoft-standard-WSL2

[运行环境]
Python 3.12.9
PyTorch: 2.5.1
----------------------------------------------------------------------------------------------------------------------------------

