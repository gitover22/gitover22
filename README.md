# Hi, I'm gitover22 👋

## 😎 About Me

AI Infrastructure Engineer specializing in high-performance LLM inference,
distributed serving, model optimization, and accelerator enablement across
NVIDIA GPUs and Cambricon MLUs.

## 💼 Experience

### Institute of Computing Technology, Chinese Academy of Sciences

**LLM Inference Systems on Cambricon Accelerators** · *Aug 2024 – Jun 2026*

**Tech stack:** Cambricon NeuWare · PyTorch · Ray · Hugging Face Transformers

- Developed KV cache management, prompt scheduling, and parallel inference
  components. Trained a DistilBERT-based output-length predictor that achieved
  **99.16% accuracy** on a public dataset.
- Used predicted output lengths to guide device-memory allocation and request
  scheduling, reducing head-of-line blocking. Designed demand-driven memory
  allocation for Cambricon MLU370 accelerators, increasing SLO-compliant
  concurrency by **2.27×** and device-memory utilization from
  **42.39% to 71.37%**.
- Ported and optimized **more than 10 LLMs**, including Llama, Qwen, and
  DeepSeek, from GPU runtimes to the Cambricon MLU platform.

### Zhejiang Lab

**LLM Deployment & Inference Optimization** · *Apr 2024 – Aug 2024*

**Tech stack:** GPTQ · vLLM · NVIDIA A100 · NVIDIA Nsight · LoRA

- Quantized a domain-specific 70B LLM with GPTQ and deployed it on NVIDIA A100
  GPUs using vLLM. Performance tuning increased supported request concurrency
  by **18.3%** and raised device-memory utilization to **95.7%**.
- Integrated team-developed MoE quantization operators into the inference
  runtime and benchmarked them against the baseline with NVIDIA Nsight.
  Fine-tuned the domain model with LoRA, improving chip-design
  question-answering accuracy by **25.83%**.

## 🚀 Technologies

![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&color=black&logoColor=blue)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&color=black&logoColor=blue)
![CUDA](https://img.shields.io/badge/-CUDA-00599C?style=flat-square&logo=nvidia&color=black&logoColor=76B900)
![Python](https://img.shields.io/badge/-Python-00599C?style=flat-square&logo=python&color=black)
![Shell](https://img.shields.io/badge/-Shell-00599C?style=flat-square&logo=gnubash&color=black)
![CMake](https://img.shields.io/badge/-CMake-00599C?style=flat-square&logo=cmake&color=black&logoColor=blue)
![Redis](https://img.shields.io/badge/-Redis-00599C?style=flat-square&logo=redis&color=black)
![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql&color=black&logoColor=blue)
![Qt](https://img.shields.io/badge/-Qt-00599C?style=flat-square&logo=Qt&color=black)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git&color=black)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&color=black)
![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=flat-square&logo=gitlab&color=black)

## 🐲 GitHub Stats

<!-- https://github.com/anuraghazra/github-readme-stats -->
<!-- markdownlint-disable MD013 MD033 -->

<a href="https://github.com/anuraghazra/github-readme-stats"><img alt="gitover22's GitHub stats" src="https://denvercoder1-github-readme-stats.vercel.app/api/?username=gitover22&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866" height="192px"/></a>
<a href="https://github.com/anuraghazra/github-readme-stats"><img alt="gitover22's top languages" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=gitover22&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&hide=Jupyter%20Notebook,Roff" height="192px"/></a>

<!-- markdownlint-enable MD013 MD033 -->
