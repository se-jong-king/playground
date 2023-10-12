# ChatGPT Playground
Put your OpenAI API Key in `.streamlit/secrets.toml`.
```config
OPENAI_API_KEY = "YOUR_API_KEY"
```
Run streamlit app.
```bash
# for local
pip install -r requirements.txt

# for codespace
ln -s /home/codespace/.local/lib/python3.10/site-packages/bin/streamlit /home/codespace/.local/bin/

streamlit run chatbot.py
```
Dependency: `openai`, `streamlit`.

- To add function call, put your function into the directory `functions` and write the description in the `functions/__init__.py`.