# Jeon Jiwon

**AI Service Developer / Python FastAPI Backend Developer**

AI 모델을 단순 호출하는 것보다, 모델 결과를 실제 서비스 데이터와 연결하고 검증 가능한 API 흐름으로 만드는 데 집중하고 있습니다.  
FastAPI 기반 백엔드, ChromaDB 기반 RAG, 임베딩 검색, Threshold 평가, Docker 기반 실행 환경을 중심으로 프로젝트를 진행했습니다.

---
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=160&text=Jeon%20Jiwon&animation=twinkling&fontColor=ffffff&fontSize=45" />
</div>

<h2>🛠️ Tech Stacks</h2>

<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=FastAPI&logoColor=white">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=SQLAlchemy&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white">
  <br/>
  <img src="https://img.shields.io/badge/ChromaDB-5B5BD6?style=flat&logoColor=white">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logoColor=white">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black">
  <br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=black">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=black">
  <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=Amazon%20AWS&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=Linux&logoColor=black">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=GitHubActions&logoColor=white">
</div>

## Core Strength

| Area | Experience |
| --- | --- |
| AI Backend | FastAPI 기반 AI Service API 설계, Main Backend 연동 구조 정리 |
| RAG / Vector Search | ChromaDB, 임베딩 모델, Cosine Similarity, Threshold 기반 검색 흐름 구현 |
| AI Evaluation | 이미지 유사사례 검색, RAG 검색 정확도, 모델/파라미터 비교 설계 |
| Backend | REST API, SQLAlchemy, MySQL, 인증/검색/필터링 API 구현 경험 |
| Infra | Docker, Docker Compose, AWS EC2 배포 흐름 경험 |

---

## Featured Projects

### 1. TUKTAK

**집수리 AI 견적 및 시공자 매칭 플랫폼**

사용자가 수리 사진과 설명을 입력하면 AI 견적서, 리스크 리포트, 역경매 매칭으로 이어지는 서비스입니다.  
저는 AI 백엔드와 RAG/유사도 검색 설계 구현을 중심으로 참여했습니다.

**Key Contribution**

- Risk Report 도메인 모델 및 API 구조 구현
- Main Backend와 AI Service 연동 구조 설계
- ChromaDB 기반 RAG 리스크 리포트 검색 흐름 설계 및 구현
- 이미지 유사사례 검색 Threshold 설계
- Nomic Embed Vision 기반 이미지 임베딩 검색 구조 검토
- AI 견적 결과와 리스크 리포트가 이어지는 서비스 흐름 정리

**Links**

- Project Summary: https://github.com/JW020799/tuktak-project-summary
- AI Service Practice: https://github.com/JW020799/tuktak-ai-service-practice
- Backend: https://github.com/TUKTAKxAI/TUKTAK_Backend
- AI Service: https://github.com/TUKTAKxAI/TUKTAK_AI_Service
- Frontend: https://github.com/TUKTAKxAI/TUKTAK_Frontend

---

### 2. Investment Agent Report

**RAG + Agent Workflow 기반 개인 투자 리포트 데모**

뉴스와 재무 데이터를 수집하고, ChromaDB RAG 검색과 LangGraph Agent Workflow를 통해 투자 참고 리포트를 생성하는 개인 프로젝트입니다.  
데이터 수집, 임베딩, 벡터 검색, Agent 분석, Streamlit UI, FastAPI API를 하나의 흐름으로 연결했습니다.

**Key Features**

- Google News RSS 기반 뉴스 수집
- yfinance 기반 재무 데이터 수집 및 실패 처리
- Sentence-Transformers 임베딩 생성
- ChromaDB 기반 RAG 검색
- LangGraph 기반 Agent Workflow 구성
- Streamlit UI와 FastAPI API 제공
- SQLAlchemy 기반 리포트 저장/조회 API 구현

**Repository**

- https://github.com/JW020799/investment-agent-report

---

### 3. GIUT

**공공데이터와 AI를 활용한 지역 행사 탐색 및 추천 코스 서비스**

한국관광공사 API, OpenAI API, Naver Map API를 연동해 지역 행사 검색과 AI 추천 코스를 제공하는 풀스택 팀 프로젝트입니다.

**Key Contribution**

- FastAPI 기반 백엔드 API 구현
- 회원가입/로그인 기능 구현
- 행사 검색 및 필터링 API 구현
- 공공데이터 API와 서비스 데이터 흐름 연동
- Docker Compose 기반 로컬/배포 실행 흐름 경험

**Repository**

- https://github.com/Baikseungwoo/IBM-x-RedHat-Midterm-Project

---

## Tech Stack

**Language**  
Python, JavaScript

**Backend**  
FastAPI, REST API, SQLAlchemy, MySQL

**AI / RAG**  
ChromaDB, Sentence-Transformers, Nomic Embed Vision, Ko-SRoBERTa, CLIP, DINOv2, LangGraph

**Frontend**  
React, Streamlit

**Infra / Collaboration**  
Docker, Docker Compose, AWS EC2, Git, GitHub Branch/PR Workflow

---

## Direction

AI 모델 결과를 서비스 API, 데이터베이스, 벡터 검색, 사용자 화면까지 연결하는 AI 서비스 개발자로 성장하고 있습니다.  
다음 단계로는 RAG 검색 품질 개선, LLM 기반 리포트 생성, FastAPI 기반 AI 서비스 운영 구조, Docker/AWS 배포 자동화를 중심으로 확장하고 있습니다.
