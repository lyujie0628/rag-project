# rag-project
A RAG-based QA system with multi-query and structured reasoning
# RAG QA System

## 项目简介
这是一个基于 Dify 搭建的 RAG（检索增强生成）问答系统，用于在自建文献库中进行信息检索和回答。

## 项目目标
相比直接使用大模型，本系统通过引入检索与结构化流程，使回答在信息来源、结构表达和边界控制上更加可控。

## 核心流程
- 用户输入问题
- 问题分类（compare / describe / direct）
- 多路检索（multi-query）
- 根据问题类型进入不同处理逻辑
- 最终生成结构化回答

## 我的主要工作
- 设计问题分类逻辑（不同问题走不同流程）
- 搭建多路检索机制，提升信息召回率
- 优化 compare / describe / direct 三类问题的回答结构
- 引入可解释拒答机制，减少幻觉问题
- 多次基于 bad case 进行流程迭代优化

## 项目文件说明
- `私域科研文献检索.yml`：Dify 导出的工作流配置
- <img width="1195" height="395" alt="image" src="https://github.com/user-attachments/assets/9f790597-b06f-4fc1-9c1c-e56dba180011" />


## 项目说明
本项目基于 Dify 平台实现，重点体现我在 RAG 系统结构设计、流程拆解与优化方面的能力，而非底层模型开发。
