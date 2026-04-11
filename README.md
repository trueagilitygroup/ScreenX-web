# ScreenX HD Web Research Recorder | ScreenX 高畫質網頁版研究錄影工具

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight, single-file web application designed for high-definition screen capture research. This tool utilizes the native browser **Screen Capture API** to explore media encoding and DRM (Digital Rights Management) enforcement within web environments.

這是一個輕量化、單一檔案的網頁應用程式，專為高畫質螢幕擷取研究而設計。本工具利用瀏覽器原生的 **Screen Capture API**，探索網頁環境中的媒體編碼與 DRM（數位內容權利管理）強制執行機制。

---

## ✨ Features | 功能特點

* **Zero Installation:** Runs directly in any modern web browser (Chrome, Edge, Firefox).
* **High Definition:** Optimized for 1080p/60FPS recording using the VP9/H.264 browser codecs.
* **Bilingual UI:** Instant switching between **English** and **Traditional Chinese (zh-TW)**.
* **Privacy-First:** All processing happens locally in the browser; no data is sent to a server.
* **免安裝:** 直接在現代瀏覽器中執行（Chrome, Edge, Firefox）。
* **高畫質:** 優化 1080p/60FPS 錄製，使用 VP9/H.264 瀏覽器編解碼器。
* **雙語介面:** 支援 **英文** 與 **繁體中文 (台灣)** 立即切換。
* **隱私至上:** 所有處理均在瀏覽器本地完成，不傳送任何資料至伺服器。

---

## 🔬 Research Context: DRM in the Browser
## 🔬 研究背景：瀏覽器中的 DRM 機制

This tool is a primary instrument for documenting **Encrypted Media Extensions (EME)**. 

When capturing the screen via a browser, platforms like **Netflix**, **Hulu**, or **Prime Video** will trigger a "Black Screen" overlay. This is a security feature where the browser prevents the `getDisplayMedia` API from accessing the decrypted video memory. This project allows researchers to analyze this security boundary.

本工具是記錄 **加密媒體擴充功能 (EME)** 的主要工具。當透過瀏覽器擷取螢幕時，Netflix 或 Prime Video 等平台會觸發「黑屏」覆蓋。這是瀏覽器防止 `getDisplayMedia` API 存取已解密視訊記憶體的安全功能。本專案允許研究人員分析此安全邊界。

---

## 🛠 Technical Details | 技術細節

* API: navigator.mediaDevices.getDisplayMedia
* Recording: MediaRecorder API
* Container: .webm (Standard for web-based recording)
* Resolution: Ideal 1920x1080 @ 60fps

---

## ⚖️ Disclaimer | 免責聲明

This tool is for educational and research purposes only. It does not bypass or circumvent any digital protections. Users are responsible for adhering to the copyright laws of their respective jurisdictions.

本工具僅供 教育與研究用途。它不會破解或規避任何數位保護機制。使用者有責任遵守其所在地之著作權法。

---

## 👤 Author | 作者

Davidian Chen (陳建璋)
* Assistant Professor, Chinese Culture University
