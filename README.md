# ai-detector
西语ai率简易检测器
# AI 文本检测器 (ai-detector)

一个简易的 AI 生成文本检测工具，支持中、英、西语。

## 🔗 在线使用地址
**[点此打开网页版检测器](https://ai-detector-hfy5g25tinawuqkfg5gibq.streamlit.app)** 

（在 GitHub 里点开链接可以直接跳转，或者直接复制到浏览器打开）

## 📖 功能介绍
- 粘贴一段文字，自动判断是 AI 生成还是人类书写
- 基于数学统计算法（句子波动性 + 词汇多样性），不依赖模型下载，速度快
- 支持多语言输入

## 🛠️ 技术栈
- Python + Streamlit
- 核心算法：Burstiness (突发性) + Lexical Diversity (词汇多样性)
