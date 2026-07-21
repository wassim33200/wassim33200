[README.md](https://github.com/user-attachments/files/30246242/README.md)
<div align="center">
  <img src="https://github-profile-maker.vercel.app/api/capsule?type=waving&color=3300ff&colorEnd=ff0000&height=180&section=header&text=Data+Scientist+%26+ML+Engineer&fontSize=42&fontColor=ffffff&animation=wave&gradientDirection=diagonal&parallax=true&wavePosition=56&waveAmplitude=50&waveSpeed=5&flipWave=true&textAlignX=50&textAlignY=50&rtl=0&rtr=0&rbr=0&rbl=0" />
</div>

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/109911566?v=4" width="130" height="130" style="border-radius: 15px;" />
</div>

<h1 align="center">Turning data into decisions 🧠</h1>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=586AF9&center=true&vCenter=true&width=520&height=30&lines=Machine%20Learning%20Engineer%3BDeep%20Learning%20%C2%B7%20NLP%20%C2%B7%20Computer%20Vision%3BPython%20%C2%B7%20PyTorch%20%C2%B7%20TensorFlow%3BMaking%20models%20that%20ship%20to%20production" alt="Typing SVG" />
</div>

<div align="center">
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/wassim33200) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wassim33200) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hamdiwassim24@gmail.com) [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://wassim.site)
</div>

<div align="center">
  <img src="https://github-profile-maker.vercel.app/api/divider?bgType=gradient&thickness=4&alignment=center&bgSolidColor=3300FF&bgStartColor=0000FF&bgEndColor=FF0000&bgGradientDirection=horizontal" alt="Divider" />
</div>

## What I Work On 🔬

I research and build machine learning systems — from data pipelines and feature engineering to model training, evaluation, and deployment. I bridge the gap between research and production.

<details open>
<summary>📄 Research & Publications</summary>

- **[2024]** "Efficient Fine-Tuning of LLMs at Scale" — arxiv.org/abs/xxxx
- **[2023]** "Real-Time Anomaly Detection in Time-Series Data" — arxiv.org/abs/yyyy
- **[2022]** "Self-Supervised Representations for Medical Imaging" — NeurIPS Workshop

</details>

<details>
<summary>🤖 Featured ML Projects</summary>

- **llm-fine-tuner** — CLI for LoRA/QLoRA fine-tuning of open-source LLMs
- **timeseries-bench** — Benchmark suite for time-series forecasting models
- **cv-pipeline** — Modular computer vision training framework (PyTorch Lightning)

</details>

## Core Stack 🧰

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,docker,kubernetes,aws,github,linux&perline=10&theme=dark" />
</div>

### Data & Tooling 📦

```python
# A glimpse at my typical experiment setup
import torch
from transformers import AutoModelForCausalLM, AutoTokenizer
from peft import LoraConfig, get_peft_model

model = AutoModelForCausalLM.from_pretrained("mistralai/Mistral-7B-v0.1")
config = LoraConfig(r=16, lora_alpha=32, target_modules=["q_proj", "v_proj"])
model = get_peft_model(model, config)
print(f"Trainable params: {model.num_parameters(only_trainable=True):,}")
```

<div align="center">
  <img src="https://github-profile-maker.vercel.app/api/divider?bgType=solid&thickness=1&alignment=center&bgSolidColor=2D4A2D&bgStartColor=2D4A2D&bgEndColor=2D4A2D&bgGradientDirection=horizontal" alt="Divider" />
</div>

<div align="center">
  <img src="https://github-profile-maker.vercel.app/api/quotes?theme=dark&quote=In+God+we+trust%2C+all+others+must+bring+data.&author=W.+Edwards+Deming&textAlign=center&authorAlign=center" alt="Quote" />
</div>

<div align="center">
  <img src="https://github-profile-maker.vercel.app/api/capsule?type=waving&color=3300ff&colorEnd=ff0000&height=180&section=header&text=Thank+You&fontSize=42&fontColor=ffffff&animation=wave&gradientDirection=diagonal&parallax=true&wavePosition=40&waveAmplitude=50&waveSpeed=5&flipWave=false&textAlignX=50&textAlignY=50&rtl=0&rtr=0&rbr=0&rbl=0" />
</div>
