
## 1. Start MySQL Server
```bash
sudo /usr/local/mysql/support-files/mysql.server start
```

## 2. Activate Virtual Environment & Run Backend
```bash
source .venv/bin/activate
uvicorn main:app --reload
```