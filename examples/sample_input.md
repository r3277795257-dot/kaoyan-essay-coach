# 示例：一次典型提交

第一次使用时，Skill 会先问你三个问题。你按下面这样回答即可；之后把作文直接粘贴发来。

---

## 第一次（建档）

> **你（直接发）：**
>
> 帮我批改考研英语作文。考英语二，目标小作文 8 分，目标院校在湖南（湖南大学国际商务）。

Skill 会确认：好，信息记下了，请把作文题目和你的作文发我。

## 提交作文

> **你（直接发）：**
>
> 【2010 英二 Part A 47 题】
> You have just come back from the U.S. as a member of a Sino-American cultural exchange program. Write a letter to your American colleague to:
> 1) express your thanks for his/her warm reception;
> 2) welcome him/her to visit China in due course.
> Write about 100 words. Do not sign your own name; use "Zhang Wei".
>
> 【我的作文】
> Dear Ally,
> With time going by, I have come back from the U.S one month. Everytime I recall the exchange life in the U.S, Your image float into my brain. So, I'm writing to express my considerable gratitude for your warm reception.
> When I first time arrived at U.S, It's you that greeted me with smile and swept my intense. Then, you became my first and best friend in Sino-American cultural exchange program. As a fresh member, Confusion always immersed in my brain, and then, you will appear like a angel. Since I came back home, I miss you every seconds and minutes.
> I specifically welcome you visit China in due course. I will bring you to travel famous resorts in China, which will give you a deep impression with Chinese history.
> At the last, I want to show my grateful appreciation to you for your help and treat. Hope you will come to China oneday!
> Yours, Zhang Wei.

Skill 在开跑前会先确认一句："这次按湖南做地区参考，对吗？"你说"对"它就开始批。

## 输出

- 对话里给你一段精简摘要（档位、最该改的 3 处、地区参考一句）。
- 同时生成三个文件：`批改报告_<日期>_01.html`、`学习档案卡_<你>.md`、`个人模板卡_<你>.md`。
- 完整的逐句对照卡、双版本作文、语法知识点都在 HTML 报告里（见 `sample_report.html`）。

## 下一次

新开对话时，先把上次的"学习档案卡"整段粘贴给它，它就能接着你的历史错误继续批，不用重新建档。
