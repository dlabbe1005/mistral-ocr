## 1. Create conda env

```bash
conda create -n mistral-ocr python=3.10
conda activate mistral-ocr
```

## 2. pip install requirements
```bash
pip install -r requirements.txt
```

## 3. clone .env.sample and rename it to .env and change with credentials

Mistral OCR is not available on Azure. You can create an account and setup the API key at https://console.mistral.ai/ .