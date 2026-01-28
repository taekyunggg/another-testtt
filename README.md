# eigenx-tee-python-app

## Development

### Setup & Local Testing
```bash
pip install -r requirements.txt
cp .env.example .env
python src/main.py
```

### Docker Testing
```bash
docker build -t another-testtt .
docker run --rm --env-file .env another-testtt
```
