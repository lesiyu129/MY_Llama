# python > 3.10
```shell
  pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple

  # Ollama 导入 gguf 模型并启动
  # 创建一个名为 的文件Modelfile，其中包含包含FROM要导入模型的本地文件路径的指令。
  FROM ./vicuna-33b.Q4_0.gguf
  # 在 Ollama 中创建模型
  ollama create example -f Modelfile
  # 运行模型
  ollama run example
```