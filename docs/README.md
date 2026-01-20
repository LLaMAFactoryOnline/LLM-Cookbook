# LLM-Cookbook 


<div align='center'>
    <img src="./images/2.jpg" alt="alt text" width="100%"> 
    <h1>LLM-Cookbook</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/github/stars/LLaMAFactoryOnline/LLaMA-Factory-Online?style=flat&logo=github" alt="GitHub stars"/>
  <img src="https://img.shields.io/github/forks/LLaMAFactoryOnline/LLaMA-Factory-Online?style=flat&logo=github" alt="GitHub forks"/>
  <img src="https://img.shields.io/badge/language-Chinese-brightgreen?style=flat" alt="Language"/>
  <a href="https://github.com/LLaMAFactoryOnline/LLaMA-Factory-Online"><img src="https://img.shields.io/badge/GitHub-Project-blue?style=flat&logo=github" alt="GitHub Project"></a>

</div>



<div align="center">

[中文](./README.md) | [English](./README_en.md)

</div>

<div align="center">

  <h3>📚 从零开始的大语言模型微调实战实践教程</h3>
  <p><em>从零掌握大模型微调核心技术，手把手实现专业级模型定制（Powered by LLaMA-Factory Online）</em></p>
</div>

---



## 🎯 项目介绍

  随着大语言模型的快速发展，越来越多开发者希望将自己的专业知识、垂直领域数据与大模型结合，但面对庞大的模型参数、复杂的训练流程和多样的微调技术，往往感到无从下手。为此，我们推出《LLM-Cookbook》项目，旨在为开发者提供一份全面、实用的大模型微调实战指南。

  本项目是专门针对大模型微调的系统性教程，从基础概念到高级技巧，从理论原理到代码实战，全面覆盖微调的各个环节。我们将带领你深入理解不同微调方法的核心机制，掌握数据处理、参数调优、模型评估的实战技能，并通过真实行业案例展示如何将大模型落地到实际业务场景。我们希望这份指南能够成为每一位希望掌握大模型定制化能力的开发者的必备手册。



## ✨ 你将收获什么？

🎯 **理论基础深入掌握**
- 深入理解大模型微调的核心原理与技术发展脉络
- 掌握 LoRA、Adapter、Prefix Tuning 等高效微调方法的机制
- 理解不同微调策略的适用场景与选择依据

🛠️ **实战技能全面提升**
- 掌握数据处理、模型训练、评估优化的全流程实践
- 学会在不同硬件资源下进行微调的性能优化技巧
- 掌握模型部署、监控、迭代的工程化方法



🏢 **行业应用深度实践**
- 学习医疗、法律、金融、工业等垂直领域的微调案例
- 掌握行业合规性、数据安全、效果评估的专业知识
- 了解企业级大模型应用的完整解决方案

🌐 **开源生态积极参与**
- 加入活跃的开源社区，与行业专家深度交流
- 获得免费的云上微调算力支持
- 参与贡献，成为项目核心维护者

## 📖 内容导航


# 📚 大模型微调学习导航表（含状态）

| 章节序号 | 章节标题                          | 核心内容              | 状态 |
|----------|-----------------------------------|--------------------------------|------|
| 第一章   |  [NLP详解](./chapter1/1.%20NLP是什么.md)  | 讲解NLP的基础概念、技术演进和核心任务。| ✅    |
| 第二章   | [Transformer架构](./chapter2/1.%20Transformer的历史意义与技术革命.md)| 解析注意力机制，搭建完整Transformer模型。| ✅    |
| 第三章   | [预训练语言模型](./chapter3/1.%20预训练语言模型的革命性意义.md) | 介绍三类预训练语言模型的架构与选型指南。| ✅    |
| 第四章   | [大语言模型](./chapter4/1.%20大语言模型的时代意义.md)| 解读大语言模型的定义与训练方法。| ✅    |
| 第五章   | [大模型微调](./chapter5/1.%20大模型微调的必要性与价值.md) | 讲解SFT、LoRA等主流微调技术，提供实战指南与避坑方案。| ✅  |
| 第六章   | [微调与其他模型优化方案的区别](./chapter6/1.%20理解模型优化的全景图.md)| 对比微调与提示工程、蒸馏、预训练的差异，给出决策框架。| ✅   |
| 第七章   | [主流大模型微调框架与工具栈](./chapter7/1.%20构建高效微调生态系统.md)| 介绍PEFT等微调工具，以及数据处理、硬件优化等配套方案。| ✅    |
| 第八章   | [数据集构建与处理](./chapter8/1.%20数据质量决定模型上限.md)| 讲解数据集构建原则与预处理流程。| ✅    |
| 第九章   | [微调参数详解](./chapter9/1.%20超参数的艺术与科学.md) | 解析学习率、Batch Size等超参数的调优技巧与速查表。| ✅    |
| 第十章   | [LLaMA-Factory Online](./chapter10/产品简介.md)| 介绍云端微调平台的注册、使用与免费体验。| ✅    |
| 第十一章 | [最佳实践](./chapter11/最佳实践.md) | 展示医疗、法律、金融领域的大模型微调落地案例。| 🛠️    |

