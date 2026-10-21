# Mapeamento Sistemático de Literatura

Este repositório lista os 75 estudos incluídos no Mapeamento Sistemático de Literatura (MSL) apresentado no Capítulo 3 da minha dissertação de mestrado. Os códigos E01 a E75 são os mesmos usados na dissertação.

## Resumo do protocolo

- **Bases:** IEEE Xplore, arXiv e SpringerLink (apenas artigos de acesso aberto, publicados entre 2022 e 2026; no SpringerLink, filtro por ciência da computação e educação).
- **Data da busca:** março de 2026.
- **String de busca:**

```
(LLM* OR "Large Language Model*" OR GenAI OR "Generative AI" OR "foundation model*") AND ("evaluation metrics" OR "quality metrics" OR "assessment framework" OR benchmark) AND ("human-in-the-loop" OR HITL OR "human evaluation" OR "human feedback" OR RLHF OR "LLM-as-a-judge" OR RAGAS OR DeepEval) AND (education OR "AI in education" OR "educational technology" OR EdTech)
```

- **Critérios de inclusão:**
  - CI1: estudos que abordam sistemas de IA generativa, especialmente LLMs;
  - CI2: estudos que apresentam ou utilizam métodos, métricas, *benchmarks*, rubricas ou outras formas de avaliação da qualidade do conteúdo gerado, incluindo abordagens automáticas e/ou baseadas em avaliação humana.
- **Critérios de exclusão:**
  - CE1: estudos que não utilizam IA generativa nem LLMs;
  - CE2: estudos que não abordam a avaliação da qualidade do conteúdo gerado;
  - CE3: estudos que apenas mencionam o uso de IA, sem detalhar os métodos de avaliação;
  - CE4: estudos que não apresentam nenhuma forma de avaliação, seja automática ou humana.
- **Critério de classificação:**
  - CC1: estudos aplicados ao contexto educacional (coluna "Educacional").

## Fluxo de seleção

| Etapa | Estudos |
|---|---|
| Identificados nas bases | 187 (IEEE Xplore 2, arXiv 30, SpringerLink 155) |
| Duplicados removidos | 1 |
| Triados | 186 |
| Excluídos (CE1 a CE4) | 111 |
| **Incluídos** | **75** (IEEE Xplore 1, arXiv 24, SpringerLink 50) |
| Aplicados ao contexto educacional (CC1) | 36 (IEEE Xplore 1, arXiv 16, SpringerLink 19) |
| Contextos gerais ou técnicos | 39 |

## Estudos incluídos

Os estudos estão ordenados por base. Quando há mais de três autores, a lista mostra os três primeiros seguidos de "et al.". As letras "a" e "b" no ano diferenciam estudos com o mesmo primeiro autor e o mesmo ano.

