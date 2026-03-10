# LIG 理论推导

**作者:** shushuzn  
**日期:** 2026 年 3 月 10 日

---

## 峰值温度公式推导

### 热传导方程

$$\rho C_p \frac{\partial T}{\partial t} = k \nabla^2 T + Q$$

### 热源项

$$Q = \alpha I = \alpha \frac{P}{\pi (d/2)^2}$$

### 稳态解

$$T_{\text{max}} = T_{\text{env}} + \frac{C \cdot \alpha P}{\rho C_p \cdot v \cdot d^2}$$

---

## 石墨化动力学

### Arrhenius 方程

$$\frac{d\chi}{dt} = A \exp\left(-\frac{E_a}{RT}\right)(1-\chi)$$

### 积分形式

$$\chi = 1 - \exp\left[-\frac{A_d}{v} \cdot \exp\left(-\frac{Bvd^2}{P}\right)\right]$$

---

## 电导率模型

### 渗流理论

$$\sigma = \sigma_0 \cdot (\chi - \chi_c)^t$$

### 简化形式

$$\sigma = \sigma_0 \cdot \chi^t$$

---

## 最终预测公式

$$\sigma = \sigma_0 \cdot \left[1 - \exp\left(-\frac{A_d}{v} \cdot \exp\left(-\frac{Bvd^2}{P}\right)\right)\right]^t$$

---

*最后更新：2026-03-10*
