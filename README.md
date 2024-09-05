# practical-llm
Practical LLM Dev

https://github.com/DJCordhose/practical-llm

## Prerequisites 
1. Create a Google Account (if you do not have one, yet): https://accounts.google.com/  
1. Login with that account into Google Colab: https://colab.research.google.com/ 
1. Create a Huggingface account (if you do not have one, yet): https://huggingface.co/join
1. Create an access token and save it for later use in the notebooks: https://huggingface.co/settings/tokens
1. Request access to gated Huggingface models:
   1. https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct 
   1. https://huggingface.co/google/gemma-2-2b-it

## Notebooks on Colab
1. https://colab.research.google.com/github/DJCordhose/practical-llm/blob/main/Assessment.ipynb?hl=en
1. https://colab.research.google.com/github/DJCordhose/practical-llm/blob/main/Eval4pptx.ipynb?hl=en

## Comparing GPU microarchitectures
* T4/RTX 20: https://en.wikipedia.org/wiki/Turing_(microarchitecture)
  * V100 - professional variant of RTX 20 consumer line: https://en.wikipedia.org/wiki/Volta_(microarchitecture)
* A100/RTX 30: https://en.wikipedia.org/wiki/Ampere_(microarchitecture)
* L4/L40/RTX 40: https://en.wikipedia.org/wiki/Ada_Lovelace_(microarchitecture)
  * H100 - professional variant of RTX 40 consumer line, not available on Colab (yet?): https://en.wikipedia.org/wiki/Hopper_(microarchitecture)
* Future successor to both Hopper and Ada Lovelace: https://en.wikipedia.org/wiki/Blackwell_(microarchitecture)
* comparing GPUs: https://www.reddit.com/r/learnmachinelearning/comments/18gn1b2/choosing_the_right_gpu_for_your_workloads_a_dive/
