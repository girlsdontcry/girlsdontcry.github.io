---
layout: paper
categories: papers
permalink: papers/llm-safety-landscape
id: llm-safety-landscape
title: "Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models"

venue: In submission
year: 2024
url: llm-safety-landscape
pdf: https://arxiv.org/abs/2405.17374
figure: /images/papers/24_safety-landscape.png
caption: "<b>A</b>. \"Safety basin\", a new phenomenon observed universally in the model parameter space of popular open-source LLMs. Our discovery inspires us to propose the new VISAGE safety metric that measures the safety in LLM finetuning by probing its safety landscape.
<b>B</b>. Visualizing the safety landscape of the aligned model also enables us to understand why finetuning with harmful data compromises safety but finetuning with both harmful and safe data preserves the safety."
feature-title: "Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models"
feature-description: <b> ShengYun Peng </b>, Pin-Yu Chen, Matthew Hull, Duen Horng Chau
image: /images/featured/24_safety-landscape.png
featured: true
feature-order: 20240522
coming-soon: false
award: 
award-link: 
code: 
selected: true
type: conference
bibtex: |-

    @article{peng2024navigating,
      title={Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models},
      author={Peng, ShengYun and Chen, Pin-Yu and Hull, Matthew and Chau, Duen Horng},
      journal={arXiv preprint arXiv:2405.17374},
      year={2024}
    }
---

Safety alignment is the key to guide the behaviors of large language models ( LLMs) are in line with human preferences and restrict harmful behaviors at inference time, but recent studies show that it can be easily compromised by finetuning with only a few adversarially designed training examples. We aim to measure the risks in finetuning LLMs through navigating the LLM safety landscape. We discover a new phenomenon observed universally in the model parameter space of popular open-source LLMs, termed as “safety basin”: randomly perturbing model weights maintains the safety level of the original aligned model in its local neighborhood. Our discovery inspires us to propose the new VISAGE safety metric that measures the safety in LLM finetuning by probing its safety landscape. Visualizing the safety landscape of the aligned model enables us to understand how finetuning compromises safety by dragging the model away from the safety basin. LLM safety landscape also highlights the system prompt’s critical role in protecting a model, and that such protection transfers to its perturbed variants within the safety basin. These observations from our safety landscape research provide new insights for future work on LLM safety community.
