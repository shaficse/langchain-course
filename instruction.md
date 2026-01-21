# Instructions (Terminal Commands)

Use the following commands in order to set up the project, install dependencies,
run the app, and format imports.

## 1) Install uv (once)

```sh
pip3 install uv
```

## 2) Add project dependencies

```sh
uv add langchain
uv add python-dotenv black isort
uv add langchain-ollama
```

## 3) Run the app

```sh
uv run python main.py
```

## 4) Format imports with isort

```sh
uv run isort .
```
