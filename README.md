# DenseNet on CIFAR-10

## 專案說明 (Description)
本專案使用 **DenseNet** 架構，透過 Keras 與 PyTorch 後端來實作深度學習模型，並以 CIFAR-10 資料集進行訓練與測試。

This project implements the **DenseNet** architecture using Keras with a PyTorch backend. The model is trained and tested on the CIFAR-10 dataset.

---

## 核心概念 (Core Concepts)

- 使用 Keras 的 `subclassing API` 建立模型。
- 熟悉 DenseNet 模型的構建與訓練流程。
- 學習如何處理 CIFAR-10 資料集。

- Building models using Keras's `subclassing API`.
- Understanding the structure and training process of DenseNet.
- Working effectively with the CIFAR-10 dataset.

---

## 資料集 (Dataset)

CIFAR-10 資料集包含10個類別，每個類別有6000張32x32像素的彩色圖片，共60000張圖片。

CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes, with 6,000 images per class.

- 官方網站 (Official site)：[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)

---

## 環境需求 (Requirements)

- Keras
- PyTorch
- CUDA (可選, Optional for GPU acceleration)



---

## 結果與分析 (Results & Analysis)

在訓練後可透過 accuracy 和 loss 觀察模型效能，進一步調整超參數以提升準確率。

You can observe the model's performance through accuracy and loss metrics, and further tune hyperparameters for improved accuracy.

---

## 貢獻者 (Contributor)

歡迎提供建議與改進！

Suggestions and improvements are always welcome!

