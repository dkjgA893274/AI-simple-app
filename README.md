# AI-simple-app

LangChain と Streamlit で作るシンプルなチャットボット

## 概要
1. chatbot.ipynb
    - LangChain + OpenAI API を利用した最小構成のチャットUI
    - Google Colab から実行・デプロイ手順を解説

## すぐ試す
[Open in Colab](https://colab.research.google.com/github/<your-name>/AI-simple-app/blob/main/section_1/chatbot.ipynb)

## セットアップ（ローカル）
```bash
python -m venv .venv && source .venv/bin/activate
pip install -U streamlit langchain langchain-openai python-dotenv
export OPENAI_API_KEY=sk-xxxx
streamlit run app.py
