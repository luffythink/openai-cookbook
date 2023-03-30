# OpenAI Cookbook

The OpenAI Cookbook shares example code for accomplishing完成 common tasks with the [OpenAI API].
OpenAI中文手册分享了使用 OpenAI API 完成常见任务的示例代码。

To run these examples, you'll need an OpenAI account and associated相关的 API key ([create a free account][api signup]).

Most code examples are written in Python, though the concepts can be applied in any language.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=468576060&machine=basicLinux32gb&location=EastUs)

## Recently added 🆕 ✨

- [How to format inputs to ChatGPT models](examples/How_to_format_inputs_to_ChatGPT_models.ipynb) [Mar 1st, 2023]
- [Using Vector Databases for Embeddings Search with Redis](https://github.com/openai/openai-cookbook/tree/main/examples/vector_databases/redis) [Feb 15th, 2023]使用向量数据库在Redis中进行嵌入搜索

- [Website Q&A with Embeddings](https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a) [Feb 11th, 2023]
- [File Q&A with Embeddings](https://github.com/openai/openai-cookbook/tree/main/apps/file-q-and-a) [Feb 11th, 2023]
- [Visualize Embeddings in Weights & Biases](https://github.com/openai/openai-cookbook/blob/main/examples/Visualizing_embeddings_in_W%26B.ipynb) [Feb 9th, 2023]在权重和偏差中可视化嵌入
- [Retrieval检索 Enhanced Generative Question Answering with Pinecone](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/pinecone/Gen_QA.ipynb) [Feb 8th, 2023] 用Pinecone检索增强生成式问答


## Guides & examples 
## 指南 & 示例

- API usage用法
  - [How to handle rate limits](examples/How_to_handle_rate_limits.ipynb)如何处理请求频率限制
    - [Example parallel processing script that avoids hitting rate limits](examples/api_request_parallel_processor.py)避免触及请求频率限制的并行处理脚本示例
  - [How to count tokens with tiktoken](examples/How_to_count_tokens_with_tiktoken.ipynb)
  - [How to stream completions](examples/How_to_stream_completions.ipynb)如何串联补全
- ChatGPT
  - [How to format inputs to ChatGPT models](examples/How_to_format_inputs_to_ChatGPT_models.ipynb)
- GPT-3
  - [Guide: How to work with large language models](how_to_work_with_large_language_models.md)
  - [Guide: Techniques to improve reliability](techniques_to_improve_reliability.md)提高可靠性的技术
  - [How to use a multi-step prompt to write unit tests](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)使用多步骤提示来编写单元测试
  - [Text writing examples](text_writing_examples.md)文本写作实例
  - [Text explanation examples](text_explanation_examples.md)文本解释实例
  - [Text editing examples](text_editing_examples.md)文本编辑实例
  - [Code writing examples](code_writing_examples.md)
  - [Code explanation examples](code_explanation_examples.md)
  - [Code editing examples](code_editing_examples.md)
- Embeddings词嵌入
  - [Text comparison examples](text_comparison_examples.md)文本比较实例
  - [How to get embeddings](examples/Get_embeddings.ipynb)如何获得词嵌入
  - [Question answering using embeddings](examples/Question_answering_using_embeddings.ipynb)使用词嵌入回答问题
  - [Semantic search using embeddings](examples/Semantic_text_search_using_embeddings.ipynb)使用词嵌入的语义搜索
  - [Recommendations using embeddings](examples/Recommendation_using_embeddings.ipynb)使用词嵌入的建议
  - [Clustering embeddings](examples/Clustering.ipynb)对词嵌入进行聚类
  - [Visualizing embeddings in 2D](examples/Visualizing_embeddings_in_2D.ipynb) or [3D](examples/Visualizing_embeddings_in_3D.ipynb)在二维或3 维中可视化嵌入
  - [Embedding long texts](examples/Embedding_long_inputs.ipynb)词嵌入长文本
- Fine-tuning GPT-3 微调GPT-3 
  - [Guide: best practices for fine-tuning GPT-3 to classify text](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)指南：微调 GPT-3 对文本进行分类的最佳做法
  - [Fine-tuned classification](examples/Fine-tuned_classification.ipynb)微调分类
- DALL-E
  - [How to generate and edit images with DALL-E](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)如何用 DALL-E生成和编辑图像
- Azure OpenAI (alternative API from Microsoft Azure)基于微软 Azure 的 OpenAI
  - [How to use ChatGPT with Azure OpenAI](examples/azure/chat.ipynb)
  - [How to get completions from Azure OpenAI](examples/azure/completions.ipynb)如何从 Azure OpenAI 获取补全功能
  - [How to get embeddings from Azure OpenAI](examples/azure/embeddings.ipynb)如何从 Azure OpenAI 获取词向量功能
  - [How to fine-tune GPT-3 with Azure OpenAI](examples/azure/finetuning.ipynb)如何用 Azure OpenAI 微调 GPT-3
- Apps
  - [File Q and A](apps/file-q-and-a/)文件问答
  - [Web Crawl Q and A](apps/web-crawl-q-and-a)网络爬行问答

## Related resources
## 相关资源

Beyond the code examples here, you can learn about the [OpenAI API] from the following resources:
除了这里的代码示例，你可以从以下资源中了解OpenAI API：

- Try out the API in the [OpenAI Playground] 在OpenAI游乐场试实验API的使用效果
- Read about the API in the [OpenAI Documentation] 在OpenAI文档了解 API的使用方法
- Discuss the API in the [OpenAI Community社区 Forum论坛] 在社区论坛讨论API的使用经验
- Look for help in the [OpenAI Help Center] 在OpenAI帮助中心寻求使用问题的帮助
- See example prompts in the [OpenAI Examples] 在OpenAI案例库找到更多使用案例
- Play with a free research preview of [ChatGPT] 使用免费的研究预览版 [ChatGPT] 进行游戏
- Stay up to date with the [OpenAI Blog]

## Contributing

If there are examples or guides you'd like to see, feel free to suggest them on the [issues page].
如果有你喜欢的例子或指南，请随时在问题页上提出。

[chatgpt]: https://chat.openai.com/
[openai api]: https://openai.com/api/
[api signup]: https://beta.openai.com/signup
[openai playground]: https://beta.openai.com/playground
[openai documentation]: https://beta.openai.com/docs/introduction
[openai community forum]: https://community.openai.com/top?period=monthly
[openai help center]: https://help.openai.com/en/
[openai examples]: https://beta.openai.com/examples
[openai blog]: https://openai.com/blog/
[issues page]: https://github.com/openai/openai-cookbook/issues
