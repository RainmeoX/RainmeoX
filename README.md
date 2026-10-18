<h1 align="center">RainmeoX</h1>

<p align="center">
  <b>电子信息科学与技术 · 在读本科生</b><br/>

  把嵌入式硬件能力 × AI 模型应用，做成能跑、能复现的工程
</p>

---

## 当前主线

| 方向                               | 进展                                                                              |
| -------------------------------- | ------------------------------------------------------------------------------- |
| **智能插排 · STM32 + ESP8266**（私有仓库） | 驱动 / 通信 / 上云全链路，OneNET 接入进行中                                                    |
| **珠科百事通 · 校园 RAG 问答平台**          | [`zhike-baishitong`](https://github.com/RainmeoX/zhike-baishitong)，面向全校师生，软著申请中 |

## 能力矩阵

| 方向                      | 技术 / 代表项目                                                           |
| ----------------------- | ------------------------------------------------------------------- |
| 嵌入式 / 物联网硬件             | STM32（HAL）、ESP8266（AT / 透传 / MQTT）、Keil + VSCode/GCC；K230 小车视觉 + UART |
| 网络安全                    | Web 安全（SQL 注入 / XSS）、应急响应（内存取证 / ATT\&CK 映射）、Volatility3 / YARA      |
| AI 大模型与 Agent（AMD ROCm） | LoRA / vLLM / RAG / Agent                                           |
| Web 全栈与工程               | Flask、微信小程序、原生前端、个人网站（anime-site）                                   |
| 数据集 / 工具                | arknights-dataset、avgforge                                          |

## 重点项目

**嵌入式 / 硬件**

- **智能插排**（STM32F103C8T6 + ESP-01S，私有仓库）— ESP8266 驱动（AT 指令 / `+IPD` 解析 / 透传 / MQTT），OneNET 物模型上云进行中
- [`K230-Vision-System`](https://github.com/RainmeoX/K230-Vision-System) — K230 AI 芯片小车视觉检测 + 串口通信

**网络安全**

- [`Web-Security-Learning`](https://github.com/RainmeoX/Web-Security-Learning) — Web 安全与应急响应学习笔记（SQL 注入 / XSS / 内存取证 / ATT\&CK 映射等实战脚本）

**AI / 大模型（AMD ROCm）**

- [`zhike-baishitong`](https://github.com/RainmeoX/zhike-baishitong) — 珠科百事通：校园 RAG 问答平台，答案带官方出处
- [`zzz-yixuan-assistant`](https://github.com/RainmeoX/zzz-yixuan-assistant) — Qwen3-4B + LoRA + vLLM + RAG 角色助手，AMD GPU 单卡部署
- [`gemma4-emotion-lora-rocm`](https://github.com/RainmeoX/gemma4-emotion-lora-rocm) — Gemma4 情绪分类微调，准确率 0.625 → 0.915
- [`arknights-qwen-assistant`](https://github.com/RainmeoX/arknights-qwen-assistant) — Qwen3-0.6B 干员问答，单卡训练

**其他项目**

- [`canteen-order-system`](https://github.com/RainmeoX/canteen-order-system) — Flask 食堂预订系统
- [`wechat-mini-program`](https://github.com/RainmeoX/wechat-mini-program) — 乡村政务微信小程序
- [`arknights-dataset`](https://github.com/RainmeoX/arknights-dataset) — 干员微调数据集
- [`zzz-yixuan-dataset`](https://github.com/RainmeoX/zzz-yixuan-dataset) — 角色资料数据集（多源爬取）
- [`avgforge`](https://github.com/RainmeoX/avgforge) — 视觉小说创作管线实验

## 技术栈

<p>
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-9ca3af?style=flat" alt="C/C++"/>
  <img src="https://img.shields.io/badge/STM32-9ca3af?style=flat" alt="STM32"/>
  <img src="https://img.shields.io/badge/ESP8266-9ca3af?style=flat" alt="ESP8266"/>
  <img src="https://img.shields.io/badge/K230-9ca3af?style=flat" alt="K230"/>
  <img src="https://img.shields.io/badge/Python-9ca3af?style=flat" alt="Python"/>
  <img src="https://img.shields.io/badge/AMD%20ROCm-9ca3af?style=flat" alt="ROCm"/>
  <img src="https://img.shields.io/badge/vLLM-9ca3af?style=flat" alt="vLLM"/>
  <img src="https://img.shields.io/badge/LoRA-9ca3af?style=flat" alt="LoRA"/>
  <img src="https://img.shields.io/badge/RAG-9ca3af?style=flat" alt="RAG"/>
  <img src="https://img.shields.io/badge/Volatility3-9ca3af?style=flat" alt="Volatility3"/>
  <img src="https://img.shields.io/badge/Flask-9ca3af?style=flat" alt="Flask"/>
</p>

## 链接

- 个人网站：<https://www.rainmeo.xyz>
- CSDN 博客：<https://blog.csdn.net/m0_67166125>

## 说明

仓库以真实工程记录为主，欢迎在 Issues 交流。
