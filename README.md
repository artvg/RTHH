# RTHH *(Phase 1)*  
Reducing Medical Hallucinations in Large Language Models

Project Summary

RTHH (Surprise name) explores how large language models hallucinate in medical question and whether prompt design can reduce those errors.

Current Phase - Phase 1: Cloud Model Testing

Originally, the plan was to build and test the hallucination detection pipeline locally using Ollama (DeepSeek & Gemma). While the local setup was successfully implemented, it quickly became too heavy and unstable for my current hardware. As a result, all Ollama components were removed and the project shifted dirrecly to cloud based APIs, which provide faster, more reliable testing.

Present Focus

Phase 1 now centers on running and evaluating the pipeline using Gemini and ChatGPT. I am currently loading the medical dataset, labeling responses, and preparing to calculate hallucination rates across these two models.

Upcoming - Phase 2: Prompt Engineering

Phase 2 will focus on experimenting with prompt re phrasing and structured prompting to test whether careful prompt design can reduce hallucination frequency in medical responses. This keeps the original goal of the project which was improving factual reliability while remaining realistic within time and resource limits.

Tools & Tech
- Language: Python
- Libraries: PyTorch, Transformers, Pandas, NumPy, Matplotlib, scikit-learn
- Current Models: Gemini (API), ChatGPT (API)
- Discontinued: DeepSeek & Gemma (Ollama was removed due to hardware limits), and Grok (API) & Copilot(API) (due to time remaining on project).
- Dataset: https://huggingface.co/datasets/curaihealth/medical_questions_pairs

Project Status

Phase 1: Cloud based testing and dataset processing using Gemini & ChatGPT (In progress)

Phase 2: Prompt engineering experiments for hallucination reduction (Upcoming)

Repository Notes
- This repo is under active development.
- Ollama implementation has been aborted due to performance limitations.
- Gemini is fully connected and processing the dataset; ChatGPT integration is validated (payment issue pending).
- Grok and Copilot were removed from scope to prioritize completing the full experiment with the two stable models.
- Future commits will include hallucination scoring modules, prompt testing scripts, and final analysis notebooks.

Stay tuned RTHH still has a surprise waiting for the finale!!!