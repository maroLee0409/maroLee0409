# 안녕하세요, 제조 현장에서 AI를 만드는 개발자입니다

스마트팩토리 솔루션 회사에서 MES·QMS 풀스택 개발로 시작해, 지금은 사내 GPU 서버에 LLM과 VLM을 직접 올리고 현장 문제에 붙이는 일을 합니다.
다음 목표는 금융 데이터와 AI를 함께 다루는 일입니다.

## 하는 일

- **온프렘 LLM 서빙**: 외부 API를 쓸 수 없는 환경에서 오픈소스 모델(Qwen 계열)을 vLLM으로 서빙하고, 사내 다른 팀의 PoC 요청을 받아 연동까지 맡았습니다.
- **VLM 현장 적용**: 제조 품질검사 차트 판독과 산업안전 관제에 쓸 모델을 직접 비교·평가하고 골랐습니다. LoRA 파인튜닝도 다룹니다.
- **RAG**: 법령·매뉴얼 문서를 근거로 답하고, 근거가 없으면 답하지 않는 챗봇을 만들었습니다(Qdrant, MCP).
- **제조 시스템**: MES·QMS 유지보수, 디지털 트윈 플랫폼 모듈, 설비 예지보전 파이프라인.

회사 코드는 공개할 수 없어서, 아래에는 개인 프로젝트만 있습니다.

## 공개 프로젝트

| 프로젝트 | 내용 |
|---|---|
| [claude-remote-computer](https://github.com/maroLee0409/claude-remote-computer) | API가 없는 Windows 프로그램을 Claude Code가 화면을 보고 직접 조작하게 하는 도구. 의존성은 Pillow 하나 |
| [korea-rnd-rag-chatbot](https://github.com/maroLee0409/korea-rnd-rag-chatbot) | 연구행정 매뉴얼·법령 기반 RAG 챗봇. 벡터 검색과 조문·페이지 조회 도구를 함께 쓰고 출처를 표시 |
| [Token_Status](https://github.com/maroLee0409/Token_Status) | Claude Code·Codex·Gemini CLI 사용량을 트레이에 실시간으로 보여주는 Windows·macOS 앱 |
| [rnd-grant-search](https://github.com/maroLee0409/rnd-grant-search) | 정부·공공 지원사업 공고를 6개 소스에서 모아 매일 리포트로 만드는 도구. 표준 라이브러리만 사용 |

## 비공개로 진행 중

- **규칙 기반 자동매매 시스템**: 자산 통합 대시보드, 추세필터·듀얼모멘텀 전략, 백테스트, 주문 검증기와 킬 스위치, 텔레그램 운영 알림. 실주문은 이중잠금으로 막아 두고 모의 운용 중입니다. 개인 자산 정보를 걷어낸 공개본을 준비하고 있습니다.
- **F1 2026 시뮬레이터**: Panda3D로 만든 데스크톱 레이싱 게임.

## 주로 쓰는 것

Python · C#/.NET · vLLM · Qwen · LoRA · Qdrant · Docker · Claude Code
