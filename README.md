# 英文小说阅读辅助软件 (English Novel Reading Assistant)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.7+-blue.svg)

一个基于AI的英文小说阅读辅助工具，帮助中文用户更好地理解和学习英文小说。

## 功能特性 ✨

- 📖 **智能文本分析**: 使用AI模型深度分析英文段落，提供详细的语言解释
- 🎯 **难度评估**: 自动评估文本难度，适合不同英语水平的读者
- 📚 **词汇管理**: 内置词汇数据库，追踪学习进度和单词熟练度
- 📊 **学习统计**: 记录阅读时间、学习单词数等统计信息
- 📄 **导出功能**: 将分析结果导出为Word文档，便于复习
- 🌐 **Web界面**: 基于Gradio的友好用户界面
- 🤖 **多模型支持**: 支持不同的AI模型进行文本分析

## 技术栈 🛠️

- **Python 3.7+**
- **Gradio** - Web界面框架
- **NLTK** - 自然语言处理
- **SQLite** - 本地数据库
- **python-docx** - Word文档生成
- **Ollama** - AI模型接口

## 安装说明 📦

### 1. 克隆项目
```bash
git clone https://github.com/wallfacer-web/novel_reader_for-Chinese.git
cd novel_reader_for-Chinese
```

### 2. 安装依赖
```bash
pip install -r requirements.txt
```

### 3. 安装Ollama（可选）
如果要使用本地AI模型，请安装[Ollama](https://ollama.ai/)：
```bash
# 下载并安装模型
ollama pull qwen:latest
```

## 使用方法 🚀

### 启动应用
```bash
python "novel_reader_for Chinese.py"
```

### 功能说明
1. **上传小说文件**: 支持txt格式的英文小说
2. **选择分析模式**: 详细分析或简化分析
3. **逐段阅读**: 逐段分析小说内容，提供详细解释
4. **词汇学习**: 自动提取生词并加入学习数据库
5. **导出报告**: 将分析结果导出为Word文档

## 项目结构 📁

```
novel_reader_for-Chinese/
├── novel_reader_for Chinese.py    # 主程序文件
├── vocabulary.db                  # 词汇数据库（自动生成）
├── requirements.txt              # 项目依赖
├── README.md                     # 项目说明
├── LICENSE                       # 开源许可证
└── .gitignore                   # Git忽略文件
```

## 主要类说明 📋

- **VocabularyDatabase**: 词汇数据库管理
- **TextDifficultyAnalyzer**: 文本难度分析器
- **EnhancedNovelReader**: 增强型小说阅读器
- **EnhancedGradioInterface**: Gradio用户界面

## 贡献指南 🤝

欢迎提交Issue和Pull Request来改进这个项目！

## 许可证 📜

本项目采用MIT许可证 - 查看[LICENSE](LICENSE)文件了解详情

## 作者信息 👨‍💻

**Toby LUO@ZHKU**  
📧 Email: 903098625@qq.com

---

© 2024 Toby LUO@ZHKU (903098625@qq.com). All rights reserved. 