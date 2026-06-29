# 中文 LLM API 入口地图

![preview](assets/preview.png)

做 LLM 应用最烦的不是写第一行代码，而是控制台、文档、模型名、价格、额度、地区限制全都散在不同地方。这个仓库就是一张入口地图，少讲概念，多给能点开的地方。

API 平台不要只看模型分数。真正做项目时，账单、限流、日志、地区和 key 管理经常比榜单名次更早把人卡死。

## 先看这几个

OpenAI Platform / Anthropic Console / Google AI Studio / DeepSeek Platform

先把 OpenAI、Anthropic、Gemini、DeepSeek 和一个聚合平台的控制台都打开看一遍。

## 入口

| 名称 | 我为什么留它 |
| --- | --- |
| [OpenAI Platform](https://platform.openai.com/docs/overview) | OpenAI API 文档和控制台入口。 |
| [Anthropic Console](https://console.anthropic.com/) | Claude API 控制台入口。 |
| [Google AI Studio](https://aistudio.google.com/) | Gemini API 原型和 key 管理入口。 |
| [DeepSeek Platform](https://platform.deepseek.com/) | DeepSeek API 平台入口。 |
| [阿里云百炼 DashScope](https://bailian.console.aliyun.com/) | 通义千问等模型调用与应用开发平台。 |
| [OpenRouter](https://openrouter.ai/) | 多模型聚合平台，适合快速切换 provider。 |
| [Hugging Face Models](https://huggingface.co/models) | 模型权重、demo、社区模型搜索入口。 |
| [Replicate](https://replicate.com/) | 托管模型 API 和 demo 平台。 |

## 我的使用顺序

- 先确定模型用途：文本、代码、视觉、语音或 embedding。
- 把控制台、定价页、API 文档一起收藏。
- 先写最小 demo，再接入生产。

## 别踩坑

- 不要忽视地区、支付方式、速率限制。
- 聚合平台方便，但生产场景要评估稳定性和隐私。

## 截图来源

这张图来自公开页面：[https://openrouter.ai/](https://openrouter.ai/)。如果页面改版，截图可能会和当前官网略有出入。

## 维护方式

链接数据放在 [`data/links.json`](data/links.json)。我倾向于少而准：入口失效就换，说明过时就改，不把这里做成什么都往里塞的大杂烩。

## License

MIT. 第三方商标、页面截图和网站内容归原权利方所有；本仓库只做中文导航和使用笔记。
