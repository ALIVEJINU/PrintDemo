# Python Print Examples with Rich

이 프로젝트는 **Python의 다양한 `print` 사용법**과
**`rich` 라이브러리**를 활용한 컬러풀한 출력 예제를 담고 있습니다.

---

## 📌 주요 기능

### 1. 기본 `print` 사용법

* 여러 값 출력 (콤마, `sep`, `end` 옵션 활용)
* f-string, `format()`, `%` 포맷팅
* 멀티라인 출력 및 계산식 포함

### 2. `rich` 활용

* 컬러/스타일 출력
* 패널(박스) 출력
* 테이블 출력
* `print`와 동일하게 `sep`, `end` 옵션 지원

---

## 🚀 실행 방법

1. 가상환경 생성 및 활성화 (선택 사항)

   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # Windows
   source .venv/bin/activate  # macOS/Linux
   ```

2. 필요한 패키지 설치

   ```bash
   pip install -r requirements.txt
   ```

3. 코드 실행

   ```bash
   python main_print_v1.py
   python main_print_v2.py
   ```

---

## 📂 파일 구조

```
project/
 ├── main_print_v1.py   # 기본 print 예제
 ├── main_print_v2.py   # rich 활용 예제
 ├── requirements.txt   # 의존성 패키지
 └── README.md
```

---

## 📦 Requirements

```text
sttokens==3.0.0
colorama==0.4.6
comm==0.2.3
debugpy==1.8.17
decorator==5.2.1
executing==2.2.1
ipykernel==6.30.1
ipython==9.6.0
ipython_pygments_lexers==1.1.1
jedi==0.19.2
jupyter_client==8.6.3
jupyter_core==5.8.1
markdown-it-py==4.0.0
matplotlib-inline==0.1.7
mdurl==0.1.2
nest-asyncio==1.6.0
packaging==25.0
parso==0.8.5
platformdirs==4.4.0
prompt_toolkit==3.0.52
psutil==7.1.0
pure_eval==0.2.3
Pygments==2.19.2
python-dateutil==2.9.0.post0
pywin32==311
pyzmq==27.1.0
rich==14.1.0
six==1.17.0
stack-data==0.6.3
tornado==6.5.2
traitlets==5.14.3
wcwidth==0.2.14
```

---

## ✨ 예제 실행 결과

```text
Hello, Python!
Name: Alice age: 25 Score: 95.5
My name is Alice, I am 25 years old, score: 95.5
...

# rich 출력 (컬러/패널/테이블 포함)
```

---

👉 이 프로젝트는 Python 출력 기본기를 정리하고,
터미널에서 컬러풀한 결과를 쉽게 확인할 수 있도록 도와줍니다.
