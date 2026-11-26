# ComposeAI - AI-powered email composition

## Architecture

```mermaid
flowchart LR
  U[Email draft] --> UI[ComposeAI interface]
  UI --> L[LLM rewriting service]
  L --> O[Tone, clarity, and style suggestions]
  O --> U
```
A powerful AI-powered assistant for rewriting and improving emails with better tone, clarity, and professionalism.

## 🌟 Features
- Rewrites emails to sound more formal, polite, or concise.
- Improves grammar, tone, and readability.
- Allows customization of the tone (formal, casual, persuasive, etc.).
- Runs directly inside a Jupyter Notebook.

## 📂 Project Structure
├── Email_rewriter.ipynb   # Main notebook

└── README.md              # Project documentation
 
## ⚡ Installation & Setup

### 1. Clone the repository:
```bash
git clone https://github.com/AryaLolusare2712/ComposeAI.git
cd ComposeAI
```

### 2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies:
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook:
```bash
jupyter notebook
```
