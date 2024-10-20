# AI Web Scrape

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Setup

### 1. Download Dependencies

- **Chrome Driver:** Download the latest Chrome driver from [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/#stable). Ensure that the Chrome version matches the driver version.
- **Ollama:** Download Ollama from the [Ollama GitHub repository](https://github.com/ollama/ollama). Follow the instructions there to install it and pull the desired model.

### 2. Create a Virtual Environment

To keep your project dependencies isolated, it's recommended to use a virtual environment. Run the following commands in your project directory:

```bash
python -m venv .venv
```

Activate the virtual environment:

- **Windows (Git Bash):**
  ```bash
  source .venv/Scripts/Activate
  ```
- **Windows (Command Prompt):**
  ```cmd
  .venv\Scripts\activate
  ```
- **macOS/Linux:**
  ```bash
  source .venv/bin/activate
  ```

### 3. Install Required Packages

Make sure you have a `requirements.txt` file in your project directory with the necessary dependencies. To install the required packages, run:

```bash
pip install -r requirements.txt
```

### 4. Run the Application

To start the Streamlit app, run:

```bash
streamlit run main.py
```
