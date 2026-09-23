# B6-2 글을 쓰고·보고·고치고·지울 수 있는 게시판형 웹 서비스 만들기

코딧세이 AI 올인원 본과정 B6-2 미션 저장소입니다.

## 범위
FastAPI+SQLAlchemy+SQLite·Jinja2 SSR·레이어 분리(라우터/서비스/저장소)·PRG 패턴

## 개발 환경
Python 3.10 이상을 사용합니다. 직접 추가할 외부 의존성은 fastapi, uvicorn, sqlalchemy, jinja2, python-multipart로 제한합니다.
필수 의존성 목록은 requirements.txt에 있습니다. 확인한 패키지 버전과 서버 실행 명령은 구현 후 기록합니다.

### 새 환경에서 준비

Git을 설치한 뒤 새 기기에서 저장소를 받습니다.

```bash
git clone https://github.com/sarguments/b6-2-fastapi-board.git
cd b6-2-fastapi-board
```

Python 3.10 이상을 설치한 뒤 저장소 루트에서 실행합니다. 가상환경은 기기마다 새로 만듭니다.

```bash
python3 --version
python3 -m venv .venv
.venv/bin/python --version
.venv/bin/python -m pip install -r requirements.txt
```

현재 의존성 파일에는 원문 필수 패키지 이름만 있습니다. 실제 설치 버전과 서버 실행 명령은 앱 구현·검증 후 기록합니다.

## 준비 상태
Python 3.14.3 가상환경을 준비했습니다. 외부 의존성은 아직 설치하지 않았습니다. 게시판 기능과 계층 구조는 직접 작성합니다. 로그인·인증·모델 간 관계는 다음 미션에서 다룹니다.
