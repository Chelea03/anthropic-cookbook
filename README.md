# Anthropic Cookbook

Anthropic Cookbook 提供了代码和指南，旨在帮助开发人员使用 Claude 进行构建，其中包含可复制的代码片段，您可以轻松地将其集成到自己的项目中。

## 先决条件

要充分利用本 Cookbook 中的示例，您需要一个 Anthropic API 密钥（[在此处免费注册](https://www.anthropic.com)）。

虽然代码示例主要用 Python 编写，但这些概念可以适用于任何支持与 Anthropic API 交互的编程语言。

如果您是 Anthropic API 的新手，我们建议您从我们的 Anthropic API 基础课程开始，以打下坚实的基础。

## 进一步探索

正在寻找更多资源来增强您使用 Claude 和 AI 助手的体验？请查看以下有用的链接：

- [Anthropic 开发人员文档](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources)
- [Anthropic 支持文档](https://support.anthropic.com)
- [Anthropic Discord 社区](https://www.anthropic.com/discord)

## 贡献

Anthropic Cookbook 依靠开发人员社区的贡献而蓬勃发展。我们重视您的投入，无论是提交想法、修复拼写错误、添加新指南还是改进现有指南。通过贡献，您帮助使这个资源对每个人都更有价值。

为避免重复工作，请在贡献之前查看现有的问题和拉取请求。

如果您有新示例或指南的想法，请在[问题页面](https://github.com/anthropics/anthropic-cookbook/issues)上分享。

## 食谱目录

### 技能

- [分类](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/classification)：探索使用 Claude 进行文本和数据分类的技术。
- [检索增强生成](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/retrieval_augmented_generation)：了解如何使用外部知识增强 Claude 的响应。
- [摘要](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/summarization)：发现使用 Claude 进行有效文本摘要的技术。

### 工具使用和集成

- [工具使用](https://github.com/anthropics/anthropic-cookbook/tree/main/tool_use)：了解如何将 Claude 与外部工具和函数集成，以扩展其功能。
  - [客户服务代理](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/customer_service_agent.ipynb)
  - [计算器集成](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/calculator_tool.ipynb)
  - [SQL 查询](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_make_sql_queries.ipynb)

### 第三方集成

- [检索增强生成](https://github.com/anthropics/anthropic-cookbook/tree/main/third_party)：使用外部数据源补充 Claude 的知识。
  - [向量数据库 (Pinecone)](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Pinecone/rag_using_pinecone.ipynb)
  - [维基百科](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Wikipedia/wikipedia-search-cookbook.ipynb/)
  - [网页](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/read_web_pages_with_haiku.ipynb)
  - [互联网搜索 (Brave)](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Brave/web_search_using_brave.ipynb)
- [使用 Voyage AI 进行嵌入](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/VoyageAI/how_to_create_embeddings.md)

### 多模态能力

- [Claude 的视觉能力](https://github.com/anthropics/anthropic-cookbook/tree/main/multimodal)：
  - [图像入门](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/getting_started_with_vision.ipynb)
  - [视觉最佳实践](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb)
  - [解释图表和图形](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/reading_charts_graphs_powerpoints.ipynb)
  - [从表单中提取内容](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/how_to_transcribe_text.ipynb)
- [使用 Claude 生成图像](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/illustrated_responses.ipynb)：将 Claude 与 Stable Diffusion 结合使用以生成图像。

### 高级技术

- [子代理](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/using_sub_agents.ipynb)：了解如何将 Haiku 作为子代理与 Opus 结合使用。
- [将 PDF 上传到 Claude](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/pdf_upload_summarization.ipynb)：解析 PDF 并将其作为文本传递给 Claude。
- [自动化评估](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_evals.ipynb)：使用 Claude 自动化提示评估过程。
- [启用 JSON 模式](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_enable_json_mode.ipynb)：确保 Claude 输出一致的 JSON 格式。
- [创建审核过滤器](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_moderation_filter.ipynb)：使用 Claude 为您的应用程序创建内容审核过滤器。
- [提示缓存](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/prompt_caching.ipynb)：学习使用 Claude 进行高效提示缓存的技术。

## 附加资源

- [AWS 上的 Anthropic](https://github.com/aws-samples/anthropic-on-aws)：探索在 AWS 基础设施上使用 Claude 的示例和解决方案。
- [AWS 示例](https://github.com/aws-samples/)：来自 AWS 的代码示例集合，可以调整以与 Claude 最佳配合使用。请注意，某些示例可能需要修改才能与 Claude 最佳配合。

---

# Anthropic Cookbook

The Anthropic Cookbook provides code and guides designed to help developers build with Claude, offering copy-able code snippets that you can easily integrate into your own projects.

## Prerequisites

To make the most of the examples in this cookbook, you'll need an Anthropic API key (sign up for free [here](https://www.anthropic.com)).

While the code examples are primarily written in Python, the concepts can be adapted to any programming language that supports interaction with the Anthropic API.

If you're new to working with the Anthropic API, we recommend starting with our [Anthropic API Fundamentals course](https://github.com/anthropics/courses/tree/master/anthropic_api_fundamentals) to get a solid foundation.

## Explore Further

Looking for more resources to enhance your experience with Claude and AI assistants? Check out these helpful links:

- [Anthropic developer documentation](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources)
- [Anthropic support docs](https://support.anthropic.com)
- [Anthropic Discord community](https://www.anthropic.com/discord)

## Contributing

The Anthropic Cookbook thrives on the contributions of the developer community. We value your input, whether it's submitting an idea, fixing a typo, adding a new guide, or improving an existing one. By contributing, you help make this resource even more valuable for everyone.

To avoid duplication of efforts, please review the existing issues and pull requests before contributing.

If you have ideas for new examples or guides, share them on the [issues page](https://github.com/anthropics/anthropic-cookbook/issues).

## Table of recipes

### Skills

- [Classification](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/classification): Explore techniques for text and data classification using Claude.
- [Retrieval Augmented Generation](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/retrieval_augmented_generation): Learn how to enhance Claude's responses with external knowledge.
- [Summarization](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/summarization): Discover techniques for effective text summarization with Claude.

### Tool Use and Integration

- [Tool use](https://github.com/anthropics/anthropic-cookbook/tree/main/tool_use): Learn how to integrate Claude with external tools and functions to extend its capabilities.
  - [Customer service agent](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/customer_service_agent.ipynb)
  - [Calculator integration](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/calculator_tool.ipynb)
  - [SQL queries](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_make_sql_queries.ipynb)

### Third-Party Integrations

- [Retrieval augmented generation](https://github.com/anthropics/anthropic-cookbook/tree/main/third_party): Supplement Claude's knowledge with external data sources.
  - [Vector databases (Pinecone)](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Pinecone/rag_using_pinecone.ipynb)
  - [Wikipedia](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Wikipedia/wikipedia-search-cookbook.ipynb/)
  - [Web pages](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/read_web_pages_with_haiku.ipynb)
  - [Internet search (Brave)](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Brave/web_search_using_brave.ipynb)
- [Embeddings with Voyage AI](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/VoyageAI/how_to_create_embeddings.md)

### Multimodal Capabilities

- [Vision with Claude](https://github.com/anthropics/anthropic-cookbook/tree/main/multimodal):
  - [Getting started with images](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/getting_started_with_vision.ipynb)
  - [Best practices for vision](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb)
  - [Interpreting charts and graphs](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/reading_charts_graphs_powerpoints.ipynb)
  - [Extracting content from forms](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/how_to_transcribe_text.ipynb)
- [Generate images with Claude](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/illustrated_responses.ipynb): Use Claude with Stable Diffusion for image generation.

### Advanced Techniques

- [Sub-agents](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/using_sub_agents.ipynb): Learn how to use Haiku as a sub-agent in combination with Opus.
- [Upload PDFs to Claude](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/pdf_upload_summarization.ipynb): Parse and pass PDFs as text to Claude.
- [Automated evaluations](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_evals.ipynb): Use Claude to automate the prompt evaluation process.
- [Enable JSON mode](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_enable_json_mode.ipynb): Ensure consistent JSON output from Claude.
- [Create a moderation filter](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_moderation_filter.ipynb): Use Claude to create a content moderation filter for your application.
- [Prompt caching](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/prompt_caching.ipynb): Learn techniques for efficient prompt caching with Claude.

## Additional Resources

- [Anthropic on AWS](https://github.com/aws-samples/anthropic-on-aws): Explore examples and solutions for using Claude on AWS infrastructure.
- [AWS Samples](https://github.com/aws-samples/): A collection of code samples from AWS which can be adapted for use with Claude. Note that some samples may require modification to work optimally with Claude.
