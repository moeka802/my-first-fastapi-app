# ライブサーバーの起動
```
uvicorn main:app
```

- main: main.pyファイル
- app: main.py内部に記載したappのこと 
- --reload: コードの変更があった時にサーバーを自動で再起動。