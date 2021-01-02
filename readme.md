- Git インストール
1. https://git-scm.com/download/win
から
Click here to download manually を実行してインストール

---

- エディタ インストール
1. https://azure.microsoft.com/ja-jp/products/visual-studio-code/
から
VSCode Windows版をインストール

以下の設定をする  
![環境構築1](https://user-images.githubusercontent.com/56077133/103454337-45330680-4d26-11eb-8147-712720ff22b8.png)

2. 以下プラグインの導入
    - Japanese Language Pack for Visual Studio Code
    - ESLint
    - Prettier - Code formatter

3. 既存のシェルを Git Bashに変更

![環境構築2](https://user-images.githubusercontent.com/56077133/103454339-48c68d80-4d26-11eb-85ba-d57e08b5b5ac.png)

---

- GitHubからプロジェクトをclone

1. 作業したいディレクトリで以下のコマンドをエディタのターミナルで実行  
git clone https://github.com/Re-Dive/react-sample.git

---

- docker インストール (https://zenn.dev/ymasaoka/articles/start-nodejs-development-with-docker)

1. https://hub.docker.com/editions/community/docker-ce-desktop-windows/  
Get Docker Desktop for Windwos をクリックしてダウンロード & インストール

2. 再起動

3. Linux カーネル更新プログラム パッケージをダウンロードする

4. docker-compose build

5. docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app react-sample"

6. docker-compose run node ls

7. docker-compose up でアプリを起動

8. http://localhost:3000/ で起動確認
