# 🕵️‍♀️ AI SPY — Intelligent Image Caption Generator

An AI-powered tool that generates captions, headlines, and social media copy from images using computer vision and NLP models.

## 🚀 Features
- Automatic image captioning
- AI-generated marketing headlines
- Fun, social-media-ready captions
- Optional translation support (English ↔ Hindi)

## 🧠 Models Used
- BLIP / ViT-GPT2 for image captioning
- FLAN-T5 for creative text generation
- MarianMT for translation

## 🧰 Tech Stack
Python · Transformers · Streamlit · PyTorch

## 🖼️ Example Output
| Input Image | Generated Caption | Headline | Social Caption |
|--------------|------------------|-----------|----------------|
| 🏞️ Road & Mountains | “a long road with a mountain in the background” | “Chase horizons beyond the ordinary” | “Adventure is calling 🚗✨ #TravelGoals” |

## 💻 Run Locally
```bash
git clone https://github.com/<your-username>/AI-SPY.git
cd AI-SPY
pip install -r requirements.txt
streamlit run app.py
