# ledger-api

FastAPI와 Supabase PostgreSQL을 연결한 가계부 API입니다.

## 주요 기능
- 계좌 생성 및 조회
- 거래 생성
- 계좌별 거래 중첩 조회
- 카테고리별 지출 집계

## 기술
- FastAPI
- SQLAlchemy
- PostgreSQL
- Supabase
- Render

## 실행
uvicorn main:app --reload