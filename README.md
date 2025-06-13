# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)

---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit






streamlit run app.py

pipenv shell
streamlit run lawyer.py
python -m streamlit run lawyer.py
pipenv run streamlit run lawyer.py



Remove-Item -Recurse -Force .git


echo "# RAGLLM" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/7rohitk/RAGLLM.git
git push -u origin main