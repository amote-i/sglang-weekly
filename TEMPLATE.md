## 新增参数

| 前一个参数/新参数分组 | 参数名称              | 默认值        | 可选值                        | 描述              |
|-----------------------|-----------------------|---------------|-------------------------------|-------------------|
| Http Server（新分组） | --host                | 127.0.0.1     | Type: str                     | The host of the http server   |
| --grpc-mode           | --skip-server-warmup  | False         | Type: bool（set to enable）   | if set, skip warmup           |

> 表格首列可以指定前一个参数或新参数分组，用于明确新增参数的位置，如果是新增分组，需要在参数名称前添加分组名称。如果不是则说明前一个参数的名称，用于定位。

## 新增模型

| 模型类型              | 模型族    | 模型名称              |
|-----------------------|-----------|-----------------------|
| Large Language Model  | ChatGLM   | ZhipiAI/chatglm2-6b   |

> 模型类型共分为 Large Language Model，Multimodal Language Model，Embedding Model，Reward Model，Rerank Model，Diffusion Language Model 这6种类型。
> 如果新增的模型类型不在这6种类型中，需要根据模型的功能和能力，划分到这6种类型中的某一种。