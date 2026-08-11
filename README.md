# Jeon Jiwon

AI Service Developer / Python Backend Developer

사용자 입력을 구조화하고, 임베딩 검색과 RAG 흐름으로 서비스 결과를 만드는 AI 백엔드 개발을 공부하고 있습니다.  
FastAPI 기반 API 구현, ChromaDB 기반 벡터 검색, RAG 리스크 리포트, 이미지 유사사례 검색 평가를 중심으로 프로젝트를 진행했습니다.

## Focus

- AI 서비스 백엔드: FastAPI, REST API, SQLAlchemy, MySQL
- RAG / Vector Search: ChromaDB, Embedding, Cosine Similarity, Threshold 설계
- AI Evaluation: 이미지 유사사례 검색 평가, RAG 검색 정확도 검증
- Infra Practice: Docker, Docker Compose, AWS EC2 배포 흐름 학습

## Projects

### TUKTAK

집수리 AI 견적 및 시공자 매칭 플랫폼입니다.  
사용자가 수리 사진과 설명을 입력하면 AI 견적서, 리스크 리포트, 시공자 매칭으로 이어지는 서비스입니다.

My Contributions

- Risk Report 도메인 모델 및 API 구조 구현
- Main Backend와 AI Service 연동 구조 설계
- ChromaDB 기반 RAG 리스크 리포트 검색 흐름 설계 및 구현
- 이미지 유사사례 검색 Threshold 설계
- Nomic Embed Vision 기반 이미지 임베딩 검색 구조 검토
- AI 견적 결과와 리스크 리포트가 이어지는 서비스 흐름 정리

Repositories

- Backend: https://github.com/TUKTAKxAI/TUKTAK_Backend
- AI Service: https://github.com/TUKTAKxAI/TUKTAK_AI_Service
- Frontend: https://github.com/TUKTAKxAI/TUKTAK_Frontend

### GIUT

공공데이터와 AI를 활용한 지역 기반 행사 탐색 및 추천 코스 서비스입니다.  
한국관광공사 API, OpenAI API, Naver Map API를 연동하고 FastAPI, MySQL, React, Docker Compose 기반으로 구현했습니다.

My Contributions

- FastAPI 기반 백엔드 API 구현
- 회원가입/로그인 기능 구현
- 행사 검색 및 필터링 API 구현
- 공공데이터 API와 서비스 데이터 흐름 연동
- Docker Compose 기반 로컬/배포 실행 흐름 경험

Repository

- https://github.com/Baikseungwoo/IBM-x-RedHat-Midterm-Project

### Investment Agent Report

뉴스와 재무 데이터를 기반으로 개인 투자 참고 리포트를 생성하는 AI Agent 데모 프로젝트입니다.  
Google News RSS, yfinance, Sentence-Transformers, ChromaDB, LangGraph, Streamlit, FastAPI를 연결해 데이터 수집부터 RAG 검색, Agent 분석, 리포트 생성까지 구현했습니다.

Key Features

- Google News RSS 기반 뉴스 수집
- yfinance 기반 재무 데이터 수집
- Sentence-Transformers 임베딩 생성
- ChromaDB 기반 RAG 검색
- LangGraph 기반 Agent Workflow 구성
- Streamlit UI와 FastAPI API 제공

## Tech Stack

Languages  
Python, JavaScript

Backend  
FastAPI, REST API, SQLAlchemy, MySQL

AI / RAG  
ChromaDB, Sentence-Transformers, Nomic Embed Vision, Ko-SRoBERTa, CLIP, DINOv2

Frontend  
React, Streamlit

Infra / Collaboration  
Docker, Docker Compose, AWS EC2, Git, GitHub, Branch/PR Workflow

## Learning Direction

AI 모델을 단순히 호출하는 것보다, 모델 결과를 서비스 데이터와 연결하고 검증 가능한 API 흐름으로 만드는 데 관심이 있습니다.  
앞으로는 RAG 검색 품질 개선, LLM 기반 리포트 생성, FastAPI 기반 AI 서비스 운영 구조, MLOps 배포 흐름을 중심으로 확장할 계획입니다.
