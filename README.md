# DE 구조적 API Session

1. ec2 실행
2. 하둡 실행
```shell
    hadoop/sbin/start-dfs.sh
    hadoop/sbin/start-yarn.sh
```

3. 실습 파일 clone
```shell
    cd ~
    mkdir structured-api
    cd structured-api
    git clone https://github.com/moggaa/Spark-The-Definitive-Guide.git
```

4. hdfs 업로드
```shell
    hdfs dfs -put structured-data/ /usr/ubuntu/
```