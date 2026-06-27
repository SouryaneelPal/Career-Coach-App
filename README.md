### ⚡ Quick Start: How to Run the App

Get your local instance up and running in less than 5 minutes.

#### 📋 Prerequisites

* Make sure you have **Python 3.10+** installed on your machine.
* Download and install **[Ollama](https://ollama.com/)** (if running locally for free).

#### 🛠️ Step-by-Step Setup

1. **Clone the Repository:**
```bash
git clone https://github.com/YOUR_USERNAME/career-coach-ai-agent.git
cd career-coach-ai-agent

```


2. **Set Up a Virtual Environment:**
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

```


3. **Install Dependencies:**
```bash
pip install -r requirements.txt

```


4. **Configure Your Environment Variables:**
Create a `.env` file in the root directory:
```text
USE_OLLAMA=true
OLLAMA_MODEL_NAME=llama3.2
OLLAMA_API_BASE=http://localhost:11434

```


5. **Start the AI Model:**
```bash
ollama run llama3.2

```


6. **Launch the Streamlit App:**
```bash
streamlit run app.py

```



---

Once you commit this `README.md` file alongside your code and push it to GitHub using `git add README.md`, `git commit -m "Add README"`, and `git push`, your profile will look completely professional and ready for the public!