---


## 🎯 模型篇


## 精选最新模型列表

平台内置海量AI模型，用户只需点击[模型列表](./Extra-Chapter/modelList)可查看并获取所有模型，无需逐一手动搜索。以下是平台最新推出的代表性模型示例：Qwen3、InternVL3、Qwen3-VL 等。模型普遍具备以下前沿技术特性：  
- **思考链（Chain-of-Thought, CoT）推理能力**  
- **混合专家（Mixture of Experts, MoE）架构**  
- **基于强化学习（Reinforcement Learning, RL）的优化机制**
- **多模态理解、视频解析、复杂推理**等综合能力更强的模型，以满足多样化的应用需求


| 模型名称 | 使用领域 | 下载地址 | Publisher | 主要特点 |
|---------|---------|---------|-----------|---------|
| Qwen3-4B-Instruct-2507 | 指令跟随 | /shared-only/models/Qwen/Qwen3-4B-Thinking-2507 | Qwen | 2025年7月最新指令版本 |
| Qwen3-4B-Thinking-2507 | 复杂推理 | /shared-only/models/Qwen/Qwen3-4B-Instruct-2507 | Qwen | 2025年7月思考链版本 |
| Qwen3-Omni-30B-A3B-Instruct | 多模态 | /shared-only/models/Qwen/Qwen3-Omni-30B-A3B-Instruct | Qwen | 全能多模态最新版 |
| Qwen3-Omni-30B-A3B-Thinking | 多模态推理 | /shared-only/models/Qwen/Qwen3-Omni-30B-A3B-Instruct | Qwen | 全能多模态思考链 |
| Qwen3-VL-4B-Instruct | 视觉理解 | /shared-only/models/Qwen/Qwen3-VL-4B-Instruct | Qwen | Qwen3系列最新视觉模型 |
| Qwen3-VL-4B-Thinking | 视觉推理 | /shared-only/models/Qwen/Qwen3-VL-4B-Thinking | Qwen | 思考链视觉模型最新 |
| Qwen3-VL-8B-Instruct | 视觉理解 | /shared-only/models/Qwen/Qwen3-VL-8B-Instruct | Qwen | 8B视觉模型最新版 |
| Qwen3-VL-8B-Thinking | 视觉推理 | /shared-only/models/Qwen/Qwen3-VL-8B-Thinking | Qwen | 8B思考链视觉最新 |
| Qwen3-VL-30B-A3B-Instruct | 视觉理解 | /shared-only/models/Qwen/Qwen3-VL-30B-A3B-Instruct | Qwen | MoE架构视觉最新 |
| Qwen3-VL-30B-A3B-Thinking | 视觉推理 | /shared-only/models/Qwen/Qwen3-VL-30B-A3B-Thinking | Qwen | MoE思考链视觉最新 |
| Qwen3-VL-235B-A22B-Instruct | 视觉理解 | /shared-only/models/Qwen/Qwen3-VL-235B-A22B-Instruct | Qwen | 超大规模视觉最新 |
| Qwen3-VL-235B-A22B-Thinking | 视觉推理 | /shared-only/models/Qwen/Qwen3-VL-235B-A22B-Thinking | Qwen | 顶尖视觉推理最新 |
| DeepSeek-R1-0528-Qwen3-8B | 推理增强 | /shared-only/models/deepseek-ai/DeepSeek-R1-0528-Qwen3-8B | DeepSeek | 2025年5月推理模型 |
| Kimi-VL-A3B-Thinking-2506 | 视觉推理 | /shared-only/models/moonshotai/Kimi-VL-A3B-Thinking-2506 | Moonshot AI | 2025年6月思考链版 |
| LLaVA-NeXT-Video-34B-DPO-hf | 视频理解 | /shared-only/models/llava-hf/LLaVA-NeXT-Video-34B-DPO-hf | LLaVA | DPO优化最新视频 |
| InternVL3-78B | 视觉理解 | /shared-only/models/OpenGVLab/InternVL3-78B | OpenGVLab | 最新大规模视觉模型 |
| Llama-4-Scout-17B-16E-Instruct | 多感官输入 | /shared-only/models/meta-llama/Llama-4-Scout-17B-16E-Instruct | Meta | Meta最新多模态 |
| MiMo-7B-RL-0530 | 强化学习 | /shared-only/models/XiaomiMiMo/MiMo-7B-RL-0530 | Xiaomi | 2025年5月RL版本 |
| MiniCPM-V-4_5 | 视觉理解 | /shared-only/models/openbmb/MiniCPM-V-4_5 | OpenBMB | 最新轻量视觉模型 |
| Ovis2.5-9B | 通用模型 | /shared-only/models/openbmb/MiniCPM-V-4_5 | OpenBMB | 最新通用模型 |






