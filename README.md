Setup
# 1. Clone / unzip the project
cd kisaan-ai

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your OpenAI API key
cp .env.example .env
# Edit .env and set: OPENAI_API_KEY=sk-...

## Usage

CLI Pipeline (test mode) =  python src/main.py

(Runs all 4 agents with a hardcoded test farmer profile and prints results.)

Web UI =  streamlit run src/app.py

(Opens a browser form where farmers enter their profile and get a full season plan.)
