# Awesome-Personalized-LLM
This repo aims to record resource of personalized LLMs, including role playing, personalized chat, and personality traits of LLm etc. 

We strongly encourage the researchers that want to promote their fantastic work to the personalized LLM community to make pull request to update their paper's information!

- [Awesome-Personalized-LLM](#awesome-personalized-llm)
  - [Awesome Papers](#awesome-papers)
    - [Role-Playing](#role-playing)
    - [Personalized Chat](#personalized-chat)
    - [Evaluation Personality of LLM](#evaluation-personality-of-llm)
      - [Myers–Briggs Type Indicator (MBTI) Evaluation](#myersbriggs-type-indicator-mbti-evaluation)
      - [Big Five Factors Evaluation](#big-five-factors-evaluation)
      - [Other Personal Evaluation](#other-personal-evaluation)
    - [Benchmark](#benchmark)
  - [Awesome Datasets](#awesome-datasets)
  - [Related Repositories](#related-repositories)


## Awesome Papers

### Role-Playing

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoleInteract: Evaluating the Social Interaction of Role-Playing Agents**](https://arxiv.org/pdf/2403.13679.pdf) | Arxiv24 | 2024-03-21 | [RoleInteract](https://github.com/X-PLUG/RoleInteract) | - |
| [**Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent**](https://arxiv.org/pdf/2402.13717.pdf) | Arxiv24 | 2024-02-21 | [Neeko](https://github.com/weiyifan1023/Neeko) | - |
| [**Large Language Models are Superpositions of All Characters: Attaining Arbitrary Role-play via Self-Alignment**](https://arxiv.org/pdf/2401.12474.pdf) | Arxiv24 | 2024-01-24 | [Ditto](https://github.com/OFA-Sys/Ditto) | - |
| [**CharacterGLM: Customizing Chinese Conversational AI Characters with  Large Language Models**](https://arxiv.org/pdf/2311.16832.pdf) | Arxiv23 | 2023-11-19 | [CharacterGLM-6B](https://github.com/thu-coai/CharacterGLM-6B) | - |
| [**Character-LLM: A Trainable Agent for Role-Playing**](https://arxiv.org/pdf/2310.10158v1.pdf) | EMNLP23 | 2023-10-16 | [trainable-agents](https://github.com/choosewhatulike/trainable-agents) | - |
| [**Large Language Models Meet Harry Potter: A Bilingual Dataset for Aligning Dialogue Agents with Characters**](https://arxiv.org/abs/2211.06869) | EMNLP23 | 2023-10-09 | [HPD](https://nuochenpku.github.io/HPD.github.io/) | - |
| [**NarrativePlay: Interactive Narrative Understanding**](https://arxiv.org/pdf/2310.01459.pdf) | arXiv | 2023-10-02 | - | - |
| [**RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models**](https://arxiv.org/abs/2310.00746) | arXiv | 2023-10-01 | [RoleLLM](https://github.com/InteractiveNLP-Team/RoleLLM-public) | - |
| [**ChatHaruhi: Reviving Anime Character in Reality via Large Language Model**](https://arxiv.org/abs/2308.09597) | arXiv | 2023-08-18 | [ChatHaruhi](https://github.com/LC1332/Chat-Haruhi-Suzumiya) | [ChatHaruhi-OpenAI](https://huggingface.co/spaces/chengli-thu/ChatHaruhi-OpenAI) |
| [**Thespian: Multi-Character Text Role-Playing Game Agents**](https://arxiv.org/pdf/2308.01872.pdf) | arXiv | 2023-08-03 | - | - |
| [**Role-Play with Large Language Models**](https://arxiv.org/abs/2305.16367) | arXiv | 2023-05-25 | - | - |
| [**Ontologically Faithful Generation of Non-Player Character Dialogues**](https://arxiv.org/abs/2212.10618) | arXiv | 2023-05-13 | - | - |


### Personalized Chat

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**ControlLM: Crafting Diverse Personalities for Language Models**](https://arxiv.org/pdf/2402.10151.pdf) | Arxiv | 2024-02-15 | [ControlLM](https://github.com/wengsyx/ControlLM) | - |
| [**Tailoring Personality Traits in Large Language Models via Unsupervisedly-Built Personalized Lexicons**](https://arxiv.org/pdf/2310.16582.pdf) | Arxiv | 2023-10-25 | - | - |
| [**Personalized Soups: Personalized Large Language Model Alignment via Post-hoc Parameter Merging**](https://arxiv.org/pdf/2310.11564.pdf) | Arxiv | 2023-10-17 | [RLPHF](https://github.com/joeljang/rlphf) | - |
| [**Large Language Models as Source Planner for Personalized Knowledge-grounded Dialogues**](https://arxiv.org/pdf/2310.08840.pdf) | Arxiv | 2023-10-15 | - | - |
| [**CharacterChat：Learning towards Conversational AI with Personalized Social Support**](https://arxiv.org/pdf/2308.10278.pdf) | arXiv | 2023-08-20 | [CharacterChat](https://github.com/morecry/CharacterChat) | - |
| [**Teach LLMs to Personalize – An Approach inspired by Writing Education**](https://arxiv.org/pdf/2308.07968.pdf) | Arxiv | 2023-08-15 | - | - |
| [**A Survey of Challenges and Methods in the Computational Modeling of Multi-Party Dialog**](https://aclanthology.org/2023.nlp4convai-1.12.pdf) | NLP4ConvAI23 | 2023-07-14 | - | - |
| [**Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models**](https://arxiv.org/pdf/2304.13835.pdf) | Arxiv | 2023-06-08 | [MultiLIGHT](https://github.com/facebookresearch/LIGHT/tree/main/light/modeling/tasks/multilight) | - |
| [**Hi Sheldon! Creating Deep Personalized Characters from TV Shows**](https://arxiv.org/pdf/2304.11093.pdf) | arXiv | 2023-04-09 | [Deep-Personalized-Character-Dataset-DPCD](https://github.com/Metaverse-AI-Lab-THU/Deep-Personalized-Character-Dataset-DPCD) | - |
| [**Role Specified Open-Domain Dialogue dataset generated by leveraging LLMs**](https://aclanthology.org/2022.naacl-main.155.pdf) | NAACL22 | 2022-04-30 | [CareCall for Seniors](https://github.com/naver-ai/carecall-corpus) | - |


### Evaluation Personality of LLM

#### Myers–Briggs Type Indicator (MBTI) Evaluation

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Does Role-Playing Chatbots Capture the Character Personalities? Assessing Personality Traits for Role-Playing Chatbots**](https://arxiv.org/abs/2310.17976) | Arxiv23 | 2023-10-27 | [Chat-Haruhi-Suzumiya](https://github.com/LC1332/Chat-Haruhi-Suzumiya) | - |
| [**Can ChatGPT Assess Human Personalities? A General Evaluation Framework**](https://arxiv.org/pdf/2303.01248.pdf) | EMNLP23 | 2023-10-13 | [ChatGPT-MBTI](https://github.com/Kali-Hac/ChatGPT-MBTI) | - |
| [**Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models**](https://arxiv.org/abs/2307.16180) | Arxiv | 2023-07-30 | [LLMs-MBTI](https://github.com/HarderThenHarder/transformers_tasks/tree/main/LLM/llms_mbti) | - |

#### Big Five Factors Evaluation

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Evaluating and Inducing Personality in Pre-trained Language Models**](https://arxiv.org/abs/2206.07550) | NeurIPS23 | 2023-05-24 | - | - |
| [**Estimating the Personality of White-Box Language Models**](https://arxiv.org/pdf/2204.12000.pdf) | Arxiv | 2023-05-10 | - | - |
| [**Identifying and Manipulating the Personality Traits of Language Models**](https://arxiv.org/abs/2212.10276) | Arxiv | 2022-12-20 | - | - |

#### Other Personal Evaluation

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Do personality tests generalize to Large Language Models?**](https://arxiv.org/pdf/2311.05297) | NeurIPS23-Workshop | 2023-11-10 | - | - |
| [**The Turing Quest: Can Transformers Make Good NPCs?**](https://aclanthology.org/2023.acl-srw.17.pdf) | ACL23-Workshop | 2023-07-10 | [NPC-Dialogue-Generation](https://github.com/FieryAced/-NPC-Dialogue-Generation) | - |
| [**Have Large Language Models Developed a Personality?: Applicability of Self-Assessment Tests in Measuring Personality in LLMs**](https://arxiv.org/abs/2305.14693) | Arxiv | 2023-05-24 | - | - |
| [**Who is GPT-3? An Exploration of Personality, Values and Demographics**](https://arxiv.org/abs/2209.14338) | Arxiv | 2022-12-26 | - | - |

### Benchmark

|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**CharacterEval: A Chinese Benchmark for Role-Playing Conversational Agent Evaluation**](https://arxiv.org/abs/2401.01275) | Arxiv24 | 2024-01-02 | [CharacterEval](https://github.com/morecry/CharacterEval) | - |
| [**RoleEval: A Bilingual Role Evaluation Benchmark for Large Language Models**](https://arxiv.org/abs/2312.16132) | Arxiv23 | 2023-12-12 | [RoleEval](https://github.com/Magnetic2014/RoleEval) | - |
| [**LaMP: When Large Language Models Meet Personalization**](https://arxiv.org/pdf/2304.11406.pdf) | Arxiv23 | 2023-05-19 | - | - |

## Awesome Datasets

- [GPTeacher/Roleplay](https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/GPTeacher/Roleplay)
- [BelleGroup/Generated_Chat_0.4M](https://huggingface.co/datasets/BelleGroup/generated_chat_0.4M)
- [CharacterChat](https://drive.google.com/drive/folders/1n5UlZ4vm3bSBZv6c4kIvIQJHFrSZgON3)
- [Deep-Personalized-Character-Dataset-DPCD](https://github.com/Metaverse-AI-Lab-THU/Deep-Personalized-Character-Dataset-DPCD)
- [Harry Potter Dialogue](https://nuochenpku.github.io/HPD.github.io/download)
- [carecall-corpus (Korean)](https://github.com/naver-ai/carecall-corpus)
- [RoleBech](https://huggingface.co/datasets/ZenMoore/RoleBench/tree/main)

## Related Repositories

- [Paper reading list in dialogue systems](https://github.com/iwangjian/Paper-Reading#personalized-dialogue)
- [LLM and Society](https://github.com/penguinnnnn/awesome-llm-and-society)
- [Persona Paper](https://github.com/Sahandfer/PersonaPaper)