## 📊 行业专用数据集库

平台内置海量AI模型，这些数据集共同构成了从基础预训练到高级任务微调的完整数据生态，支持多语言、多模态大语言模型的开发与训练，点击[数据集列表](./Extra-Chapter/datasetlList)免费获取更多高质量数据集。

**基础预训练**数据集：包括wikipedia_zh、wikipedia_en、refinedweb和redpajama_v2等，它们规模巨大、内容通用，是模型学习语言和世界知识的基石。

**指令监督微调**数据集：以alpaca_en和alpaca_zh_demo为代表，用于教会模型理解并遵循人类的指令进行对话和任务执行。

**工具调用微调**数据集：如glaive_toolcall_en_demo和glaive_toolcall_zh_demo，专门训练模型理解“调用外部函数”并处理返回结果的能力。

**多模态微调**数据集：包括mllm_audio_demo、mllm_video_demo等，通过关联文本与音频、视频文件，训练模型处理和理解多模态信息。

**领域专项微调**数据集：例如针对自动驾驶的QA_from_CoVLA_zh、针对医疗的medical_o1_sft_Chinese_alpaca以及定义身份的identity，用于增强模型在特定垂直领域的专业性或行为规范。

这些数据集共同支撑了大语言模型从通用知识学习、对话能力培养到专项技能赋予的全阶段开发流程。

| 数据集名称 | 数据集大小 | 数据集路径 | Publisher | 数据集描述 |
| :--- | :--- | :--- | :--- | :--- |
| wikipedia_zh | 501MB | `/shared-only/datasets/pleisto/wikipedia-cn-20230720-filtered/wikipedia-cn-20230720-filtered.json` | pleisto | 经过过滤和处理的2023年7月20日中文维基百科数据，适用于中文模型预训练。 |
| wikipedia_en | 12GB | `/shared-only/datasets/olm/olm-wikipedia-20221220/data/` | olm | 包含2022年12月20日英文维基百科快照的文本，高质量知识性预训练语料。 |
| refinedweb | 568GB | `/shared-only/datasets/tiiuae/falcon-refinedweb/data/` | TII | 由TII为Falcon模型创建的高质量网络文本，经过大量过滤和去重，是目前最好的开放网络语料之一。 |
| QA_from_CoVLA_zh | 940MB | `/shared-only/datasets/AlayaNeW/QA_from_CoVLA_zh/data/QA_from_CoVLA_zh.json` | AlayaNeW | 专为多模态大模型微调任务构建，聚焦自动驾驶场景下的视觉识别需求。基于QA_from_CoVLA数据集进行翻译整理的中文版本。适配了llamafactory框架微调数据集格式。 |
| redpajama_v2 | 114MB | `/shared-only/datasets/togethercomputer/RedPajama-Data-V2` | togethercomputer | 一个旨在完全开源地复现LLaMA模型训练数据的项目，包含海量、多样的文本和代码。 |
| medical_o1_sft_Chinese_alpaca | 49GB | `/shared-only/datasets/medical_o1_sft_Chinese_alpaca.json` | llamafactory | 暂无 |
| identity | 20KB | `/shared-only/datasets/identity.json` | llamafactory | 包含多种语言（中英）的用户询问及对应的AI助手回复模板，涉及AI助手的名称和开发者信息。 |
| alpaca_en | 22MB | `/shared-only/datasets/alpaca_data_en_52k.json` | llamafactory | Alpaca格式的英文指令微调数据集，包含用户指令、输入、模型回答、系统提示和对话历史。 |
| alpaca_zh_demo | 622KB | `/shared-only/datasets/alpaca_zh_demo.json` | llamafactory | Alpaca格式的中文指令微调数据集，包含指令、输入、回答、系统提示和对话历史。 |
| glaive_toolcall_en_demo | 722KB | `/shared-only/datasets/glaive_toolcall_en_demo.json` | llamafactory | ShareGPT格式、英文微调数据集，包含多角色对话（如 human、gpt、function_call 等）。 |
| glaive_toolcall_zh_demo | 722KB | `/shared-only/datasets/glaive_toolcall_zh_demo.json` | llamafactory | ShareGPT格式、中文微调数据集，包含多角色对话（如 human、gpt、function_call 等）。 |
| mllm_audio_demo | 877B | `/shared-only/datasets/mllm_audio_demo.json` | llamafactory | ShareGPT 格式的多模态音频数据集，含对话和音频路径，用于音频问答微调。 |
| mllm_video_demo | 828B | `/shared-only/datasets/mllm_video_demo.json` | llamafactory | ShareGPT 格式的多模态视频数据集，含视频问答及视频路径，用于视频问答微调。 |
| mllm_video_audio_demo | 1.1KB | `/shared-only/datasets/mllm_video_audio_demo.json` | llamafactory | ShareGPT 格式的多模态音视频数据集，含音视频问答及对应文件路径，用于音视频问答微调。 |



