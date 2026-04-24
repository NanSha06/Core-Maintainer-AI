# CoreMaintainerId

**CoreMaintainerId** is a Streamlit web application for analyzing contributor networks in open‑source GitHub repositories.  
It identifies *core maintainers* and *peripheral contributors* using machine learning and network analysis.

## 🚀 Features
- Fetches contributor and commit data from GitHub repositories via the GitHub API
- Builds a social graph using **NetworkX**
- Applies clustering and classification models (**scikit‑learn**) to detect key maintainers
- Visualizes collaboration patterns with **Plotly** and **Seaborn**
- Streamlit interface for easy interaction and configuration

## 🧠 Tech Stack
- **Python 3.11+**
- **Streamlit** for UI
- **NetworkX**, **scikit‑learn**, **pandas**, **numpy** for analytics
- **Plotly**, **matplotlib**, **seaborn** for visualization
- **PyGithub** for GitHub API access

## ⚙️ Installation

```bash
git clone <repo_url>
cd CoreMaintainerId
pip install -r requirements.txt
```

## ▶️ Usage

```bash
streamlit run app.py
```

Then open your browser at http://localhost:8501.

## 🔑 Authentication

For higher GitHub API rate limits, provide a **Personal Access Token** in the Streamlit sidebar (optional).  
Never share your token publicly or commit it to the repository.

## 📁 Project Structure

```
CoreMaintainerId/
├── app.py               # Streamlit main application
├── main.py              # Entry file (simple runner)
├── pyproject.toml       # Project metadata and dependencies
├── requirements.txt     # Auto‑generated dependencies list
└── (various hidden and config files)
```

## 🧩 Future Improvements
- Modularize codebase (data, models, visualizations)
- Add caching optimizations and rate‑limit handling
- Add CI and test suite
- Add documentation and examples

## 🪪 License
This project is for educational and research purposes.

---
*Generated README and requirements automatically.*
