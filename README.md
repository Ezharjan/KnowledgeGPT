<h1 align="center">
📖KnowledgeGPT
</h1>

Accurate answers and instant citations for your documents.

## 🔧 Features

- Upload documents 📁(PDF, DOCX, TXT) and answer questions about them.
- Cite sources📚 for the answers, with excerpts from the text.

## 💻 Running Locally

1. Prepare your OpenAI API Key so that you can configure the settings when the application is launched.**Remember to change the IP of the deployed server to the place where OpenAI allows**.


2. Clone the repository📂

```bash
git clone https://github.com/mmz-001/knowledge_gpt
cd knowledge_gpt
```

3. Install [Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer) on your computer. If you are using Windows platform, try run the following command:

```bash
curl -sSL https://install.python-poetry.org | python - --git https://github.com/python-poetry/poetry.git@master
```




4. **Make sure you are in Administrator/root while running the console board!** Install dependencies with [Poetry](https://python-poetry.org/) and activate virtual environment🔨

```bash
poetry install
poetry shell
```

5. Install some pip packages:

```bash
pip install docx2txt
pip install --upgrade langchain
pip install pypdf
pip install streamlit --upgrade
```

6. Run the Streamlit server🚀

```bash
cd knowledge_gpt
streamlit run main.py
```

## 🚀 Upcoming Features

- Add support for more formats (e.g. webpages 🕸️, PPTX 📊, etc.)
- Highlight relevant phrases in citations 🔦
- Support scanned documents with OCR 📝
- More customization options (e.g. chain type 🔗, chunk size📏, etc.)

<br>
<br>
<br>

[Online Official Demo](https://knowledgegpt.streamlit.app/)

<br>

[Known Issues](https://blog.csdn.net/weixin_43894266/article/details/123315430)
