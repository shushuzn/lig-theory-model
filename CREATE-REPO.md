# 创建 GitHub 仓库指南

**仓库名称:** lig-theory-model  
**描述:** LIG 电导率预测理论模型研究

---

## 🚀 创建步骤

### 步骤 1: 创建 GitHub 仓库

1. 访问：https://github.com/new
2. 填写信息:
   - **Repository name:** `lig-theory-model`
   - **Description:** LIG Conductivity Prediction - Theoretical Model
   - **Visibility:** Public (推荐) 或 Private
   - **Initialize:** ❌ 不要勾选 (我们已有本地代码)
3. 点击 **Create repository**

---

### 步骤 2: 推送本地代码

仓库创建后，执行：

```bash
cd D:\OpenClaw\workspace\11-research\lig-theory-model
git remote add origin https://github.com/shushuzn/lig-theory-model.git
git branch -M main
git push -u origin main
```

---

### 步骤 3: 添加 Zenodo DOI (可选)

参考：`../lig-conductivity-prediction-zenodo/ZENODO-DOI-GUIDE.md`

---

## 📋 仓库结构

```
lig-theory-model/
├── README.md          # ✅ 已创建
├── THEORY.md          # ✅ 已创建
├── DERIVATION.md      # 待创建
├── notebooks/         # 待创建
└── references/        # 待创建
```

---

## 🔗 相关仓库

- **lig-conductivity-prediction:** 实验数据 + ML 模型
- **lig-theory-model:** 理论推导 + 数学建模 (新)

---

*创建日期：2026-03-10*
