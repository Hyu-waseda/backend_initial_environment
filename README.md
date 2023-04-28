# backend_initial_environment

バックエンドの初期環境構築

- Python 3.10.9
- pip 23.1

## 起動方法

- 仮想環境の用意

```bash
cd backend
python3 -m venv .venv
```

- 仮想環境の起動

```shell
source .venv/bin/activate
```

- 必要なモジュールのインストール

```shell
pip install -r requirements.txt
```

- 起動

```shell
uvicorn main:app --reload
```

- アクセス

`localhost:8080/docs` or `localhost:8080/PATH`

## その他

- メモ
  - requirements.txtの作り方

	```shell
	pip freeze > requirements.txt
	```
