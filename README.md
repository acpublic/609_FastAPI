# FastAPI
## https://fastapi.tiangolo.com/ja/tutorial/
### インストール 
$ pip install "fastapi[all]"

### ローカル起動
$ uvicorn main:app --reload

### 外部起動
$ uvicorn main:app --host 0.0.0.0 --port 8000

### ローカルアクセス
http://127.0.0.1:8000

http://127.0.0.1:8000/docs

http://127.0.0.1:8000/redoc
