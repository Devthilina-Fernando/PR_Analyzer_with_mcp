# PR_Analyzer_with_mcp

# initializing uv
uv init

# Create environment
uv venv

# Activate the environment
.venv\Scripts\activate

uv add "mcp[cli]"

# Install dependancies
uv add "mcp[cli]" requests python-dotenv notion-client

# Install requirements
uv pip install -r requirements.txt