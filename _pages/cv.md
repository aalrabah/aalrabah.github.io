---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/resume.pdf" class="btn btn--info">Download PDF</a>

Education
======
* Ph.D. in Computer Science, University of Illinois Urbana-Champaign, Aug 2025 – present
* M.S. in Computer Science, University of Illinois Urbana-Champaign, Dec 2024
* B.S. in Mechanical Engineering, California State University Northridge, May 2013

Research Experience
======
* Aug 2025 – present: Graduate Research Assistant, Siebel School Fellow, University of Illinois Urbana-Champaign
  * Multimodal knowledge graph pipeline for large-scale retrieval and concept extraction, running multi-LLM inference (Llama 3B/8B, Qwen 14B) on H200/A100 GPUs via vLLM with human-in-the-loop evaluation
  * Agent-based task-oriented dialogue system for contextual risk intervention using belief state tracking, structured databases, and reinforcement learning for action selection
  * Embodied multi-agent planning by extending PARTNR (Habitat 3.0) with inter-agent dialogue, training coordination policies with SFT and GRPO on Llama 3.1-8B
  * Generative AI diagnosis pipeline that maps semantic errors to knowledge graph concepts, evaluated against expert human judgments

* Jan 2025 – Aug 2025: Volunteer Researcher, University of Illinois Urbana-Champaign
  * Organized course interaction data and summarized usage patterns for an AI-driven education analytics tool
  * Prototyped a knowledge graph linking student activity signals to learning concepts and prerequisites

* May 2023 – Dec 2024: Graduate Research Assistant, University of Illinois Urbana-Champaign
  * Built CodeLens, an AI-powered SQL assistant that gives targeted feedback on semantic errors in student queries, using fine-tuned GPT models on real student submissions
  * Work published at ASEE 2024 and DataEd 2025

* Aug 2023 – Dec 2023: Researcher, CS 598 Security and Privacy for IoT in Homes, University of Illinois Urbana-Champaign
  * Designed the user interface for a Matter protocol testbed with a network utility device for traffic sniffing and wireless access
  * Distinguished Paper Award at SDIoTSec 2024

Industry Experience
======
* May 2026 – present: ChipStack AI Super Agent Team, Cadence Design Systems, San Jose, CA
  * LLM-based agents for automated RTL design and optimization workflows
  * Benchmarking and evaluation pipelines for agent performance on PPA objectives

* Jun 2023 – Aug 2023: Web Application Developer, Department of Computer Science, University of Illinois Urbana-Champaign
  * Demo booking website with Python Flask and Google Cloud, including authentication and booking management

* Jan 2016 – Aug 2021: Founder and CEO, Gonuts Cronuts LLC, Kuwait
  * Ran financial and operational strategy and supply chain analytics for a business supplying 70+ outlets

* Jun 2014 – Dec 2015: Field Engineer, Baker Hughes Drilling Fluids, Ahmadi, Kuwait
  * Optimized drilling fluid properties using operational and geological data analysis

* Dec 2013 – Jun 2014: Plant Engineer, Alkout Industrial Project, Shuaiba, Kuwait
  * Plant inspections, scheduled shutdowns, and chemical input process improvements

Skills
======
* Programming: Python, Java, Matlab, R
* Frameworks: PyTorch, TensorFlow, vLLM
* Data: SQL, Neo4j, MongoDB, pandas, NumPy, scikit-learn, PowerBI, Tableau
* Web and Cloud: HTML, CSS, JavaScript, Docker, AWS, GCP
* Languages: English (native), Arabic (native), French (basic)

Publications
======
{% assign pubs = site.publications | sort: "date" | reverse %}
<ul>
{% for pub in pubs %}
  <li><a href="{{ pub.paperurl }}" target="_blank" rel="noopener noreferrer">{{ pub.title }}</a>{% if pub.award %} &#127942; {{ pub.award }}{% endif %}<br>
  <span style="font-size:0.9em">{{ pub.authors }}. <i>{{ pub.venue }}</i>, {{ pub.year }}.</span></li>
{% endfor %}
</ul>

Awards
======
* Distinguished Paper Award, SDIoTSec 2024
* Siebel School Fellow, University of Illinois Urbana-Champaign, 2025
* 1st place, Fostering the Entrepreneurial Mindset, Babson Global Inc., 2016
* 1st place, SME Entrepreneurship Diploma, The National Fund, 2016
