---
layout: about
title: About
permalink: /
subtitle: Tenure-track Assistant Professor at Tsinghua University

profile:
  align: right
  image: jingtao_zhan.png
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Tsinghua Shenzhen International Graduate School</p>
    <p>Tsinghua University</p>
    <p>Shenzhen, China</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

mermaid:
  enabled: true
  zoomable: false

tabs: true
---

<style>
  .publications .links {
    display: flex;
    flex-wrap: wrap;
  }

  .publications .links a[href$=".pdf"] {
    order: -1;
  }

  .social .contact-icons a[title="Xiaohongshu"] svg {
    margin-bottom: 0;
    vertical-align: -0.125em;
  }
</style>

I am a tenure-track Assistant Professor at [Tsinghua Shenzhen International Graduate School](https://www.sigs.tsinghua.edu.cn/en/), Tsinghua University. I lead [**FAITH Lab**](https://www.faithlab.cn/) (**F**oundation of **AI** lab at **T**sing**H**ua), where we study the fundamental principles of artificial intelligence and seek the underlying laws that govern intelligent systems.

I received my Ph.D. in Computer Science and Technology from Tsinghua University in 2025, advised by Prof. Shaoping Ma and Prof. Yiqun Liu. I received my B.E. in Electronic Engineering from Tsinghua University in 2020.

## The meaning of FAITH

The name **FAITH** carries a double meaning.

- As an acronym, **FAITH** stands for the **F**oundation of **AI** lab at **T**sing**H**ua. It expresses our commitment to rigorous, fundamental research.
- As a word, **faith** expresses the starting point of scientific inquiry. It is the commitment to pursue a possibility before sufficient evidence exists.

The name therefore joins the starting point of research with its desired result. [Read more in _Why FAITH?_]({% post_url 2026-08-06-why-faith %})

## Research vision

**The purpose of artificial intelligence is to scale human intelligence.**

A person's intelligence does not scale on its own. It is formed through experience, then remains embodied in that individual. Its direct reach is therefore limited to the people that individual can assist. Humanity has long preserved experience in external artifacts like books. These artifacts allow knowledge to outlive its creators. AI makes the accumulated human knowledge usable at scale. It enables lessons learned within individual lives to serve people far beyond their original reach. The central research question is how far human intelligence can be scaled.

Previously, information retrieval (IR) established a major paradigm for scaling intelligence. Since human knowledge is stored in external artifacts, an IR system organizes these artifacts into a searchable collection, then retrieves the information that matches each user's need. It scales the application of human knowledge by allowing the relevant information to reach each person. Its central research question is how efficiently the right information can be matched to a particular need.

Today, generative AI has become a central paradigm for scaling human intelligence and is currently the main focus of my research. In this paradigm, intelligence is embodied in the model. During training, an LLM compresses the knowledge expressed in human-created data into its parameters. During inference, the LLM uses the intelligence encoded in those parameters to generate information for a particular need. Unlike IR that only locates existing information, generative AI can synthesize a novel response for a new task and thus makes accumulated human knowledge reusable across a much wider range of problems. Despite the change of paradigm, the purpose remains the same: to make human intelligence available as widely as possible.

There are several stages within generative AI: Human experience becomes data; learning turns data into an LLM; inference uses the capabilities of the LLM to produce information for users; and subsequent human activity begins the cycle again:

```mermaid
flowchart LR
    U["Users"] --- D["Data"]
    D ---|learning| M["LLM"]
    M ---|inference| I["Information"]
    I --- U
```

This cycle reveals four fundamental problems for AI:

- **Capturing human experience (Users → Data):** Human activity produces the data from which models learn. The central question is which data provide the most valuable basis for machine intelligence.
- **Building machine intelligence (Data → LLM):** Learning compresses data into model capabilities. The central question is how efficiently those capabilities can be acquired.
- **Applying machine intelligence (LLM → Information → Users):** Inference brings model capabilities to a user's need. The central question is how effectively the LLM can produce useful information.
- **Evolving machine intelligence (Users → LLM → Users):** Users bring new needs to the LLM. Information from the LLM shapes their subsequent activity. That activity produces new data for future learning. The central question is how this cycle can support continued model evolution.

The mission of FAITH Lab is to build an AI system that scales human intelligence to the greatest possible extent. I am broadly interested in every stage of the information cycle. Among them, four specific directions are of particular interest:

- **Scaling laws:** Scaling laws provide a theoretical lens on evaluating machine intelligence. We use them to study the science of generative AI. For example, we are particularly interested in understanding the pattern and boundary of machine intelligence under the current paradigm.
- **Model evolution:** We study how models can evolve efficiently with human feedback, memory techniques, reinforcement learning, etc. The goal is continual acquisition of new capabilities from experience.
- **Human intelligence versus machine intelligence:** We compare the two forms of intelligence to understand what current learning paradigms fail to capture. This comparison guides the search for stronger training methods. It also helps identify the data those methods require.
- **Agents:** Since agents can reliably complete tasks on behalf of users, they substantially scale human intelligence beyond what one person can do. We study how to use LLMs to build agents that can perform complex tasks.

## Join FAITH Lab

{% tabs join-language %}

{% tab join-language English %}

### Admissions

FAITH Lab typically has the following openings each year:

- 1–2 Ph.D. positions for students from mainland China
- 1 Ph.D. position for an international student
- 5–6 master's positions, with approximately half filled through recommendation-based admission and half through the national graduate entrance examination
- 1–2 master's positions for international students

The exact number of openings may vary from year to year.

**Programs and university affiliation:** Ph.D. students are admitted to the Computer Science and Technology program. Master's students may join the lab through one of three programs: Computer Technology, Large Model Science and Engineering, or AI for Science.

Tsinghua Shenzhen International Graduate School (Tsinghua SIGS) is a constituent school of Tsinghua University, institutionally parallel to other schools and departments such as the Department of Computer Science and Technology. All admitted students are enrolled as Tsinghua University students. Their admission letters, graduation certificates, and degree certificates are issued by Tsinghua University.

### What I look for in applicants

I look for applicants with a strong academic record and a deep, sustained interest in scientific research.

I encourage students at an early stage of their studies to join the lab as research interns. When other qualifications are comparable, I generally prefer applicants with substantial, long-term internship experience in the lab. A longer period of collaboration allows students to develop a deeper understanding of our research. It also helps the student and the lab assess their fit for long-term collaboration.

### Application materials

When applying to join the lab, please provide the following materials:

- **Curriculum vitae:** Include your educational background, research experience, project experience, and other relevant information.
- **Academic transcript:** Please also provide your ranking within your cohort or program.
- **Personal statement:** Introduce your background, key experiences, and long-term goals.
- **Research statement:** Describe the research directions that interest you, summarize representative work in these areas, and outline your initial research plan.

### Research internships

Research internships are available in either remote or in-person formats. In-person interns are welcome to participate in regular lab meetings. Students interested in joining the lab may contact me by email (jingtaozhan@tsinghua.edu.cn) and include the materials listed above.

{% endtab %}

{% tab join-language 中文 %}

### 招生名额

FAITH Lab 每年通常可提供以下招生名额：

- 1–2 名内地博士生
- 1 名国际博士生
- 5–6 名硕士生，其中推荐免试与统考录取各约占一半
- 1–2 名国际硕士生

具体名额可能根据当年的招生政策与实际情况有所调整。

**招生专业与学籍归属：**博士生通过“计算机科学与技术”专业招收。硕士生可通过“计算机技术”“大模型科学与工程”或“AI for Science（人工智能赋能科学）”项目加入实验室。

清华大学深圳国际研究生院是清华大学的二级院系，在学校组织体系中与计算机系等院系处于同一层级。所有录取学生均为清华大学学生，录取通知书、毕业证书和学位证书均由清华大学颁发。

### 我们希望寻找怎样的学生

我希望申请者具备扎实的学业基础，课程成绩良好，对科学研究抱有强烈而持久的兴趣。

我也欢迎低年级学生尽早加入实验室开展科研实习。在其他条件相当的情况下，我会优先考虑曾在实验室长期实习的同学。较长时间的共同研究能够帮助学生深入了解实验室的研究方向，也有助于老师与学生了解彼此。

### 申请材料

申请加入实验室时，请提供以下材料：

- **个人简历：**介绍教育背景、研究经历、项目经历以及其他相关信息。
- **学习成绩单：**请同时注明个人在专业中的排名。
- **个人自述：**介绍个人背景、主要经历以及未来发展规划。
- **研究陈述：**说明感兴趣的研究方向，概述该方向已有的代表性研究，并介绍自己的初步研究计划。

### 科研实习

科研实习可以线上进行，也欢迎同学线下参与实验室组会。申请者可以通过邮件联系我（jingtaozhan@tsinghua.edu.cn），并附上上述材料。

{% endtab %}

{% endtabs %}

## Honors and awards

- 2025 — Outstanding Graduate, Department of Computer Science and Technology, Tsinghua University
- 2024 — National Scholarship
- 2024 — SIGIR Best Paper Award
- 2022 — Longfor Scholarship
- 2022 — Overall Excellence Scholarship, First Prize, Tsinghua University (Top 5%)
- 2022 — WSDM Best Paper Award
- 2021 — Overall Excellence Scholarship, Second Prize, Tsinghua University (Top 10%)
- 2020 — Outstanding Graduate of Beijing
- 2020 — Outstanding Graduate of Tsinghua University

## Work and education

- **2025–present:** Tenure-track Assistant Professor, Tsinghua Shenzhen International Graduate School, Tsinghua University
- **2020–2025:** Ph.D., Department of Computer Science and Technology, Tsinghua University
- **2024:** Visiting Research Scholar, University of Illinois Urbana-Champaign
- **2016–2020:** B.E., Department of Electronic Engineering, Tsinghua University
