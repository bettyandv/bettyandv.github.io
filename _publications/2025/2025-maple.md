---
title:          "MAPLE: Multi-Agent Adaptive Planning with Long-Term Memory for Table Reasoning"
# title_zh:       "DivScore: 专业领域中大语言模型生成文本的零样本检测"
date:           2025-11-26 00:01:00 +0800
selected:       true
pub:            "The 23rd Annual Workshop of the Australasian Language Technology Association (ALTA 2025)"
# pub_zh:         "自然语言处理实证方法会议 (EMNLP)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Main Conference</span>'
# pub_last_zh:    ' <span class="badge badge-pill badge-publication badge-success">主会议</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776
abstract: >-
  Table-based question answering requires complex reasoning capabilities that current LLMs struggle to achieve with single-pass inference. Existing approaches, such as Chain-of-Thought reasoning and question decomposition, lack error detection mechanisms and discard problem-solving experiences, contrasting sharply with how humans tackle such problems. In this paper, we propose MAPLE (Multi-agent Adaptive Planning with Long-term mEmory), a novel framework that mimics human problem-solving through specialized cognitive agents working in a feedback-driven loop. MAPLE integrates 4 key components: (1) a Solver using the ReAct paradigm for reasoning, (2) a Checker for answer verification, (3) a Reflector for error diagnosis and strategy correction, and (4) an Archiver managing long-term memory for experience reuse and evolution. Experiments on WiKiTQ and TabFact demonstrate significant improvements over existing methods, achieving state-of-the-art performance across multiple LLM backbones.
# abstract_zh: >-
#   在医学和法律等专业高风险领域检测大语言模型生成的文本对于打击错误信息和确保真实性至关重要。我们提出了DivScore，一个使用归一化熵评分和领域知识蒸馏的零样本检测框架，能够稳健地识别专业领域中的大语言模型生成文本。实验表明，DivScore始终优于最先进的检测器，AUROC提高14.4%，在0.1%误报率阈值下召回率提高64.0%。
cover:          /assets/images/covers/maple_overview.png
authors:
  - Ye Bai
  - Minghan Wang
  - Thuy-Trang Vu
links:
  Paper: https://aclanthology.org/2025.alta-main.10/
  Code: https://github.com/bettyandv/MAPLE-table-reasoning
  # Project Page: /publications/divscore.html
# links_zh:
#   论文: https://aclanthology.org/2025.emnlp-main.971/
#   代码: https://github.com/richardChenzhihui/DivScore
#   项目页面: /publications/divscore.html
---

