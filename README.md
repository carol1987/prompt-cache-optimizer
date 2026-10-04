# prompt-cache-optimizer

对话缓存优化器 Skill（Agent 行为准则）。

## 简介

用于最大化对话前缀缓存命中率、降低积分（token）消耗的 Agent 行为准则。适用于长对话、连续追问、大上下文任务，或当上下文过长、积分消耗过快、需要压缩对话或继续上次任务时。

覆盖四类开销：

- 长对话历史累积
- 大文件与检索结果
- 工具调用轮次过多
- 重复解释背景

## 内容

本仓库包含该 Skill 的打包安装文件：

- `prompt-cache-optimizer.zip` — 完整 Skill 安装包

## 安装方式

将 `prompt-cache-optimizer.zip` 解压到 TeleAgent 的 skills 目录（或按对应平台的 Skill 安装流程导入即可）。