| Código | Autores | Ano | Título | Base | Educacional |
|---|---|---|---|---|---|
| E01 | Christopher C. Y. Yang; Guan-Jie Liu; Cheng-Jui Yu | 2025 | Optimizing RAG in Programming Education: A Comparative Study of Models and Strategies | IEEE Xplore | Sim |
| E02 | Zhuqian Zhou; Kirk Vanacore; Bakhtawar Ahtisham; et al. | 2026 | Utility-Preserving De-Identification for Math Tutoring: Investigating Numeric Ambiguity in the MathEd-PII Benchmark Dataset | arXiv | Sim |
| E03 | Abdellah El Mekki; Samar M. Magdy; Houdaifa Atou; et al. | 2026 | Alexandria: A Multi-Domain Dialectal Arabic Machine Translation Dataset for Culturally Inclusive and Linguistically Diverse LLMs | arXiv | Não |
| E04 | Alexander Scarlatos; Jaewook Lee; Simon Woodhead; et al. | 2026 | Simulated Students in Tutoring Dialogues: Substance or Illusion? | arXiv | Sim |
| E05 | Zihao Wang; Ruibin Yuan; Ziqi Geng; et al. | 2025 | Singing Timbre Popularity Assessment Based on Multimodal Large Foundation Model | arXiv | Não |
| E06 | Pooja Singh; Sandeep Kumar | 2026 | AdiBhashaa: A Community-Curated Benchmark for Machine Translation into Indian Tribal Languages | arXiv | Não |
| E07 | Yefeng Wu; Yuchen Song; Yecheng Zhao; et al. | 2025 | CogEvo-Edu: Cognitive Evolution Educational Multi-Agent Collaborative System | arXiv | Sim |
| E08 | Wendkûuni C. Ouédraogo; Yinghua Li; Xueqi Dang; et al. | 2025 | Human-Aligned Code Readability Assessment with Large Language Models | arXiv | Não |
| E09 | Marwa Abdulhai; Ryan Cheng; Aryansh Shrivastava; et al. | 2025 | Evaluating & Reducing Deceptive Dialogue from Language Models with Multi-Turn RL | arXiv | Não |
| E10 | Hyunji Nam; Lucia Langlois; James Malamut; et al. | 2025 | IDEAlign: Comparing Large Language Models to Human Experts in Open-ended Interpretive Annotations | arXiv | Sim |
| E11 | Shou’ang Wei; Xinyun Wang; Shuzhen Bi; et al. | 2025 | ELMES: An Automated Framework for Evaluating Large Language Models in Educational Scenarios | arXiv | Sim |
| E12 | Jiaju Chen; Yuxuan Lu; Xiaojie Wang; et al. | 2025a | Multi-Agent-as-Judge: Aligning LLM-Agent-Based Automated Evaluation with Multi-Dimensional Human Evaluation | arXiv | Sim |
| E13 | Jiamin Su; Yibo Yan; Fangteng Fu; et al. | 2025 | EssayJudge: A Multi-Granular Benchmark for Assessing Automated Essay Scoring Capabilities of Multimodal Large Language Models | arXiv | Sim |
| E14 | Jialiang Chen; Kaifa Zhao; Jie Liu; et al. | 2025b | CoReQA: Uncovering Potentials of Language Models in Code Repository Question Answering | arXiv | Não |
| E15 | Yibo Yan; Shen Wang; Jiahao Huo; et al. | 2024 | ERRORRADAR: Benchmarking Complex Mathematical Reasoning of Multimodal Large Language Models via Error Detection | arXiv | Sim |
| E16 | Zonghai Yao; Zihao Zhang; Chaolong Tang; et al. | 2026 | MedQA-CS: Objective Structured Clinical Examination (OSCE)-Style Benchmark for Evaluating LLM Clinical Skills | arXiv | Não |
| E17 | Anindita Kundu; Denilson Barbosa | 2024 | Are Large Language Models Good Essay Graders? | arXiv | Sim |
| E18 | Irina Jurenka; Markus Kunesch; Kevin R. McKee; et al. | 2025 | Towards Responsible Development of Generative AI for Education: An Evaluation-Driven Approach | arXiv | Sim |
| E19 | Rui Yang; Boming Yang; Sixun Ouyang; et al. | 2024a | Graphusion: Leveraging Large Language Models for Scientific Knowledge Graph Fusion and Construction in NLP Education | arXiv | Sim |
| E20 | Steven Moore; Eamon Costello; Huy A. Nguyen; et al. | 2024 | An Automatic Question Usability Evaluation Toolkit | arXiv | Sim |
| E21 | Rui Yang; Boming Yang; Sixun Ouyang; et al. | 2024b | Leveraging Large Language Models for Concept Graph Recovery and Question Answering in NLP Education | arXiv | Sim |
| E22 | Aysa Xuemo Fan; Ranran Haoran Zhang; Luc Paquette; et al. | 2023 | Exploring the Potential of Large Language Models in Generating Code-Tracing Questions for Introductory Programming Courses | arXiv | Sim |
| E23 | Anaïs Tack; Ekaterina Kochmar; Zheng Yuan; et al. | 2023 | The BEA 2023 Shared Task on Generating AI Teacher Responses in Educational Dialogues | arXiv | Sim |
| E24 | Ziang Xiao; Susu Zhang; Vivian Lai; et al. | 2023 | Evaluating Evaluation Metrics: A Framework for Analyzing NLG Evaluation Metrics using Measurement Theory | arXiv | Não |
| E25 | Jiazheng Li; Lin Gui; Yuxiang Zhou; et al. | 2023 | Distilling ChatGPT for Explainable Automated Student Answer Assessment | arXiv | Sim |
| E26 | Margit Antal; Krisztian Buza | 2025 | Evaluating Open-Source LLMs in RAG Systems: A Benchmark on Diploma Theses Abstracts Using Ragas | SpringerLink | Não |
| E27 | Ting Zhang; Luke Patterson; Blue Webb; et al. | 2026 | Evaluating generative AI chatbots for large-scale assessment data: comparing LLM-as-a-judge and human ratings | SpringerLink | Sim |
| E28 | Riccardo Cantini; Alessio Orsino; Massimo Ruggiero; et al. | 2025 | Benchmarking adversarial robustness to bias elicitation in large language models: scalable automated assessment with LLM-as-a-judge | SpringerLink | Não |
| E29 | Mohammadreza Farrokhnia; Saeed Latifi; Pantelis M. Papadopoulos; et al. | 2026 | Generative AI offers more, but students revise less: comparing the effects of teacher and AI feedback on student essay revisions | SpringerLink | Sim |
| E30 | Nurit Novis-Deutsch; Tal Elyoseph; Zohar Elyoseph | 2025 | How much of a pluralist is ChatGPT? A comparative study of value pluralism in generative AI chatbots | SpringerLink | Não |
| E31 | Rebecca Johnson; Leslye Denisse Dias Duran; Enrico Panai; et al. | 2026 | The ghost in the machine speaks with an American accent: cultural value drift in early GPT-3 and the case for pluralist evaluation of generative AI | SpringerLink | Não |
| E32 | Uyen N. Le-Khac; Vinh N. X. Truong | 2025 | A survey on large language models unlearning: taxonomy, evaluations, and future directions | SpringerLink | Não |
| E33 | Karima Bouziane; Abdelmounim Bouziane | 2024 | AI versus human effectiveness in essay evaluation | SpringerLink | Sim |
| E34 | Marina Jovic; Stavros Papakonstantinidis; Robert Kirkpatrick | 2025 | From red ink to algorithms: investigating the use of large language models in academic writing feedback | SpringerLink | Sim |
| E35 | Julia Pargmann; Florian Berding; Karin Rebmann; et al. | 2025 | How AI feedback supports lesson planning in vocational teacher education: a longitudinal intervention study using an analytical AI platform | SpringerLink | Sim |
| E36 | Praveen Prasannan; Prasanna Kumar Kumaresan; Saranya Rajiakodi; et al. | 2025 | Counter-speech generation for homophobic and transphobic social media content in Malayalam | SpringerLink | Não |
| E37 | Md Abul Bashar; Richi Nayak | 2025 | Chatting with organisational data: a generative AI approach applied to scientific reports for information seeking | SpringerLink | Não |
| E38 | Michael J. Parker; Caitlin Anderson; Claire Stone; et al. | 2024 | A Large Language Model Approach to Educational Survey Feedback Analysis | SpringerLink | Sim |
| E39 | Suna-Şeyma Uçar; Iñigo Lopez-Gazpio; Josu Lopez-Gazpio | 2025 | Evaluating and challenging the reasoning capabilities of generative artificial intelligence for technology-assisted chemistry education | SpringerLink | Sim |
| E40 | Fatih Demir; Uğur Yavuz | 2026 | Evaluating the performance of generative artificial intelligence models in multidimensional data analysis tasks: a comparative study with large language models | SpringerLink | Não |
| E41 | Silvia García-Méndez; Francisco de Arriba-Pérez; María del Carmen Somoza-López | 2024 | A Review on the Use of Large Language Models as Virtual Tutors | SpringerLink | Sim |
| E42 | Tiago Conceição; Nuno Cruz | 2025 | Evaluation of the maturity of LLMs in the cybersecurity domain | SpringerLink | Não |
| E43 | Li Bowen; Zhong Zhuoqing; Zhang Hengyu; et al. | 2025 | Improving negative rejection ability in language models: A review of fine-tuned LLMs, RAG, and RAFT | SpringerLink | Não |
| E44 | Keerthana Sivamayilvelan; Elakkiya Rajasekar; Subramaniyaswamy Vairavasundaram; et al. | 2026 | Building an effective chatbot for optimizing the debt collection process through large language models | SpringerLink | Não |
| E45 | Mohamad Saleh Torkestani; Ali Alameer; Shivakumara Palaiahnakote; et al. | 2025 | Inclusive prompt engineering for large language models: a modular framework for ethical, structured, and adaptive AI | SpringerLink | Não |
| E46 | Weikai Xu; Chengrui Huang; Shen Gao; et al. | 2025 | LLM-Based Agents for Tool Learning: A Survey | SpringerLink | Não |
| E47 | Donggeun Park; Hyeonbin Moon; Seunghwa Ryu | 2026 | A self-correcting multi-agent LLM framework for language-based physics simulation and explanation | SpringerLink | Não |
| E48 | Liqaa Habeb Al-Obaydi; Marcel Pikhart | 2025 | AI partner versus human partner: comparing AI-based peer assessment with human-generated peer assessment in examining writing skills | SpringerLink | Sim |
| E49 | Muhammad Tanveer Jan; Mohammed G. Al-Jassani; Martinraj Nadar; et al. | 2025 | Text-to-video generators: a comprehensive survey | SpringerLink | Não |
| E50 | Michele Braccini; Gianluca Aguzzi; Paolo Baldini | 2026 | Unraveling Creativity Through Variability: A Comparison of LLMs and Humans in an Educational Q&A Scenario | SpringerLink | Sim |
| E51 | Xiaowei Huang; Wenjie Ruan; Wei Huang; et al. | 2024 | A survey of safety and trustworthiness of large language models through the lens of verification and validation | SpringerLink | Não |
| E52 | Jennifer M Reddig; Arav Arora; Christopher J. MacLellan | 2025 | Generating In-Context, Personalized Feedback for Intelligent Tutors with Large Language Models | SpringerLink | Sim |
| E53 | Hanshu Rao; Weisi Liu; Haohan Wang; et al. | 2026 | A Scoping Review of Synthetic Data Generation by Language Models in Biomedical Research and Application: Data Utility and Quality Perspectives | SpringerLink | Não |
| E54 | Kyung Ho Lim; Ujin Kang; Xiang Li; et al. | 2025 | Susceptibility of Large Language Models to User-Driven Factors in Medical Queries | SpringerLink | Não |
| E55 | Andreas Happe; Aaron Kaplan; Jürgen Cito | 2026 | LLMs as Hackers: Autonomous Linux Privilege Escalation Attacks | SpringerLink | Não |
| E56 | Sascha Schweitzer; Markus Conrads | 2024 | The digital transformation of jurisprudence: an evaluation of ChatGPT-4’s applicability to solve cases in business law | SpringerLink | Não |
| E57 | Yunpu Zhao; Rui Zhang; Wenyi Li; et al. | 2025 | Assessing and Understanding Creativity in Large Language Models | SpringerLink | Não |
| E58 | Youngmin Ji; Inho Lee; Yunsick Sung | 2026 | Keyword-Centered Rescheduling for LLM Agents | SpringerLink | Não |
| E59 | HyoJe Jung; Yunha Kim; Jiahn Seo; et al. | 2025 | Clinical Assessment of Fine-Tuned Open-Source LLMs in Cardiology: From Progress Notes to Discharge Summary | SpringerLink | Não |
| E60 | Subhey Sadi Rahman; Md. Adnanul Islam; Md. Mahbub Alam; et al. | 2026 | Hallucination to truth: a review of fact-checking and factuality evaluation in large language models | SpringerLink | Não |
| E61 | Dandan Wang; Shiqing Zhang | 2024 | Large language models in medical and healthcare fields: applications, advances, and challenges | SpringerLink | Não |
| E62 | Shaun Ramlogan; Vidya Raman; Shayn Ramlogan | 2025 | A pilot study of the performance of Chat GPT and other large language models on a written final year periodontology exam | SpringerLink | Sim |
| E63 | Ana Pastor-Merino; Xavier Martínez-Barbero; Josep Domenech | 2025 | Detecting AI adoption at scale: a web mining and LLM methodology | SpringerLink | Não |
| E64 | Akshi Kumar; Dipika Jain | 2024 | EmoMBTI-Net: introducing and leveraging a novel emoji dataset for personality profiling with large language models | SpringerLink | Não |
| E65 | Wenyu Ning; Shaotao Shi; Yuchen Yin; et al. | 2025 | Intent-aware personalized summarization for educational texts with large language models | SpringerLink | Sim |
| E66 | Abigail Gurin Schleifer; Beata Beigman Klebanov; Giora Alexandron | 2025 | Uncovering Measurement Biases in LLM Embedding Spaces: The Anna Karenina Principle and Its Implications for Automated Feedback | SpringerLink | Sim |
| E67 | Huixin Gao; Harwati Hashim; Melor Md Yunus | 2025 | Assessing the reliability and relevance of DeepSeek in EFL writing evaluation: a generalizability theory approach | SpringerLink | Sim |
| E68 | Yeawon Lee; Chia-Hsuan Chang; Christopher C. Yang | 2025 | Enhancing Patient-Physician Communication: Simulating African American Vernacular English in Medical Diagnostics with Large Language Models | SpringerLink | Não |
| E69 | Zhedong Lin; Zhongsheng Wang; Qian Liu; et al. | 2026 | Narratology meets text-to-image: a survey of consistency in AI generated storybook illustrations | SpringerLink | Não |
| E70 | Fernando R. Altermatt; Andres Neyem; Nicolás I. Sumonte; et al. | 2025 | Evaluating GPT-4o in high-stakes medical assessments: performance and error analysis on a Chilean anesthesiology exam | SpringerLink | Sim |
| E71 | Cyril Picard; Kristen M. Edwards; Anna C. Doris; et al. | 2025 | From concept to manufacturing: evaluating vision-language models for engineering design | SpringerLink | Não |
| E72 | Ömer Alperen Gürses; İsmail Ceylan | 2026 | Consistency over accuracy: run-to-run stability of contemporary large language models on Turkish curriculum-aligned theoretical anatomy multiple-choice questions | SpringerLink | Sim |
| E73 | Ji Yoon Jung; Lillian Tyack; Matthias von Davier | 2024 | Combining machine translation and automated scoring in international large-scale assessments | SpringerLink | Sim |
| E74 | Siva Sankari Sivakaminathan; Elena Musi | 2025 | ChatGPT is a gender bias echo-chamber in HR recruitment: an NLP analysis and framework to uncover the language roots of bias | SpringerLink | Não |
| E75 | Arwa Al Saqaabi; Craig Stewart; Eleni Akrida; et al. | 2025 | A Deep Learning Approach for Paragraph-Level Paraphrase Generation for Plagiarism Detection | SpringerLink | Sim |
