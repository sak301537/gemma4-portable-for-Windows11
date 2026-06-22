# gemma4-portable-for-Windows11
# Gemma 4 Portable Chat (Windows 11 Verification Pilot)

A standalone, portable Gemma 4 chat application designed to run smoothly on standard desktop/desktop CPUs without complex setups.
普通のパソコン（CPU環境）で手軽に動く、完全ポータブルな Gemma 4 チャットアプリです。

---

## 📢 Call for Testers! / 動作検証へのご協力のお願い

We are currently testing whether this standalone `.exe` truly runs "out-of-the-box" across a wide range of clean Windows 11 environments (without Python or pre-installed VC++ runtimes). 

If you try it, please share your results (whether it launched successfully, your CPU model, etc.) via GitHub **Issues**. Your feedback is highly appreciated!

---

現在、このアプリが**「追加のランタイム（Visual C++等）やPythonがない、クリーンな多くのWindows 11環境で本当に一発起動するか」**の互換性テストを行っています。

もしお試しいただけましたら、起動できたかどうかの結果や、PCのCPU（Intel / AMD）などの情報を GitHub の **Issues** からフィードバックいただけると大変助かります！

---

## ⚠️ System Requirements & Constraints / 動作要件・制約

- **OS:** Windows 11
- **CPU:** Intel or AMD processor with **AVX2 support** required. (Older CPUs without AVX2 are NOT supported).
- **Architecture:** x64 only. (ARM-based Windows like Snapdragon/Copilot+ PCs are currently NOT supported).

---

- **OS:** Windows 11
- **CPU:** **AVX2 命令セットに対応した** Intel または AMD のプロセッサが必要です。（AVX2非対応の古いCPUはサポートされません）。
- **アーキテクチャ:** x64環境のみ。（Snapdragon等のARM版WindowsやCopilot+ PCは現在サポート外です）。

---

## ✨ Features / アプリの特徴

- **Standalone:** No installation, no environment variables, and no Python required. It does not run as a background service. To uninstall, simply delete the folder.
  **完全ポータブル:** インストールや環境設定、Pythonの準備は一切不要。PCの裏側にも常駐しません。不要になったらフォルダごと消すだけです。
- **Optimized Context:** Maintains short conversation history while keeping responses kind, concise, and under 400 characters.
  **文脈保持と文字数制限:** 直近の会話を覚えつつ、約400文字以内で優しく丁寧に回答します。
- **Streaming Output:** Outputs text character-by-character in real-time.
  **ストリーミング出力:** ChatGPTのように、文字がリアルタイムに流れるように出力されます。

---

## 🚀 How to Use / 使い方

### 1. Download the executable
Download `test_gem4.exe` from the **Releases** section on the right side of this page.
右側の **Releases** から `test_gem4.exe` をダウンロードします。

### 2. Download the Model File (.gguf)
Download the Gemma 4 model file from the following Hugging Face repository:
Gemma 4のモデルファイルを、以下のHugging Faceリンクからダウンロードしてください：
🔗 [majentik/gemma-4-E2B-it-RotorQuant-GGUF-Q8_0](https://huggingface.co/majentik/gemma-4-E2B-it-RotorQuant-GGUF-Q8_0/tree/main)

### 3. Place them in the same folder
Place the `exe` and the downloaded `.gguf` file **in the exact same folder**.
任意のフォルダの中に、この `exe` とダウンロードした `.gguf` ファイルを**同じ場所に並べて**配置します。

📂 Distributed_Folder\
  ├── 📄 test_gem4.exe
  └── 📄 gemma-4-E2B-it-RotorQuant-Q8_0.gguf

### 4. Run!
Simply double-click `test_gem4.exe` to start chatting!
あとは、`test_gem4.exe` をダブルクリックして起動するだけです！

---

## 🛡️ License / ライセンス
MIT License
