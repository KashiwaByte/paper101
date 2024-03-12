

- [动词- 动词](#动词--动词)
- [形容词](#形容词)
- [名词](#名词)
- [衔接词](#衔接词)
  - [图像显示](#图像显示)
  - [相反](#相反)
  - [之前的工作](#之前的工作)
  - [我们提出方法](#我们提出方法)
  - [做实验](#做实验)
  - [在这一段](#在这一段)
  - [接下来介绍细节](#接下来介绍细节)
  - [数据集](#数据集)
  - [Baseline](#baseline)
  - [评估指标](#评估指标)
  - [引用baselines结果](#引用baselines结果)
  - [实验结果表明](#实验结果表明)
  - [消融实验](#消融实验)

# 动词- [动词](#动词)
To address these issues（解决）

These issues largely **diminish** the performance and  trustworthiness of LLMs （降低）

  
planning optimization, which **distills** the knowledge from KGs into LLMs to generate faithful  
relation paths as plans;（提炼）

where E and R **denote** the set of entities and relations, **respectively**.（各自代表）

By treating relation paths as plans, we can make sure the plans **are grounded by** KGs（基于）

Can the planning module of RoG **be integrated with** other LLMs to improve their  performance?（融为一体）

In this paper, we propose a novel method called reasoning on graphs (RoG) that *synergizes* LLMs  with KGs to conduct faithful and interpretable reasoning.（统筹）

we can  find that ChatGPT+CoT *suffers* from the lack of knowledge issue（遭受）



To **tackle** the issues,（解决）

To further **unleash** LLMs’ reasoning ability （释放）

To  **utilize** the instruction-following ability of LLMs（利用）




# 形容词
What’s especially **striking** is their ability to handle complex tasks （突破性的）

DECAF (Yu et al., 2022a) combines semantic  parsing and LLMs reasoning to jointly generate answers, which also reach **salient** performance on  KGQA tasks （突出的）
# 名词


To address the issues of hallucinations and  lack of knowledge, we present a planning-retrieval-reasoning **framework**  （框架）

**plan-and-solve paradigm** （范例）

Moreover, the planning module of RoG  can be **plug-and-play** with different LLMs during inference to improve their performance.  （即插即用）


We also evaluate the *transferability* of RoG to other KGs. （迁移性）
# 衔接词
## 图像显示
as shown in Figure


## 相反
On the contrary, RoG can generate faithful relation paths and retrieve valid reasoning paths from  KGs for reasoning.

## 之前的工作
Previous works that jointly use KGs and LLMs for  KGQA reasoning can be broadly divided into two categories:

## 我们提出方法
In this paper, we propose a novel method called reasoning on graphs (RoG) that synergizes LLMs  with KGs to conduct faithful and interpretable reasoning.

## 做实验
We conduct extensive experiments on two benchmark KGQA datasets,  and the results demonstrate that RoG achieves state-of-the-art performance on KG reasoning tasks

## 在这一段
In this section, we introduce our method: reasoning on graphs (RoG).


## 接下来介绍细节
We will  discuss the implementation details of these two tasks in the following subsections.  


## 数据集
We evaluate the reasoning ability of RoG on two benchmark KGQA datasets:


## Baseline
We compare RoG with 21 baselines grouping into 5 categories: 1) Embedding-  
based methods, 2) Retrieval-augmented methods, 3) Semantic parsing methods, 4) LLMs, and 5)  LLMs+KGs methods. The details of each baseline are described in Appendix A.4


## 评估指标
Following previous works, we use Hits@1 and F1 as the evaluation metrics

## 引用baselines结果
 Since UniKGQA  (Jiang et al., 2022) and DECAF (Yu et al., 2022a) are state-of-the-art methods, we directly refer their  results and those of the other baselines reported in their papers for comparison


## 实验结果表明
From the results, it is evident that


## 消融实验
We conduct an ablation study to analyze the effectiveness of the planning module  
and reasoning module in our method (RoG). We compare four variant


