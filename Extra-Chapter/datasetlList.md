# 数据集列表

| 数据集名称 | 数据集大小 | 数据集路径 | Publisher | 数据集描述 |
| :--- | :--- | :--- | :--- | :--- |
| wikipedia_zh | 501MB | `/shared-only/datasets/pleisto/wikipedia-cn-20230720-filtered/wikipedia-cn-20230720-filtered.json` | pleisto | 经过过滤和处理的2023年7月20日中文维基百科数据，适用于中文模型预训练。 |
| wikipedia_en | 12GB | `/shared-only/datasets/olm/olm-wikipedia-20221220/data/` | olm | 包含2022年12月20日英文维基百科快照的文本，是高质量的知识性预训练语料。 |
| refinedweb | 568GB | `/shared-only/datasets/tiiuae/falcon-refinedweb/data/` | TII | 由TII为Falcon模型创建的高质量网络文本，经过大量过滤和去重，是目前最好的开放网络语料之一。 |
| olcc_test_ppl_filtered | 202KB | `/shared-only/datasets/ChineseTinyLLM/olcc_test_ppl_filtered.json` | 暂无 | 暂无 |
| QA_from_CoVLA_zh | 940MB | `/shared-only/datasets/AlayaNeW/QA_from_CoVLA_zh/data/QA_from_CoVLA_zh.json` | AlayaNeW | AlayaNeW数据集专为多模态大模型微调任务构建，聚焦自动驾驶场景下的视觉识别需求。基于QA_from_CoVLA数据集进行翻译整理的中文版本。适配了llamafactory框架微调数据集格式。 |
| redpajama_v2 | 114MB | `/shared-only/datasets/togethercomputer/RedPajama-Data-V2` | togethercomputer | 一个旨在完全开源地复现LLaMA模型训练数据的项目，包含海量、多样的文本和代码。 |
| medical_o1_sft_Chinese_alpaca | 49GB | `/shared-only/datasets/medical_o1_sft_Chinese_alpaca.json` | llamafactory | 暂无 |
| identity | 20KB | `/shared-only/datasets/identity.json` | llamafactory | 该数据集主要围绕身份信息展开，包含多种语言（中英）的用户询问（如问候、询问身份、能力等）及对应的AI助手回复模板，模板中涉及AI助手的名称和开发者信息。 |
| alpaca_en | 22MB | `/shared-only/datasets/alpaca_data_en_52k.json` | llamafactory | 该数据集是 Alpaca 格式的英文指令监督微调示例数据集，包含用户指令、输入、模型回答、系统提示词和历史对话消息等内容，用于模型学习和微调。 |
| alpaca_zh_demo | 622KB | `/shared-only/datasets/alpaca_zh_demo.json` | llamafactory | 该数据集是 Alpaca 格式的中文指令监督微调示例数据集，包含用户指令、输入、模型回答、系统提示词和历史对话消息等内容，用于模型学习和微调。 |
| glaive_toolcall_en_demo | 722KB | `/shared-only/datasets/glaive_toolcall_en_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的英文指令监督微调示例数据集，通过 `conversations` 列呈现包含 human、function_call、observation、gpt 等多种角色的对话内容，还可包含系统提示词和工具描述，用于模型学习和工具调用相关的微调训练。 |
| glaive_toolcall_zh_demo | 722KB | `/shared-only/datasets/glaive_toolcall_zh_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的中文指令监督微调示例数据集，以对象列表形式在 `conversations` 列呈现 human、function_call、observation、gpt 等多种角色的对话，还可包含选填的系统提示词和工具描述，用于模型学习和工具调用相关的微调训练。 |
| mllm_demo | 3.3KB | `/shared-only/datasets/mllm_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的多模态语言模型演示数据集，包含多条中英文的图文对话消息及对应图片路径，用于模型学习图像相关的问答交互。 |
| mllm_audio_demo | 877B | `/shared-only/datasets/mllm_audio_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的多模态音频演示数据集，包含用户与助手的对话消息以及对应的音频文件路径，用于多模态模型在音频相关问答上的学习和微调。 |
| mllm_video_demo | 828B | `/shared-only/datasets/mllm_video_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的多模态视频演示数据集，包含用户针对视频提出的问题及对应助手的回答，同时提供视频文件路径，用于多模态模型在视频问答方面的学习和微调。 |
| mllm_video_audio_demo | 1.1KB | `/shared-only/datasets/mllm_video_audio_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的多模态视频与音频演示数据集，包含用户针对视频和音频提出的问题及对应助手的回答，同时提供视频和音频文件的路径，用于多模态模型在视频与音频问答方面的学习和微调。 |
| dpo_zh_demo | 834KB | `/shared-only/datasets/dpo_zh_demo.json` | llamafactory | 该数据集是 Sharegpt 格式的中文偏好演示数据集，包含对话消息、更优回复和更差回复，用于大语言模型基于直接偏好优化（DPO）方法的微调训练。 |
| dpo_en_demo | 1.6MB | `/shared-only/datasets/dpo_en_demo.json` | llamafactory | 该项目提供了丰富多样的数据集，涵盖预训练、指令微调、偏好等类型，包含英文、中文、德文等多语言，涉及百科、对话、问答、数学等广泛内容，支持Alpaca和Sharegpt等格式。 |
| kto_en_demo | 893KB | `/shared-only/datasets/kto_en_demo.json` | llamafactory | 该数据集采用 Sharegpt 格式，包含用户指令与模型回答的对话内容，额外添加了 `kto_tag` 列用于记录人类反馈的布尔值，可用于大语言模型基于 KTO（具体指代需结合上下文）方法的微调训练。 |
| alpaca_zh | 18MB | `/shared-only/datasets/alpaca_data_zh_51k.json` | llamafactory | 该数据集是LLaMA-Factory推出的中文数据集。 |
| coco_2014_caption_vl | 4.8MB | `/shared-only/datasets/Qwen2.5-VL-Fine-Tuning/coco_2014_caption_vl.json` | COCO | coco_2014_caption_vl是基于COCO 2014数据集的图像描述任务，用于Qwen2.5-VL-Fine-Tuning。 |
| alpaca_gpt4_en | 42MB | `/shared-only/datasets/alpaca_gpt4_data_en.json` | llamafactory | 该数据集是LLaMA-Factory推出的英文Alpaca格式指令数据集，内容由GPT-4生成，包含用户指令、输入文本及高质量的模型回答，适用于大语言模型的指令微调任务。 |
| alpaca_gpt4_zh | 27MB | `/shared-only/datasets/alpaca_gpt4_data_zh.json` | llamafactory | 该数据集是LLaMA-Factory推出的中文Alpaca格式指令数据集，内容由GPT-4生成，包含用户指令、输入文本及模型回答，适用于大语言模型的指令微调任务。 |
| manifest | 69GB | `/shared-only/datasets/CoVLA-Dataset-Mini/manifest.json` | CoVLA | 自动驾驶综合视觉-语言-动作数据集。 |
| lima | 3MB | `/shared-only/datasets/llamafactory/lima/lima.json` | llamafactory | 该数据集是 LLaMA-Factory 基于 LIMA（Less Is More for Alignment）理念构建的指令数据集，包含经过筛选的高质量用户指令及对应回答，用于大语言模型的高效对齐训练。 |
| belle_1m | 437MB | `/shared-only/datasets/BelleGroup/train_1M_CN` | BelleGroup | 该数据集是 BelleGroup 发布的中文训练数据集，包含 100 万条中文指令微调数据，适用于大语言模型的训练与优化。 |
| belle_dialog | 524MB | `/shared-only/datasets/BelleGroup/generated_chat_0.4M/generated_chat_0.4M.json` | BelleGroup | 该数据集是 BelleGroup 推出的中文对话数据集，包含 40 万条生成的中文聊天数据，适用于大语言模型的对话能力训练。 |
| belle_math | 132MB | `/shared-only/datasets/BelleGroup/school_math_0.25M/school_math_0.25M.json` | BelleGroup | 该数据集是BelleGroup推出的中文学校数学数据集，包含25万条中小学数学相关的题目及解答，用于大语言模型的数学解题能力训练。 |
| pile | 313GB | `/shared-only/datasets/monology/pile-uncopyrighted` | monology | 一个著名的大规模英文文本语料库，来源非常广泛，包含书籍、网页、代码等。 |
| skypile | 609GB | `/shared-only/datasets/Skywork/SkyPile-150B/data/` | Skywork | 由天工AI团队发布，包含150B tokens的大规模、高质量中文网络语料。 |
| olcc_train_ppl_filtered | 6.1MB | `/shared-only/datasets/ChineseTinyLLM/olcc_train_ppl_filtered.json` | 暂无 | 暂无 |
| open_platypus | 16MB | `/shared-only/datasets/garage-bAInd/Open-Platypus/data/train-00000-of-00001-4fe2df04669d1669.parquet` | Garage-bAInd | Open-Platypus是一个用于微调大语言模型的数据集。它由11个开源数据集组成，主要包含人为设计的问题，侧重于提升大语言模型的STEM和逻辑知识。 |
| codealpaca | 8MB | `/shared-only/datasets/sahil2801/CodeAlpaca-20k/code_alpaca_20k.json` | sahil2801 | 包含2万条代码生成指令的数据集，适用于训练代码助手模型 |
| alpaca_cot | 3.7GB | `/shared-only/datasets/QingyiSi/Alpaca-CoT` | QingyiSi | 该数据集是 Alpaca-CoT，包含带思维链（CoT）的中文指令微调数据，通过结构化展示推理过程提升大语言模型的逻辑思考能力。 |
| OpenOrca_1M-GPT4 | 1.01GB | `/shared-only/datasets/Open-Orca/OpenOrca/1M-GPT4-Augmented.parquet` | OpenOrca | 该数据集是Open-Orca推出的OpenOrca数据集，包含从ChatGPT和GPT-4等模型收集的对话数据，用于大语言模型的训练与优化。 |
| slimproca | 986MB | `/shared-only/datasets/Open-Orca/SlimOrca/oo-labeled_correct.gpt4.sharegpt.jsonl` | OpenOrca | 该数据集是 Open-Orca 推出的 SlimOrca 数据集，精选自 OpenOrca 并经过轻量化处理，保留高质量对话数据用于大语言模型的高效训练与优化。 |
| mathinstruct | 212MB | `/shared-only/datasets/TIGER-Lab/MathInstruct/MathInstruct.json` | TIGER-Lab | 该数据集是 TIGER-Lab 推出的 MathInstruct 数学指令数据集，包含中小学数学问题及解题思路，用于大语言模型的数学推理与解题能力训练。 |
| firefly | 1.1GB | `/shared-only/datasets/YeungNLP/firefly-train-1.1M/firefly-train-1.1M.jsonl` | YeungNLP | 该数据集是YeungNLP推出的firefly-train-1.1M中文训练数据集，包含110万条指令微调数据，适用于大语言模型的训练与优化。 |
| wikiqa | 3MB | `/shared-only/datasets/microsoft/wiki_qa/data/` | llamafactory | 一个经典的问答数据集，问题和答案对均来自维基百科。 |
| webqa | 15MB | `/shared-only/datasets/suolyer/webqa/train.json` | suolyer | 该数据集是suolyer推出的webqa中文网络问答数据集，包含基于网页信息的问答对，用于大语言模型的问答能力训练。 |
| webnovel | 603MB | `/shared-only/datasets/zxbsmk/webnovel_cn/novel_cn_token512_50k.json` | zxbsmk | 该数据集是zxbsmk推出的webnovel_cn中文网络小说数据集，包含各类网络小说文本，适用于自然语言处理相关的训练与研究。 |
| nectar_sft | 252MB | `/shared-only/datasets/AstraMindAI/SFT-Nectar/sft_data_structured.json` | AstraMindAI | 该数据集是 AstraMindAI 推出的 SFT-Nectar 数据集，包含多领域中文指令微调数据，用于大语言模型的监督微调以提升多任务处理能力。 |
| deepctrl | 28GB | `/shared-only/datasets/deepctrl/deepctrl-sft-data` | DeepCTRL（深智AI） | 由DeepCTRL（深智AI）在ModelScope上发布的中文监督微调数据集。 |
| adgen_train | 27MB | `/shared-only/datasets/HasturOfficial/adgen/data/train-00000-of-00001-5924736d8b9825b5.parquet` | HasturOfficial | 该数据集是HasturOfficial推出的adgen中文广告生成数据集，包含产品描述与对应广告文案，用于训练大语言模型的广告创意生成能力。 |
| adgen_eval | 254KB | `/shared-only/datasets/HasturOfficial/adgen/data/validation-00000-of-00001-b01a1a8dd8034cf6.parquet` | llamafactory | 与adgen_train配套，用于评估广告文案生成模型效果的验证集。 |
| sharegpt_hyper | 6MB | `/shared-only/datasets/totally-not-an-llm/sharegpt-hyperfiltered-3k/sharegptclean_final.json` | totally-not-an-llm | 包含3000个从ShareGPT数据中经过高度过滤和清洗的对话样本。 |
| sharegpt4 | 575MB | `/shared-only/datasets/shibing624/sharegpt_gpt4` | shibing624 | 从ShareGPT网站收集，并由GPT-4模型润色或生成的对话数据集。 |
| ultrachat_200k | 1.6GB | `/shared-only/datasets/HuggingFaceH4/ultrachat_200k/data/` | HuggingFaceH4 | HuggingFaceH4团队发布的20万条高质量多轮对话SFT数据集。 |
| agent_instruct | 1.3MB | `/shared-only/datasets/THUDM/AgentInstruct/data/` | 清华大学KEG实验室 | 由清华大学KEG实验室构建，专门用于训练能够自主规划和执行任务的AI Agent。 |
| OpenOrca1M-3_5M-GPT3_5 | 3.9GB | `/shared-only/datasets/Open-Orca/OpenOrca/3_5M-GPT3_5-Augmented.parquet` | OpenOrca | OpenOrca 数据集是一个增强型 FLAN Collection 数据集的集合。目前包含约 100 万条 GPT-4 完成结果和约 320 万条 GPT-3.5 完成结果。 |
| ali-demo-eval | 82KB | `/shared-only/datasets/ali/eval.json` | Ali | 阿里训练数据集 |
| glaive_toolcall_100k | 251MB | `/shared-only/datasets/hiyouga/glaive-function-calling-v2-sharegpt/glaive_toolcall.json` | Glaive AI | Glaive AI发布的包含10万条函数/工具调用示例的数据集，是训练模型工具使用能力的重要资源。 |
| cosmopedia | 86GB | `/shared-only/datasets/HuggingFaceTB/cosmopedia` | HuggingFaceTB | 一个大型合成数据集，包含教科书、博客、故事等多种形式的文本，旨在提升模型的知识广度和文本生成能力。 |
| stem_zh | 145MB | `/shared-only/datasets/hfl/stem_zh_instruction` | HFL | 由HFL（哈工大讯飞联合实验室）发布的中文科学、技术、工程和数学（STEM）领域的指令数据集。 |
| ali-demo-train | 894KB | `/shared-only/datasets/ali/train.json` | ali | 阿里训练数据集 |
| neo_sft | 246MB | `/shared-only/datasets/m-a-p/neo_sft_phase2/neo_sft_phase2.json` | m-a-p | 一个用于SFT第二阶段的ShareGPT格式数据集，可能用于对模型进行更精细的调整。 |
| magpie_pro_300k | 538MB | `/shared-only/datasets/Magpie-Align/Magpie-Pro-300K-Filtered/data/` | Magpie-Align | 由Magpie-Align项目发布，包含30万条经过筛选的高质量多语言指令数据。 |
| magpie_ultra | 504MB | `/shared-only/datasets/argilla/magpie-ultra-v0.1/data/` | Argilla和Magpie-Align | 由Argilla和Magpie-Align合作发布，是一个高质量的指令遵循数据集。 |
| web_instruct | 3.3GB | `/shared-only/datasets/TIGER-Lab/WebInstructSub/data/` | TIGER-Lab | 由TIGER-Lab发布，是一个从网络中搜集和构建的大型视觉-语言指令微调数据集。 |
| openo1_sft | 514MB | `/shared-only/datasets/llamafactory/OpenO1-SFT/OpenO1-SFT-Pro.jsonl` | llamafactory | 由LlamaFactory整理的一个开放的指令微调数据集，专注于提升模型的指令遵循能力。 |
| open_thoughts | 1.1GB | `/shared-only/datasets/llamafactory/OpenThoughts-114k/data/` | llamafactory | 是由LlamaFactory整理，包含11.4万条对话，其中显式包含了模型的思考或推理过程（思维链）。 |
| open_r1_math | 472MB | `/shared-only/datasets/llamafactory/OpenR1-Math-94k/data/` | llamafactory | 由LlamaFactory整理，包含9.4万条数学题，答案中包含了详细的解题步骤和推理过程。 |
| chinese_r1_distill | 647MB | `/shared-only/datasets/Congliu/Chinese-DeepSeek-R1-Distill-data-110k-SFT` | llamafactory | 是从中文DeepSeek-R1模型蒸馏（Distill）出的11万条SFT数据，用于传承其能力。 |
| llava_1k_en | 177MB | `/shared-only/datasets/BUAADreamer/llava-en-zh-2k/en/train-00000-of-00001.parquet` | BUAADreamer | 包含1千条英文图文对话数据，用于多模态模型微调。 |
| orca_dpo_de | 63MB | `/shared-only/datasets/mayflowergmbh/intel_orca_dpo_pairs_de/intel_orca_dpo_pairs_de.json` | mayflowergmbh | 是德语版的Intel Orca DPO偏好数据集。 |
| llava_1k_zh | 178MB | `/shared-only/datasets/BUAADreamer/llava-en-zh-2k/zh/train-00000-of-00001.parquet` | BUAADreamer | 是包含1千条中文图文对话数据，用于中文多模态模型微调。 |
| llava_150k_en | 28GB | `/shared-only/datasets/BUAADreamer/llava-en-zh-300k/en` | BUAADreamer | 是包含15万条英文图文对话的大规模数据集，用于增强多模态模型的能力。 |
| llava_150k_zh | 28GB | `/shared-only/datasets/BUAADreamer/llava-en-zh-300k/zh` | BUAADreamer | 是包含15万条中文图文对话的大规模数据集。 |
| pokemon_cap | 155MB | `/shared-only/datasets/llamafactory/pokemon-gpt4o-captions` | llamafactory | 是LlamaFactory整理的宝可梦（口袋妖怪）图文对数据集，图片描述由GPT-4o生成。 |
| mllm_pt_demo | 53KB | `/shared-only/datasets/BUAADreamer/mllm_pt_demo/data/train-00000-of-00001.parquet` | BUAADreamer | 是一个多模态（图文）的预训练演示数据集，帮助模型学习图像和文本之间的关联。 |
| oasst_de | 8MB | `/shared-only/datasets/mayflowergmbh/oasst_de/oasst_de.json` | OpenAssistant | 是OpenAssistant项目的德语对话数据集，由社区众包创建。 |
| dolly_15k_de | 8MB | `/shared-only/datasets/mayflowergmbh/dolly-15k_de/dolly_de.json` | mayflowergmbh | 是德语版的Dolly 15k数据集，包含由人类生成的指令和回答。 |
| alpaca-gpt4_de | 47MB | `/shared-only/datasets/mayflowergmbh/alpaca-gpt4_de/alpaca_gpt4_data_de.json` | mayflowergmbh | 是使用GPT-4生成的德语Alpaca指令数据集。 |
| openschnabeltier_de | 24MB | `/shared-only/datasets/mayflowergmbh/openschnabeltier_de/openschnabeltier.json` | mayflowergmbh | 是一个高质量的德语多任务指令微调数据集。 |
| evol_instruct_de | 148MB | `/shared-only/datasets/mayflowergmbh/evol-instruct_de/evol_instruct_de.json` | mayflowergmbh | 是使用指令进化方法生成的德语复杂指令数据集。 |
| dolphin_de | 120MB | `/shared-only/datasets/mayflowergmbh/dolphin_de/dolphin.json` | mayflowergmbh | 是经过筛选的德语版Dolphin对话数据集。 |
| booksum_de | 201MB | `/shared-only/datasets/mayflowergmbh/booksum_de/booksum.json` | mayflowergmbh | 是用于德语书籍摘要任务的数据集。 |
| airoboros_de | 74MB | `/shared-only/datasets/mayflowergmbh/airoboros-3.0_de/airoboros_3.json` | mayflowergmbh | 是德语版的Airoboros数据集，以其指令的多样性和复杂性著称。 |
| ultrachat_de | 595MB | `/shared-only/datasets/mayflowergmbh/ultra-chat_de/ultra_chat_german.json` | mayflowergmbh | 是德语版的UltraChat多轮对话数据集。 |
| dpo_mix_en | 49MB | `/shared-only/datasets/llamafactory/DPO-En-Zh-20k/dpo_en.json` | llamafactory | 是LlamaFactory整理的2万条中英DPO数据集中的英文部分，用于偏好对齐。 |
| dpo_mix_zh | 28MB | `/shared-only/datasets/llamafactory/DPO-En-Zh-20k/dpo_zh.json` | llamafactory | 是LlamaFactory整理的2万条中英DPO数据集中的中文部分。 |
| ultrafeedback | 188MB | `/shared-only/datasets/llamafactory/ultrafeedback_binarized/train.json` | llamafactory | 是一个大型反馈数据集，包含模型的多种回答和评分，已二元化为“选择”和“拒绝”格式，用于DPO。 |
| coig_p | 766MB | `/shared-only/datasets/m-a-p/COIG-P/data/` | m-a-p | 是一个中文指令偏好数据集，用于训练符合人类偏好的模型。 |
| rlhf_v | 348MB | `/shared-only/datasets/llamafactory/RLHF-V/rlhf-v.parquet` | llamafactory | 是LlamaFactory整理的视觉RLHF（基于人类反馈的强化学习）偏好数据集，包含图片、对话和偏好选择。 |
| vlfeedback | 4.8GB | `/shared-only/datasets/Zhihui/VLFeedback/data/` | Zhihui | 是一个视觉语言偏好数据集，包含多模态对话和人类的偏好选择。 |
| rlaif_v | 13GB | `/shared-only/datasets/openbmb/RLAIF-V-Dataset` | OpenBMB | 是OpenBMB发布的，通过AI模型模拟人类进行反馈标注的视觉偏好数据集。 |
| orca_pairs | 35MB | `/shared-only/datasets/Intel/orca_dpo_pairs/orca_rlhf.jsonl` | Intel | 是由Intel发布的DPO数据集，包含问题、选择的答案和拒绝的答案。 |
| hh_rlhf_en | 162MB | `/shared-only/datasets/shbyun080/hh-rlhf-en/data/` | Anthropic | 是Anthropic发布的著名英文偏好数据集，旨在让模型变得更有益（Helpful）和更无害（Harmless）。 |
| nectar_rm | 2.1GB | `/shared-only/datasets/AstraMindAI/RLAIF-Nectar/rlaif_data_structured.json` | Anthropic | 是由AstraMindAI发布的，用于训练奖励模型（Reward Model）的偏好数据集。 |
| kto_mix_en | 22MB | `/shared-only/datasets/argilla/kto-mix-15k/data/` | Argilla | 是Argilla发布的包含1.5万样本的KTO数据集，用于更细粒度的模型对齐。 |
| ultrafeedback_kto | 216MB | `/shared-only/datasets/argilla/ultrafeedback-binarized-preferences-cleaned-kto/data/` | Argilla | 是从UltraFeedback数据集中清洗并转换为KTO格式的偏好数据集。 |
| wiki_demo | 1.5MB | `/shared-only/datasets/wiki_demo.txt` | llamafactory | 是从维基百科中提取的一小部分纯文本，用作预训练（Pre-training）流程的演示数据。 |
| c4_demo | 730KB | `/shared-only/datasets/c4_demo.jsonl` | llamafactory | 是从大规模网络文本语料库C4中提取的JSONL格式演示数据，用于验证预训练流程。 |
| open_hermes_test_ppl_filtered | 336KB | `/shared-only/datasets/ChineseTinyLLM/open_hermes_test_ppl_filtered.json` | 暂无 | 暂无 |
| haruhi_train | 56MB | `/shared-only/datasets/haruhi/haruhi_train.json` | AlayaNeW | 暂无 |
| haruhi_val | 66MB | `/shared-only/datasets/haruhi/haruhi_val.json` | AlayaNeW | 暂无 |
| alpaca_en_demo | 841K | `/shared-only/datasets/alpaca_en_demo.json` | llamafactory | 暂无 |
| alpaca_zh_demo | 2.4MB | `/shared-only/datasets/alpaca_zh_demo.json` | llamafactory | 暂无 |
| glaive_toolcall_en | 2.4MB | `/shared-only/datasets/llamafactory/glaive_toolcall_en/glaive_toolcall_en_1k.json` | llamafactory | 暂无 |
| glaive_toolcall_zh | 2.4MB | `/shared-only/datasets/llamafactory/glaive_toolcall_zh/glaive_toolcall_zh_1k.json` | llamafactory | 暂无 |
| CNPM_audio_train | 2.1GB | `/shared-only/datasets/cnpm/CNPM_audio_train.json` | cnpm | 暂无 |
| sa-v | 1.1TB | `/shared-only/datasets/sa-v` | meta | 暂无 |
| fin_mme | 6.8MB | `/shared-only/datasets/fin_mme_train.json` | 暂无 | 暂无 |
| ICLR_2024 | 529MB | `/shared-only/datasets/ReviewMT/ICLR_2024.json` | ReviewMT | 暂无 |
| iclr_test_data | 9.1MB | `/shared-only/datasets/ReviewMT/iclr_test_data.json` | ReviewMT | 暂无 |
| D_train_ft_train | 50MB | `/shared-only/datasets/D_train_ft_train.json` | 暂无 | 暂无 |
| mini-StatQA_ft_test | 5MB | `/shared-only/datasets/mini-StatQA_ft_test.json` | 暂无 | 暂无 |
| cbt | 58MB | `/shared-only/datasets/CBT.json` | 暂无 | 暂无 |
| coig_cqia_test_ppl_filtered | 497KB | `/shared-only/datasets/ChineseTinyLLM/coig_cqia_test_ppl_filtered.json` | 暂无 | 暂无 |
| coig_cqia_train_ppl_filtered | 19MB | `/shared-only/datasets/ChineseTinyLLM/coig_cqia_train_ppl_filtered.json` | 暂无 | 暂无 |
| open_hermes_train_ppl_filtered | 5.7MB | `/shared-only/datasets/ChineseTinyLLM/open_hermes_train_ppl_filtered.json` | 暂无 | 暂无 |
| SUdongpo_merged | 24MB | `/shared-only/datasets/SUdongpo_merged.json` | AlayaNeW | 暂无 |
| dpo_zh_mini | 1MB | `/shared-only/datasets/dpo_zh_mini.json` | AlayaNeW | 暂无 |
| kto_mini | 10KB | `/shared-only/datasets/kto_mini.json` | AlayaNeW | 暂无 |
| weclone_air_dialogue-sft | 584MB | `/shared-only/datasets/weclone_air_dialogue-sft.json` | AlayaNeW | 暂无 |
| KnowYourMbti_train_48000 | 337MB | `/market/datasets/lfol/KnowYourMbti_train_48000.json` | lfol | llamafactory online官方MBTI数据集 |
| KnowYourMbti_test_100 | 711KB | `/market/datasets/lfol/KnowYourMbti_test_100.json` | lfol | llamafactory online官方MBTI数据集 |
| belle_0.5m | 286MB | `/shared-only/datasets/BelleGroup/train_0.5M_CN/Belle_open_source_0.5M.jsonl` | BelleGroup | 该数据集是 BelleGroup 推出的中文对话数据集，包含 50 万条生成的中文聊天数据，适用于大语言模型的对话能力训练。 |