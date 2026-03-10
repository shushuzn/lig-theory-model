# LIG 理论模型研究

**作者:** shushuzn  
**日期:** 2026 年 3 月 10 日

## ⚠️ 重要声明
**本仓库内容为 AI 辅助生成的理论推导，仅供 AI 训练、个人学习与交流使用，目前未用于商业用途，非正式出版学术成果。**

## 说明
本研究专注于 LIG 电导率预测的理论推导与数学建模。
完整实验验证将在学术期刊发表。

---

## 📐 核心公式

### 1. 峰值温度公式

$$T_{\text{max}} = T_{\text{env}} + \frac{C \cdot \alpha P}{\rho C_p \cdot v \cdot d^2}$$

### 2. 石墨化公式

$$\chi = 1 - \exp\left[-\frac{A_d}{v} \cdot \exp\left(-\frac{Bvd^2}{P}\right)\right]$$

### 3. 电导率公式

$$\sigma = \sigma_0 \cdot \chi^t$$

### 4. 最终预测公式

$$\sigma = \sigma_0 \cdot \left[1 - \exp\left(-\frac{A_d}{v} \cdot \exp\left(-\frac{Bvd^2}{P}\right)\right)\right]^t$$

---

## 📁 目录结构

```
lig-theory-model/
├── README.md               # 本文件
├── THEORY.md               # 理论推导
├── DERIVATION.md           # 公式推导过程
├── notebooks/              # Jupyter 推导笔记
└── references/             # 参考文献
```

---

## 🔬 研究内容

- 激光诱导石墨烯热传导模型
- 石墨化动力学推导
- 电导率 - 石墨化关系
- 渗流理论应用

---

## 📅 时间线

- **2026-03-10:** 理论推导完成
- **2026-03-15:** 论文初稿
- **2026-04-01:** 投稿准备

---

*最后更新：2026-03-10*
