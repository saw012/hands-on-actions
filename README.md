# hands-on-actions
PythonでGitHub Actionsを試してみましょう。<br>
このリポジトリはサンプルですので、ご自身のGitHubのリポジトリにForkしてください。

## 構成
構成はこんな感じになっています。
  ```bash
  ├── .dockerignore
  ├── .github
  │   └── workflows
  │       └── python-app.yml → GitHub Actionsのワークフローのymlファイル
  ├── Dockerfile → チャレンジ問題用のDockerfile
  ├── README.md　→ このファイル
  ├── requirements.txt → pipのパッケージを定義
  ├── srcs
  │   └── app.py → pyhtonのソースコード
  └── test
      ├── __init__.py
      └── test.py → pythonのテストコード
  ```

# CIをスキップする場合
Commitメッセージに[skip ci]を追加してください。
