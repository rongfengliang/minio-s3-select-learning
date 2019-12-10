# minio select api learning

> use python3 venv  && integration with prometheus

## How to Running

* init venv

```code
python3 -m venv venv
```

* active venv

```code
source venv/bin/activate
```

* install deps

```code
pip install -r requirements.txt
```

or 

```code
pip install boto3 -i https://mirrors.aliyun.com/pypi/simple/
```

* some demo files

```code
demo.json
```

* upload json to minio

> can use minio mc or browser

* do search

```code
python select.py2
```

* exec python 

cmd:
```code
python select.py2
```
output result

```code
python select.py2
{"dir_name":"important_docs","files":[{"name":"."},{"name":".."},{"name":".aws"},{"name":"downloads"}]}

Stats details bytesScanned: 
300
Stats details bytesProcessed: 
300
```
