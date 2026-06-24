# Kinako Project Gemma4
# Gemma 4 Portable Chat (Windows 11 Verification Pilot)

A standalone, portable Gemma 4 chat application designed to run smoothly on standard desktop/desktop CPUs without complex setups.
普通のパソコン（CPU環境）で手軽に動く、完全ポータブルな Gemma 4 チャットアプリです。

---

## ⚠️ System Requirements & Constraints / 動作要件・制約

[English]
* OS: Windows 11 (x64)
* CPU: Intel 4th Generation (Haswell, 2013) or later / AMD Ryzen series or later.
  * Note: Very old CPUs (released over 10 years ago) are not supported. ARM-based PCs (e.g., Snapdragon, Copilot+) are currently not supported.

[日本語]
* OS: Windows 11 (x64環境のみ)
* CPU: Intel 第4世代 以降、または AMD Ryzen シリーズ以降であれば動作します。
  * ※今から10年以上前の極端に古いPC（Core iシリーズの3ケタ・2ケタ型番など）は動きません。また、Snapdragon等のARM版Windows（Copilot+ PC）は現在サポート外です。

---

## ✨ Features / アプリの特徴

- **Standalone:** No installation, no environment variables, and no Python required. It does not run as a background service. To uninstall, simply delete the folder.
- **Optimized Context:** Maintains short conversation history while keeping responses kind, concise, and under 400 characters.
- **Streaming Output:** Outputs text character-by-character in real-time.

  **完全ポータブル:** インストールや環境設定、Pythonの準備は一切不要。PCの裏側にも常駐しません。不要になったらフォルダごと消すだけです。
  **文脈保持と文字数制限:** 過去の会話をあらすじで覚えつつ、約400文字以内で優しく丁寧に回答します。
  **ストリーミング出力:** 文字が流れるように出力されるので待たせません。
---

## 🚀 How to Use / 使い方

### 1. Download the executable
Download `kinako_gem4_en.exe(English)` from the **Releases** section on the right side of this page.
右側の **Releases** から `kinako_gem4_jp.exe（日本語）` をダウンロードします。

### 2. Download the Model File (.gguf)
Download the Gemma 4 model file from the following Hugging Face repository:
Gemma 4のモデルファイルを、以下のHugging Faceリンクからダウンロードしてください：
🔗 [majentik/gemma-4-E2B-it-RotorQuant-GGUF-Q8_0](https://huggingface.co/majentik/gemma-4-E2B-it-RotorQuant-GGUF-Q8_0/blob/main/gemma-4-E2B-it-RotorQuant-Q8_0.gguf)

### 3. Place them in the same folder
Place the `exe` and the downloaded `.gguf` file **in the exact same folder**.
任意のフォルダの中に、この `exe` とダウンロードした `.gguf` ファイルを**同じ場所に並べて**配置します。

📂 Distributed_Folder\
  ├── 📄 kinako_gem4_en.exe or kinako_gem4_jp.exe  
  └── 📄 gemma-4-E2B-it-RotorQuant-Q8_0.gguf

### 4. Run!
Simply double-click `test_gem4.exe` to start chatting!
あとは、`test_gem4.exe` をダブルクリックして起動するだけです！

---

## 🛡️ License / ライセンス
MIT License
