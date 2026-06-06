# 🎤 AI Speech

AI语音工具，支持语音识别、语音合成、语音分析。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🎙️ 语音识别系统设计
- 🔊 语音合成系统设计
- 🤖 语音助手设计
- 🎵 音频分析
- 📊 语音数据集方案
- ⚖️ 语音模型比较

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_speech import create_tools

tools = create_tools()

# 语音识别系统
stt = tools.design_stt_system("实时转录，中文")

# 语音合成系统
tts = tools.design_tts_system("女声", "中文")

# 语音助手
assistant = tools.generate_voice_assistant("Sans", ["对话", "工具调用"])

# 音频分析
analysis = tools.analyze_audio(audio_description)

# 数据集方案
dataset = tools.generate_speech_dataset(requirements)

# 模型比较
comparison = tools.compare_speech_models("语音识别")
```

## 📁 项目结构

```
ai-speech/
├── tools.py       # 语音工具核心
└── README.md
```

## 📄 许可证

MIT License
