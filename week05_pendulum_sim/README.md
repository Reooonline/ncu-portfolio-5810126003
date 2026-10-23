# Week 05 - Chaotic Double Pendulum

## 实验信息
- 实验者：付启昊
- 学号：5810126003
- 专业：给排水科学与工程
- 实验主题：双摆混沌仿真实验（Double Pendulum Chaos Simulation）

## 状态说明
- 工作区：已就绪
- 数值积分：Runge-Kutta 4 阶（RK4）
- 交互方式：支持鼠标拖拽摆球并释放
- 视觉效果：第二摆球采用半透明彩虹拖尾

## 运行方式
1. 打开 `index.html` 文件；
2. 或在当前目录中启动本地静态服务器：
   ```bash
   python -m http.server 8000
   ```
3. 浏览器访问 `http://localhost:8000`。

## 实验目标
- 观察双摆系统的非线性运动与混沌特性；
- 验证 RK4 对拉格朗日方程的稳定求解；
- 研究拖拽初始条件对系统演化的影响。
