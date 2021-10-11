# jupyterlab-mysql_by_dockercompose

### 1, how to use this dev env
**you must delete jupyterlab-mysql_by_dockercompose/db/data01/readme.txt**
**you can adjust volumes in docker-compose.yml for your env**
```
git clone https://github.com/xianglishan/jupyterlab-mysql_by_dockercompose.git
rm jupyterlab-mysql_by_dockercompose/db/data01/readme.txt
cd jupyterlab-mysql_by_dockercompose
docker-compose up -d --build
```
then you can use jupyterlab in browser at `http://localhost:8888`

### 2, you can refer to my test files
**you can test by files in jupyterlab-mysql_by_dockercompose/notebook/work/**
