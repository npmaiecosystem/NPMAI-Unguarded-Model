### Initial model: 
**Deepseek-r1-abliterated-32B**: https://huggingface.co/huihui-ai/DeepSeek-R1-Distill-Qwen-32B-abliterated
**GLM5.2 (Distill first)**: https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF

### 1. General / Knowledge Update (Latest Data, Continued Pretraining/SFT)
- **RedPajama-Data-v2**: https://huggingface.co/datasets/togethercomputer/RedPajama-Data-V2
- **RefinedWeb (Falcon)**: https://huggingface.co/datasets/tiiuae/falcon-refinedweb
- **arXiv Dataset**: https://www.kaggle.com/datasets/Cornell-University/arxiv
- **Wikipedia dumps** (recent): https://dumps.wikimedia.org/ or HF mirrors
- **OpenWebMath**: https://huggingface.co/datasets/open-web-math/open-web-math

### 2. General Instruction / SFT (for Distillation Base)
- **OpenHermes 2.5**: https://huggingface.co/datasets/teknium/OpenHermes-2.5
- **UltraChat** (filtered): https://huggingface.co/datasets/stingning/ultrachat

### 3. Coding
- **Magicoder-OSS-Instruct-75K**: https://huggingface.co/datasets/ise-uiuc/Magicoder-OSS-Instruct-75K
- **OpenCodeInstruct**: Search HF or related papers
- **Nemotron-SFT-Competitive-Programming-v2**: HF NVIDIA collections
- **The Stack v2** (BigCode): https://huggingface.co/datasets/bigcode/the-stack-v2 (permissively licensed code)
- **rStar-Coder**: https://huggingface.co/datasets/microsoft/rStar-Coder

### 4. Reasoning / Math (for CoT & Distillation)
- **NuminaMath-CoT / TIR**: https://huggingface.co/datasets/AI-MO/NuminaMath-CoT (and TIR variant)
- **GSM8K**: https://huggingface.co/datasets/openai/gsm8k
- **MATH**: https://huggingface.co/datasets/hendrycks/competition_math
- **OpenThoughts3**: Search HF

---
