# SearchGPT-Explorer

SearchGPT-Explorer 是一个将搜索 API 功能与大型语言模型集成的项目，实现了类似 New Bing 的实时网络信息访问能力。该项目使普通的 GPT 模型能够执行最新信息检索和智能问答。

## 特性

- 无缝集成搜索 API 和 GPT 模型
- 实时网络信息检索
- 动态函数调用，实现灵活的搜索操作
- 错误处理和稳健的 API 交互
- 易用的接口，增强 AI 对话能力

## 快速开始

### 前提条件

- Python 3.7+
- OpenAI API 密钥
- DuckDuckGo 搜索 API（无需密钥）

### 安装

1. 克隆仓库：
   ```
   git clone https://github.com/yourusername/SearchGPT-Explorer.git
   ```

2. 安装所需包：
   ```
   pip install -r requirements.txt
   ```

3. 设置 OpenAI API 密钥为环境变量：
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

### 使用

运行主脚本：

```
python search_gpt_core.py
```

## 贡献

欢迎贡献！请随时提交 Pull Request。

## 许可证

该项目采用 MIT 许可证 - 详情请见 [LICENSE](LICENSE) 文件。
