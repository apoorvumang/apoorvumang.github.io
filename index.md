---
layout: single
author_profile: true
author: Apoorv Umang Saxena
toc: true
---
I am a Member of Technical Staff at [Inception](https://inceptionlabs.ai), working from our Bangalore office across the training and inference stack for [Mercury](https://www.inceptionlabs.ai/), our family of diffusion LLMs. Previously I was a Research Scientist at Adobe Research, working on NLP and multi-modal machine learning.

I received my PhD from the Department of Computational and Data Sciences (CDS) at the [Indian Institute of Science, Bangalore](https://www.iisc.ac.in/), advised by [Prof. Partha Talukdar](https://scholar.google.com/citations?user=CIZwXAcAAAAJ), where I worked on knowledge graph embeddings for question answering ([thesis](https://etd.iisc.ac.in/handle/2005/6082)).

Prior to graduate school, I received my Bachelor of Engineering (BE Hons.) in Computer Science from [Birla Institute of Technology and Science, Pilani (BITS Pilani)](http://www.bits-pilani.ac.in/) in 2015.


## Research

My work comes down to two questions: **how do you make language models faster without giving up quality**, and **how do you verify that what a model generates is actually supported by what you gave it**.

On speed, I wrote [Prompt Lookup Decoding](https://github.com/apoorvumang/prompt-lookup-decoding), a speculative decoding method now integrated into Hugging Face Transformers and vLLM, and I currently work on inference for diffusion LLMs at Inception.

On grounding, I work on attribution — reading a model's attention to trace generated text back to the exact source spans behind it. That research [shipped in Adobe Acrobat's AI Assistant](https://arxiv.org/abs/2405.17980) and is now the foundation of [TokenPath](https://tokenpath.ai/).

During my PhD I worked on knowledge graph embeddings for question answering. During my undergraduate studies I worked on humanoid robotics and computer vision.

A full publication list is on [Google Scholar](https://scholar.google.com/citations?user=MpOVpSUAAAAJ).


## Projects

### Everything 3D

Get custom 3D-printed figurines and personalized keepsakes made from your photos. Order a unique gift from the store or follow the latest creations on Instagram :)

Store: [everything3dindia.com](https://everything3dindia.com/)  
Instagram: [everything_3d_india](https://www.instagram.com/everything_3d_india/)

<button>
<a style="text-decoration: none;" href="https://everything3dindia.com/"><i class="fas fa-store"></i> Visit Store</a>
</button>
<button>
<a style="text-decoration: none;" href="https://www.instagram.com/everything_3d_india/"><i class="fab fa-instagram"></i> Follow on Instagram</a>
</button>

### TokenPath.ai

TokenPath is an API for grounding AI-agent outputs by tracing generated tokens back to the exact source tokens behind them. It grew out of my research on attribution in document-grounded question answering, and provides token-level attribution signals for precise citations, provenance, hallucination gates, and evals.

Website: [tokenpath.ai](https://tokenpath.ai/)  
Docs: [docs.tokenpath.ai](https://docs.tokenpath.ai/)

<button>
<a style="text-decoration: none;" href="https://tokenpath.ai/"><i class="fas fa-link"></i> Website</a>
</button>
<button>
<a style="text-decoration: none;" href="https://docs.tokenpath.ai/"><i class="fas fa-fw fa-book" aria-hidden="true"></i> Docs</a>
</button>
<button>
<a style="text-decoration: none;" href="https://arxiv.org/abs/2405.17980"><i class="fas fa-file-alt"></i> Research</a>
</button>


## Experiments

### Knowledge Cutoff Benchmark

A simple benchmark to measure the *actual* knowledge cutoff of LLMs, rather than the date labs report. The results are surprising: OpenAI and Anthropic are the only major labs keeping their models fresh — most others, including the Chinese labs, lag by 12+ months.

<button>
<a style="text-decoration: none;" href="https://apoorvumang.github.io/knowledge-cutoff/"><i class="fas fa-chart-bar"></i> Live Benchmark</a>
</button>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/knowledge-cutoff"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>
<button>
<a style="text-decoration: none;" href="https://x.com/apoorv_umang/status/2075646580083048945"><i class="fab fa-fw fa-x-twitter" aria-hidden="true"></i> X Post</a>
</button>

### Retrieval vs Recall

Agentic search benchmarks may not measure search. Running WideSearch with retrieval turned *off*, one frontier model scored slightly **better** without it — the tasks are built from facts old enough to answer from memory. Rebuilt on post-cutoff events, the ranking changed. Write-up published on the Inception blog.

<button>
<a style="text-decoration: none;" href="https://www.inceptionlabs.ai/blog/mercury-2-for-search"><i class="fas fa-file-alt"></i> Write-up</a>
</button>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/retrieval-vs-recall"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>

### The Seen and the Unseen — Transcripts

A searchable browser for Whisper-generated transcripts of Amit Varma's podcast [The Seen and the Unseen](https://seenunseen.in/), covering 300+ episodes. Read any episode's transcript in a clean, per-episode view.

<button>
<a style="text-decoration: none;" href="{{site.url}}/seenunseen/"><i class="fas fa-podcast"></i> Browse Transcripts</a>
</button>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/seenunseen-whisper"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>


## Selected publications
**Saxena A.** [Prompt Lookup Decoding](https://github.com/apoorvumang/prompt-lookup-decoding). 
Developed a method to speed-up LLM decoding, integrated in transformers and vLLM.<br>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/prompt-lookup-decoding"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>
<button>
<a style="text-decoration: none;" href="https://x.com/joao_gante/status/1747322413006643259"><i class="fab fa-fw fa-x-twitter" aria-hidden="true"></i> X Post</a>
</button>
<button>
<a style="text-decoration: none;" href="https://docs.vllm.ai/en/latest/features/speculative_decoding/n_gram/"><i class="fas fa-fw fa-book" aria-hidden="true"></i> vLLM Docs</a>
</button>


D.J. Bajpai, S. Agarwal, **A. Saxena**, K. Kulkarni, S. Mitra & M.K. Hanawal. ["FlowCast: Trajectory Forecasting for Scalable Zero-Cost Speculative Flow Matching"](https://arxiv.org/abs/2602.01329). International Conference on Learning Representations (ICLR 2026).


S. Somasundaram, A. Phukan & **A. Saxena**. ["PLD+: Accelerating LLM Inference by Leveraging Language Model Artifacts"](https://arxiv.org/abs/2412.01447). Findings of the Association for Computational Linguistics: NAACL 2025.


A. Phukan, S. Somasundaram, **A. Saxena**, K. Goswami & B.V. Srinivasan. ["Peering into the mind of language models: An approach for attribution in contextual question answering"](https://arxiv.org/abs/2405.17980). Findings of the Association for Computational Linguistics: ACL 2024, 11481-11495. Shipped in Adobe Acrobat's AI Assistant.


**Saxena A.**, Kochsiek A. & Gemulla R. [“Sequence-to-Sequence Knowledge Graph Completion and Question Answering”](https://arxiv.org/abs/2203.10321). Accepted to the 2022 Annual Conference of the Association for Computational Linguistics (ACL 2022).<br>
<button>
<a style="text-decoration: none;" href="https://huggingface.co/spaces/apoorvumang/kgt5"><i class="fas fa-play"></i> Demo</a>
</button>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/kgt5"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>
<button>
<a style="text-decoration: none;" href="https://docs.google.com/presentation/d/1704LNdD9yQAdAIPnjKEqKaytS74GT_E83aCFFAgJAPs/edit?usp=sharing">
<i class="fa fa-archive"></i> Slides</a>
</button>


**Saxena A.**, Chakrabarti S. & Talukdar P. [“Question Answering Over Temporal Knowledge Graphs”](https://aclanthology.org/2021.acl-long.520/). Accepted to the 2021 Annual Meeting of the Association for Computational Linguistics (ACL 2021).<br>
<button>
<a style="text-decoration: none;" href="https://github.com/apoorvumang/CronKGQA"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>


**Saxena A.**, Tripathi A. & Talukdar P. [“Improving Multi-hop Question Answering over Knowledge Graphs using Knowledge Base Embeddings”](https://malllabiisc.github.io/publications/papers/final_embedkgqa.pdf). Accepted to the 2020 Annual Conference of the Association for Computational Linguistics (ACL 2020).<br>
<button>
<a style="text-decoration: none;" href="https://virtual.acl2020.org/paper_main.412.html"><i class="fas fa-video"></i> Video</a>
</button>
<button>
<a style="text-decoration: none;" href="https://github.com/malllabiisc/EmbedKGQA"><i class="fab fa-fw fa-github" aria-hidden="true"></i> Code</a>
</button>


## Work Experience

### Inception, Bangalore
Member of Technical Staff — September 2025 - Present

Working across the training and inference stack for the Mercury series of diffusion LLMs.

- Core algorithmic work on application-specific decoding performance, including a 2x speedup on Mercury Edit
- Led post-training of Mercury 2 for an enterprise query-rewrite workload — quality parity with their production Gemini baseline, 2.5x faster
- Tool-calling data and evaluation for the Mercury 2 and Mercury 2.5 releases
- Work with search and answer-engine customers on agentic retrieval pipelines

### Adobe Research, Bangalore
Research Scientist — June 2022 - August 2025

Document Experiences Lab — research on LLMs for document understanding, generation and grounding, taken from idea to shipped product.

- Shipped attribution into Acrobat's AI Assistant, giving users sentence-level grounding for answers over long documents
- Contributor to the first Adobe Firefly image model
- 15+ papers at ACL, EMNLP, NAACL, ICCV, EACL and INLG; 12+ patents filed
- Mentored interns and junior researchers, several of whom led first-author papers at ACL, NAACL and EMNLP

### Google, Hyderabad
Software Engineer, Tools and Infrastructure — May 2016 - Mar 2017

### PayPal, Chennai
Software Engineer 1 — July 2015 - November 2015

## Teaching

Guest lecturer on **LLM decoding** in [Introduction to Natural Language Processing (DS 207)](https://danishpruthi.com/teaching/ds-207-jan-2026/) at the Indian Institute of Science, invited two years running (2025 and 2026). Course by Prof. Danish Pruthi.

## CV

[PDF]({{site.url}}/download/Apoorv_Resume_CV_Sep2026.pdf)

## Contact

### Email

apoorv [at] inceptionlabs.ai
<br />
apoorvumang [at] gmail.com
