# mysqlの公式イメージである「mysql」をDockerHubからダウンロード
FROM mysql

# ポート番号3306で起動
EXPOSE 3306

ADD ./my.cnf /etc/mysql/conf.d/my.cnf

# サーバーを起動
CMD ["mysqld"]
