# rag-udemy
Learning repository for RAG Course: https://www.udemy.com/course/ultimate-rag-bootcamp-using-langchainlanggraph-langsmith

### Install UV
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
### Initialize UV Project

Open terminal and execure the command:
```bash
uv init
```
### Create virtual environment

Refer to UV Documentation at: https://docs.astral.sh/uv/guides/install-python/ to understand how specific python versions can be installed

Check the version specified in .python-version. If you are using penv to manage python environments, then change it to a version of python already installed in pyenv

Create a virtual environment use the command

```bash
uv venv
```

Activate the virtual environment with 

```bash
source .venv/bin/activate
```

Install dependencis in virtual environment with a requirements.txt file
```bash
uv add -r requirements.txt
```

To generate a lock file
```bash
uv export --format requirements.txt
```