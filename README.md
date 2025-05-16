# RobotLabel
CityU Labeling Project

```bash
mamba create -n robotlabel python=3.11
mamba activate robotlabel
pip install -r requirements.txt
```

## Edit the `.env` File

Create a `.env` file in the root directory of the project and add the following content:

```
# OpenRouter Setting Up
OPENROUTER_API_KEY='xxxxxxxxxxxxxxx'

# Azure OpenAI Setting Up
AZURE_OPENAI_ENDPOINT='https://xxxxxxxxxxx.openai.azure.com/'
AZURE_OPENAI_DEPLOYMENT_NAME='xxxxxxx'
AZURE_OPENAI_API_VERSION='xxxxxxxxx'
AZURE_API_KEY='xxxxxxxxxx'

# Gemini 2.0 Flash
GEMINI_API_KEY='xxxxxxxxxxxxxx'
```