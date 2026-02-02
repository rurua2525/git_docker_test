ターミナルを起動する（PowerShell または コマンド プロンプト）
Docker が利用できることを確認します
docker --version
OWASP Juice Shop のイメージを事前取得します（オフライン実行のため）
docker pull bkimminich/juice-shop
コンテナを起動する
docker run --rm -p 3000:3000 bkimminich/juice-shop
ブラウザで以下にアクセスし、画面が表示されることを確認します
http://localhost:3000/
