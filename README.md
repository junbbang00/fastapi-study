# 🚀 FastAPI & DevOps 기초 학습 저장소

데브옵스(DevOps) 및 엠엘옵스(MLOps) 엔지니어로 성장하기 위한 첫걸음으로, FastAPI를 활용한 백엔드 아키텍처와 인프라 기초를 학습하고 기록하는 저장소입니다.

## 🛠️ 개발 환경 및 기술 스택
- **Language:** Python 3.10
- **Framework:** FastAPI
- **Server:** Uvicorn (ASGI)
- **Environment:** 파이썬 기본 가상환경 (`venv`)

## 💡 주요 고려 사항 및 배운 점 (Troubleshooting)
- **무거운 아나콘다(Anaconda) 대신 가벼운 `venv` 도입:** FastAPI 웹 개발 특성에 맞춰 메모리와 용량을 많이 차지하는 아나콘다 대신, 프로젝트 폴더 내부에 독립적인 `venv` 가상환경을 구축하여 프로젝트 경량화 및 직관적인 폴더 구조 확립.
- **포트 충돌 및 실행 경로 트러블슈팅:**
  `uvicorn` 서버 실행 시 모듈 로드 에러(`Could not import module "main"`)를 경험하며, 터미널의 현재 작업 디렉터리(PWD)와 파이썬 실행 파일 경로 간의 관계를 파악하고 파일 위치 조정을 통해 해결함.