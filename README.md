# AI Chat Log Summarizer

This Python tool parses AI chat logs from `.txt` files and generates a simple summary including total exchanges and top keywords.

## Features
- Parses messages by User and AI
- Counts total messages
- Extracts top 5 keywords (excluding stopwords)
- Supports multiple chat logs in a folder

## How to Use
1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Download NLTK resources:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

3. Run the summarizer:
```bash
python chat_parser.py
```

## Sample Output
```
Processing sample_chat.txt:
Summary:
- The conversation had 6 exchanges.
- The user asked mainly about relevant topics.
- Most common keywords: machine, learning, ai, field, data
```