## 💡 如何学习

### 目标受众
- 🤖 **AI工程师/算法工程师**：希望系统掌握大模型微调技术
- 🎓 **学生/研究人员**：需要理论基础与实验指导
- 🏢 **企业技术负责人**：寻求大模型落地解决方案
- 💻 **开发者/爱好者**：对AI感兴趣，希望参与开源项目

### 学习路径建议

#### 初学者路径（建议2-3周）
1. **第一周**：阅读第1-3章，建立微调基础认知
2. **第二周**：学习第5章，完成第一个微调实验
3. **第三周**：选择感兴趣的行业案例（第7章）进行实践

#### 进阶者路径（建议1-2周）
1. **深度学习**：重点学习第2、4、8章的技术细节
2. **系统实践**：使用 LLaMA-Factory Online 完成端到端项目
3. **源码研究**：阅读项目提供的完整代码案例

#### 专家路径
1. **技术创新**：研究第2章中的前沿微调技术
2. **性能优化**：实践第4、8章的调优技巧
3. **贡献社区**：提交PR参与项目

### 学习建议
1. **理论结合实践**：每个技术点都配有代码示例，建议动手运行
2. **循序渐进**：按照章节顺序学习，打好基础再深入
3. **社区互动**：遇到问题及时在Issue区提问，积极参与讨论
4. **持续更新**：关注项目更新，了解最新技术动态

## 🤝 如何贡献

我们热烈欢迎任何形式的贡献，共同打造最好的大模型微调学习资源！

### 🐛 报告问题
- 发现文档错误、代码Bug？请提交[Issue](https://github.com/LLaMAFactoryOnline/LLaMA-Factory-Online/issues)。
- 详细描述问题，提供复现步骤，我们会尽快处理。

### 💡 提出建议
- 有好的想法或功能建议？欢迎分享
- 包括：新章节建议、技术补充、案例添加等

### 📝 完善内容
- 补充缺失的技术细节
- 优化文档表达，提升可读性
- 翻译多语言版本

### 🔧 代码贡献
- 修复代码Bug
- 优化算法实现
- 添加新的示例代码

### 🏢 行业案例贡献
- 分享你的行业微调实践经验
- 提供经过验证的数据集和模型
- 贡献企业级应用案例



### 🚀 参与步骤
1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 🙏 致谢

### 核心贡献团队
- **项目发起人**：LLM-Cookbook团队




## ⭐ 支持我们

如果这个项目对您有帮助，请给我们一个Star！⭐
您的支持是我们持续更新的最大动力！


## 📞 联系与交流

### 官方平台
- 🌐 **官方网站**：https://www.llamafactory.online/
- 💬 **在线文档**：https://docs.llamafactory.online/
- 🎥 **视频教程**：https://space.bilibili.com/3546954208381522/upload/video
- 💬 **微信交流群**：（扫码添加助手，备注"微调指南"）




## 📜 开源协议

本项目采用 **知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议** 进行许可。

**您可以自由地：**
- 分享 — 在任何媒介以任何形式复制、发行本作品
- 演绎 — 修改、转换或以本作品为基础进行创作

**惟须遵守下列条件：**
- 署名 — 您必须给出适当的署名，提供指向本许可协议的链接，同时标明是否对原始作品作了修改。您可以用任何合理的方式来署名，但是不得以任何方式暗示许可人为您或您的使用背书。
- 非商业性使用 — 您不得将本作品用于商业目的。
- 相同方式共享 — 如果您再混合、转换或者基于本作品进行创作，您必须基于与原先相同的许可协议分发您贡献的作品。

---

**关于 LLaMA-Factory**  
LLaMA-Factory Online是一个开源的大模型微调与部署平台，致力于降低大模型应用门槛，让每一位开发者都能轻松使用和定制大模型。无需编写代码通过交互式选参即可轻松完成大模型微调任务，支持SFT、DPO等训练方法和LoRA、Freeze调优算法，提供高性能GPU卡进行单机多卡、多机多卡分布式训练。

扫描二维码关注我们，获取最新技术动态和活动信息：

![alt text](./images/1.jpg)


**一起构建更智能的未来！** 🚀