<h1 align="center">RainmeoX</h1>

<p align="center">
  <b>电子信息科学与技术 · 在读本科生</b><br/>
  把嵌入式硬件能力 × AI 模型应用，做成能跑、能复现的工程
</p>

---

## 当前主线

| 方向 | 进展 |
| --- | --- |
| **AMD ROCm Hackathon · 本地私有硬件 Agent** | [`Radeon-hackathon-2026-07`](https://github.com/RainmeoX/Radeon-hackathon-2026-07)（Radeon-Assistant「磐石」）· Track 2，运行于 **AMD Radeon Pro W7900（ROCm）** |
| 角色助手全链路 | 数据集 → LoRA 微调 → vLLM 部署 → WebUI |

## 能力矩阵

| 方向 | 技术 / 代表项目 |
| --- | --- |
| AI 大模型与 Agent（AMD ROCm） | LoRA / vLLM / RAG / Agent；Radeon-Assistant「磐石」本地私有 AI Agent（硬件研发特化）、zzz-yixuan 角色助手（★2） |
| 嵌入式视觉（硬件） | K230 AI 芯片：图形 / 二维码检测 + UART 串口 |
| Web 全栈与工程 | Flask（canteen-order-system）、微信小程序、原生前端（zzz-yixuan-webui）、个人网站（anime-site） |
| 数据集 / 安全 / 工具 | arknights-dataset（22k+ 问答对）、Web-Security-Learning、avgforge |

## 重点项目

**AI Agent / 大模型（AMD ROCm）**
- [`Radeon-hackathon-2026-07`](https://github.com/RainmeoX/Radeon-hackathon-2026-07) — Radeon-Assistant「磐石」，**本地私有 AI Agent**，运行于 AMD ROCm，特化**硬件研发**（Verilog / Testbench 生成、芯片手册 PDF 解析）（Track 2）
- [`zzz-yixuan-assistant`](https://github.com/RainmeoX/zzz-yixuan-assistant) — Qwen3-4B + LoRA + vLLM + RAG 角色助手，部署于 **AMD GPU（ROCm）**（★2，链路最完整）
- [`gemma4-emotion-lora-rocm`](https://github.com/RainmeoX/gemma4-emotion-lora-rocm) — Gemma4 LoRA 情绪分类，于 **AMD ROCm 单卡**训练，准确率 0.625 → 0.915
- [`arknights-qwen-assistant`](https://github.com/RainmeoX/arknights-qwen-assistant) — Qwen3-0.6B 干员问答，**AMD ROCm 单卡**训练

**嵌入式 / 硬件视觉**
- [`K230-Vision-System`](https://github.com/RainmeoX/K230-Vision-System) — **K230 AI 芯片**视觉检测 + 串口通信（硬件落地）
- [`canteen-order-system`](https://github.com/RainmeoX/canteen-order-system) — Flask 三层架构食堂预订系统
- [`wechat-mini-program`](https://github.com/RainmeoX/wechat-mini-program) — 乡村政务微信小程序

**数据 / 工具**
- [`arknights-dataset`](https://github.com/RainmeoX/arknights-dataset) — 干员微调数据集（22k+ 问答对）
- [`zzz-yixuan-dataset`](https://github.com/RainmeoX/zzz-yixuan-dataset) — 角色资料数据集（多源爬取）
- [`avgforge`](https://github.com/RainmeoX/avgforge) — 视觉小说创作管线实验
- [`Web-Security-Learning`](https://github.com/RainmeoX/Web-Security-Learning) — 网络安全学习笔记

## 技术栈

<p>
  <img src="https://img.shields.io/badge/Python-9ca3af?style=flat" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-9ca3af?style=flat" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/AMD%20ROCm-9ca3af?style=flat" alt="ROCm"/>
  <img src="https://img.shields.io/badge/vLLM-9ca3af?style=flat" alt="vLLM"/>
  <img src="https://img.shields.io/badge/LoRA-9ca3af?style=flat" alt="LoRA"/>
  <img src="https://img.shields.io/badge/RAG-9ca3af?style=flat" alt="RAG"/>
  <img src="https://img.shields.io/badge/K230-9ca3af?style=flat" alt="K230"/>
  <img src="https://img.shields.io/badge/Flask-9ca3af?style=flat" alt="Flask"/>
  <img src="https://img.shields.io/badge/C%2F C%2B%2B-9ca3af?style=flat" alt="C/C++"/>
</p>

## 链接

- 个人网站：https://www.rainmeo.xyz
- CSDN 博客：https://blog.csdn.net/m0_67166125

## 说明

项目多为边学边做的学习 / 实验性质，部分已落地到具体场景（如本地私有 AI Agent 的硬件研发特化）。方向选择、架构设计、调试与部署由我本人完成；部分代码有 AI 辅助。仓库以真实工程记录为主，欢迎在 Issues 交流。
