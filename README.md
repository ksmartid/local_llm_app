# local_llm_app
local_llm_app


# 가상 환경 만들기
## uv 설치

```
uv 설치 curl -LsSf https://astral.sh/uv/install.sh | sh
```

# 파이썬 버전과 프롬프트 설정 
```
uv venv .venv --python 3.12 --prompt local_llm
```

## 가상환경 활성화 
source .venv/bin/activate


## 기본 패키지 설치
# uv pip install 패키지명 
uv pip install langchain ollama fastapi

## requirements.txt 사용해서 설치하는 방법 
# uv pip install -r 라이브러리목록파일.txt 
uv pip install -r requirements.txt

가상환경 비활성화 deactivate
