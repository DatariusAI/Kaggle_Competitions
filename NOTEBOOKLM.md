# 🧠 NotebookLM Integration

This repository has a dedicated [Google NotebookLM](https://notebooklm.google.com) notebook
pre-loaded with all curated papers, ebooks, and resources for **Kaggle Competitions**.

## 📚 What's Inside the Notebook
- 📄 Key research papers and articles
- 📖 Free textbooks and ebooks
- 🔗 Official documentation and guides
- 🎓 Course materials and tutorials

## 🎯 Generated Study Artifacts
| Artifact | Description |
|----------|-------------|
| 🎙️ Audio Podcast | Technical deep-dive discussion of core concepts |
| ❓ Quiz | Hard-difficulty questions to test understanding |
| 🗂️ Flashcards | Key terms and definitions for quick review |
| 🗺️ Mind Map | Visual overview of topic relationships |
| 📖 Study Guide | Structured learning path through the material |

## 🚀 Access via CLI
```bash
# Activate this notebook
python -m notebooklm use d1afe08c-75f7-41b8-aa46-296a58fbb385

# Ask questions grounded in the sources
python -m notebooklm ask "Your question here"

# Regenerate artifacts
python -m notebooklm generate audio --wait
python -m notebooklm generate quiz --difficulty hard
python -m notebooklm generate flashcards
python -m notebooklm generate mind-map
python -m notebooklm generate study-guide
```

## 🔑 Notebook ID
`d1afe08c-75f7-41b8-aa46-296a58fbb385`

## 🔧 Setup
See the [notebooklm-integration](https://github.com/DatariusAI/notebooklm-integration)
repo for full installation and authentication instructions.
