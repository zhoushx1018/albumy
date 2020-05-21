# Albumy

《[Flask Web 开发实战](http://helloflask.com/book)》 第8章个人博客

Demo: http://Albumy.helloflask.com

![Screenshot](http://helloflask.com/screenshots/Albumy.png)


## 安装

git clone源码
```
$ git clone https://github.com/greyli/Albumy.git
$ cd Albumy
```

安装依赖
```
$ pip3 install -r requirements.txt
```

预先在DB生成假记录
```
$ flask forge

```

启动http服务

```
## Running on http://0.0.0.0:8080/
$ flask run -h 0.0.0.0  -p 8080 
```

在本地尝试访问服务

```
$ curl http://localhost:8080
```

通过浏览器访问服务

```
http://IP:8080
```








# Albumy

*Capture and share every wonderful moment.*

> Example application for *[Python Web Development with Flask](http://helloflask.com/en/book)* (《[Flask Web 开发实战](http://helloflask.com/book)》).

Demo: http://albumy.helloflask.com

![Screenshot](http://helloflask.com/screenshots/albumy.png)

## Installation

clone:
```
$ git clone https://github.com/greyli/albumy.git
$ cd albumy
```
create & activate virtual env then install dependency:

with venv/virtualenv + pip:
```
$ python -m venv env  # use `virtualenv env` for Python2, use `python3 ...` for Python3 on Linux & macOS
$ source env/bin/activate  # use `env\Scripts\activate` on Windows
$ pip install -r requirements.txt
```
or with Pipenv:
```
$ pipenv install --dev
$ pipenv shell
```
generate fake data then run:
```
$ flask forge
$ flask run
* Running on http://127.0.0.1:5000/
```
Test account:
* email: `admin@helloflask.com`
* password: `helloflask`

## License

This project is licensed under the MIT License (see the
[LICENSE](LICENSE) file for details).
