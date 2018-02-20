Document Template from Sphinx
---

Sphinxで始めるヒアドキュメントなドキュメント  

### How to use
HTMLなドキュメントの生成  
```sh
make html
```

### How to development
オートリロードを有効にして開発作業をらくらくに！  
```sh
make livehtml
```
http://localhost:8000/ にアクセスすれば確認できる  
ファイルの更新を検知して勝手にビルドし直してくれる  

### Requires
使い始めるのに必要の者たち
- Python3
- Pip
- Pandoc
```sh
pip install -r requirements.txt
```

