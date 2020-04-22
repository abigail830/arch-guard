---
layout: single
title: 评估策略
sidebar:
  nav: "models"
permalink: /models/evaluate-strategic/
toc: true
---

## 业务导向架构评估

### 指定评估策略的原则
> 聚焦业务价值最大方向，快速定向智能评估，务求架构决策更客观，投资更精准
{: .notice--info}

### 相关参考
* [The Elephant in the Architecture](https://martinfowler.com/articles/value-architectural-attribute.html)
* [为什么要从业务价值导向架构决策？](https://zhuanlan.zhihu.com/p/111293116)

### 评估阶段常见痛点
* 没有人能说清目前的业务和架构是怎样的、为什么这样
* 业务复杂、架构混乱，靠人力评估的话对能力要求太高了
* 没有统一的业务术语和架构表示方法，因而难以沟通
* 从组织级层面看，系统太多，如何能规模化综合评估？
* 评估出了改进项，但难以排定改造的优先级

## 策略模型

### 市场响应力评估模型
> 市场响应力：当市场发生改变时，现有业务为了能够适应市场，业务作出反应的能力
{: .notice--info}

#### 适配场景
- 系统收集不到业务反馈，不知道业务该怎么走
- 每次新增功能都需要3，5个月才能上线，跟不上竞品更新速度

#### 评估维度

![市场响应力评估模型](/arch-guard/assets/images/market.png)

### 质量评估模型
> 质量：业务上线后，该业务是否能满足客户期望，有多少严重Bug
{: .notice--info}

#### 适配场景
- 测试返修率高，总是反复测试才能上线
- 经常出现上线失败，需要紧急修复
- 客户经常投诉，页面错乱，业务出错

#### 评估维度

![质量评估模型](/arch-guard/assets/images/quality.png)

### 可用性评估模型
> 可用性：业务不稳定，访问出错
{: .notice--info}

#### 适配场景
- 上线无法实现零停机时间
- 经常接到客户投诉，页面打不开了，连接错误

#### 评估维度

![可用性评估模型](/arch-guard/assets/images/reliability.png)

### 开放性评估模型
> 开放性：当出现出现创新性业务时，原有系统能不能很好的支撑
{: .notice--info}

#### 适配场景
- 新增线上渠道，系统需要花很长时间改造才能支持新渠道
- 给其他系统提供API，需要花很长时间开发接口

#### 评估维度

![开放性评估模型](/arch-guard/assets/images/openable.png)
