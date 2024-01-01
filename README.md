# fitness-saporter

- ランニングマシーン等のワークアウト結果の写真を送信することで自動的に集計する
  - gemini pro vision
  - go
  - cloud run
  - cloud deploy
  - google cloud storage
  - bigquery

## int for developer

1. install direnv

```bash
brew install direnv
```

2. init app

```bash
make init
```

3. run server

```bash
make run
```

4. health check

```bash
curl http://localhost:8080/healthcheck
```
