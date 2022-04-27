# Node.jsの公式イメージである「node:16.14.2」をDockerHubからダウンロード
FROM node:16.14.2

# コンテナ内の作業ディレクトリを指定
WORKDIR /usr/src/app/

# 必要パッケージをインストール
RUN npm install -g npm && \
    npm install -g @vue/cli

# サーバーを起動
CMD [ "npm", "run", "serve" ]
