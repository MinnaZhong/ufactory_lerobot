# uFactory LeRobot

uFactory 机械臂与 LeRobot 框架集成项目，用于机器人学习、数据采集和策略部署。

## 功能特性

- 🤖 uFactory 机械臂控制接口
- 📷 多摄像头数据采集
- 🧠 模仿学习（行为克隆、ACT、扩散策略等）
- 🚀 策略部署与实时推理
- 📊 训练过程可视化和日志记录

## 环境要求

- Python >= 3.10
- CUDA >= 12.0（GPU 训练推荐）
- uFactory 机械臂（xArm 系列）

## 安装

```bash
# 克隆仓库
git clone <repo-url>
cd ufactory_lerobot

# 创建虚拟环境
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# .venv\Scripts\activate   # Windows

# 安装依赖
pip install -e ".[dev]"
```

## 快速开始

```python
# TODO: 添加示例代码
```

## 项目结构

```
ufactory_lerobot/
├── src/            # 源代码
├── configs/        # 配置文件
├── scripts/        # 脚本
├── tests/          # 测试
└── docs/           # 文档
```

## 许可证

本项目基于 MIT 许可证发布。详见 [LICENSE](LICENSE) 文件。
