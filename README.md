# Qwen1.5_utils


# Qwen1.5实现function 调用
1. 不能使用ollama 的qwen的openai接口调用，因为没有实现functioncall 参考 [link](https://github.com/ollama/ollama/blob/main/docs/openai.md)  所以Ollama应该也不会实现openai的agent functioncall这些功能暂时
2. 不能使用qwen里面的openai_api这个版本调用，因为这个版本只支持qwen的1.0版本. 且Qwen1.5这个repo都出了很久了，有人提也很久了，应该也不会更新openai_api.py这个文档了 [link](https://github.com/QwenLM/Qwen1.5)
3. 只能基于openai_api来改
