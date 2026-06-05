# Wang Hui

AI 应用后端与企业知识服务方向，关注把 LLM / RAG / 数字员工能力接入真实业务系统，并补齐服务边界、数据流、权限、日志、trace、评测、降级和交付风险。

## 作品主线

这组仓库不是单点 Demo，而是一条 AI 应用后端工程链路：

```text
文档解析与切片 -> 企业知识检索/RAG -> 业务型 AI 应用 -> AI 能力平台化
ChunkFlow      -> RecallForge        -> PeiLian      -> ai-platform
```

## Featured Projects

| Project | Positioning | What it shows |
| --- | --- | --- |
| [ai-backend-portfolio](https://github.com/hui-wang-lab/ai-backend-portfolio) | 完整作品集入口 | 作品索引、case study、架构图、能力映射和阅读指南 |
| [ai-platform](https://github.com/hui-wang-lab/ai-platform) | 企业级 AI 能力平台 | 多服务边界、控制台、知识服务、数字员工、LLM Gateway 与平台化组织方式 |
| [RecallForge](https://github.com/hui-wang-lab/RecallForge) | 企业级 RAG 知识服务 | 文档接入、检索、引用、权限隔离、可追溯与可评测的 RAG 链路 |
| [ChunkFlow](https://github.com/hui-wang-lab/ChunkFlow) | 面向 RAG 的文档解析与切片服务 | 多解析器降级、文档类型识别、父子 chunk、质量诊断与执行链路 |
| [PeiLian](https://github.com/hui-wang-lab/PeiLian) | 寿险代理人 AI 文本陪练系统 | 业务型 AI 应用、persona、对话状态、规则评估、LLM-as-Judge 与 Web 报告 |

## Capability Map

| Capability | Evidence |
| --- | --- |
| RAG 工程化 | `ChunkFlow` 负责高质量切片，`RecallForge` 负责企业知识检索与 RAG 服务 |
| AI 应用后端架构 | `ai-platform` 以服务边界组织训练、知识、编排、数字员工和模型网关能力 |
| 数字员工 / Agent 建模 | `ai-platform` 与 `PeiLian` 展示 persona、run、state、event、trace 类后端建模思路 |
| 评测与可观测 | `PeiLian` 的规则评估 / LLM-as-Judge，`ChunkFlow` 的质量监控，`RecallForge` 的可评测性设计 |
| 企业交付意识 | 关注权限、审计、日志、降级、合成数据和脱敏边界 |

## Reading Path

1. 先看 [ai-backend-portfolio](https://github.com/hui-wang-lab/ai-backend-portfolio)：理解作品索引、能力映射和阅读路径。
2. 再看 [ai-platform](https://github.com/hui-wang-lab/ai-platform)：理解整体 AI 平台边界。
3. 继续看 [RecallForge](https://github.com/hui-wang-lab/RecallForge) 与 [ChunkFlow](https://github.com/hui-wang-lab/ChunkFlow)：理解可信 RAG 链路。
4. 最后看 [PeiLian](https://github.com/hui-wang-lab/PeiLian)：理解 AI 能力如何落到具体业务场景。

## Notes

公开仓库均以学习、重构或脱敏 Demo 为边界，不包含公司私有代码、客户数据、合同、真实接口地址或密钥。重点展示工程建模、接口设计、系统边界、评测与交付取舍。
