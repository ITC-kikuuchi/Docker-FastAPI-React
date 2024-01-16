# Docker-FastAPI-React
Dockerを使用したFastAPI,React の開発環境の構築

# 目的
現在システム開発で使用している言語に加え、別の言語、フレームワークの技術と知識を習得するため

# バックエンド
プロジェクトの作成  
docker/python 配下にフォルダ app を作成する。  
既存のプロジェクトは app にクーロンする。  

以下にアクセスして画面に Hello World が表示されることを確認する。  
(device_management_back リポジトリをクーロンした場合)  
http://localhost:3001/

# フロントエンド
プロジェクトの作成  
docker フォルダと同階層にフォルダ front を作成する。  
既存のプロジェクトは front にクーロンする。  
恐らく、package.json が front 配下に存在しない場合、React の画面は表示されないはず…。  
ごめんなさい。まだ node_module のインストール方法がわかりません。  
恐らく`npm -install` 的な感じなのを叩けばいいのかと…。

プロジェクト作成後に以下にアクセスして、React の画面が表示されること。  
http://localhost:3000/

# Python コンテナの入り方
`docker-compose exec python bash`

# node コンテナの入り方
`docker-compose exec node sh`

