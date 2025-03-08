# 베이스 이미지 설정
FROM python:3.14

# 작업 디렉토리 설정
WORKDIR /usr/src/app

# 의존성 파일 복사
COPY requirements.txt ./

# 의존성 설치
RUN pip install --no-cache-dir -r requirements.txt

# FastAPI와 Uvicorn 설치
RUN pip install fastapi uvicorn[standard]