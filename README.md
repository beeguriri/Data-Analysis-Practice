# Data-Analysis-Practice
> [Toy Project] 회귀, 분류, 시계열분석 연습

<br>

## 설정

0. Python 기본설정
```shell
# 버전확인
$ python  # Python 3.10.10

# 설치목록 확인
$ pip list

#Package    Version
#---------- -------
#pip        23.0.1
#setuptools 65.5.0
#wheel      0.40.0

# wheel 설치되어있지 않았을 경우
$ pip install wheel

# list에 필요없는 파일이 설치되어있을 경우
$ pip freeze > req.txt
$ pip uninstall -r req.txt -y

```

1. Python 격리
```shell
# 가상환경 생성
$ python -m venv venv

# 가상환경 활성화
$ .\venv\Scripts\activate
# ctrl+shift+p => python interpreter => venv 설정

# 가상환경 내에 패키지 설치
$ (venv) pip install -r requirements.txt
```