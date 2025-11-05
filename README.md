# 🤖 로컬 LLM 기반 AI 챗봇 "AssistantK"

개인 프라이버시를 지키며 채팅, 이미지 생성, 일정 관리를 모두 처리할 수 있는 100% 로컬 구동 AI 어시스턴트입니다. (2025-XX-XX)

## ✨ 주요 기능
* **통합 채팅:** 일반 대화, 이미지 생성, 일정 관리를 단일 UI에서 처리
* **100% 로컬 AI:** Ollama (LLM)와 ComfyUI (이미지 생성)를 사용
* **일정 관리 (CRUD):** 로컬 PostgreSQL과 연동하여 일정 생성/조회/삭제
* **지능형 NLU:** LLM을 이용한 의도 분류, 일정 파싱, 안전성 검사
* **고급 UI/UX:** 다크/라이트 모드, 플로팅 블러 디자인, 애니메이션 적용

## 💻 핵심 기술
* **Backend:** Python Flask
* **AI:** Ollama, ComfyUI
* **Database:** PostgreSQL
* **Frontend:** HTML, CSS, Vanilla JavaScript (Fetch)

## 🔧 실행 방법

**1. Backend (Flask Server)**

```bash
# (학교 서버에서)
pip install -r requirements.txt
python AssistantK.py
