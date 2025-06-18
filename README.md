title: Riya - All-in-One AI Assistant
emoji: 🤖
colorFrom: pink
colorTo: purple
sdk: gradio
sdk_version: 4.19.2
app_file: app.py
python_version: 3.10
license: mit

files:
  - path: index.html
    type: frontend

description: |
  Riya is your All-in-One Assistant, capable of answering questions, engaging in casual conversations, and helping with productivity. Built using Gradio with a custom HTML UI.

dependencies:
  - gradio==4.19.2
  - openai
  - python-dotenv

models:
  - openai/gpt-3.5-turbo  # Or any other LLM you are using

tags:
  - Generative AI
  - Assistant
  - Gradio
  - Custom UI
  - OpenAI

metadata:
  creator: Santhosh V
  age: 19
  personality: Youthful, Intelligent, Dynamic AI
  profile_image: https://herobot.app/wp-content/uploads/2022/11/AI-bot-1.jpg
