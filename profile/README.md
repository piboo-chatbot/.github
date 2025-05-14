# Piboo

# 👥 팀 소개
> SK네트웍스 Family AI 캠프 11기 3차 프로젝트 <br/>
> 팀 명:  <br/>
> 기간: 2025.05.02 - 2025.05.15 <br/>

## 👤팀원 소개

<table align="center">
  <thead>
    <td align="center">
      <img src="https://github.com/kimseoungji0801.png" width=200 alt="seongji"/><br />
      <a href='https://github.com/kimseoungji0801'>김성지</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/yugyeongh.png" width=200 alt="yugyeong"/><br />
      <a href='https://github.com/yugyeongh'>현유경</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/Ohjunghh.png" width=200 alt="junghyun"/><br />
      <a href='https://github.com/Ohjunghh'>오정현</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/misnog-hub.png" width="200" alt="misong"/><br />
      <a href='https://github.com/misnog-hub'>백미송</a><br />
    </td>
  </thead>
</table>

<br/><br/>

# 🩷 프로젝트 개요

### 🌸 PiBoo: 성분부터 궁합까지, 똑똑한 화장품 도우미
사용자의 피부 타입, 피부 고민, 보유 중인 화장품 등의 정보를 바탕으로, 궁합이 잘 맞는 기초 화장품이나 스킨케어 제품을 추천 서비스를 개발해 단순한 제품 매칭을 넘어, 화장품 성분 분석과 실제 사용자 리뷰 데이터를 기반으로 한 신뢰도 높은 추천을 제공하는 챗봇 

## ☝🏻 프로젝트 필요성
최근 화장품을 선택할 때 제품의 성분을 중요시하는 소비자가 급격히 증가했습니다. 하지만 대다수의 소비자들은 화장품 성분의 구체적인 효능과 서로 다른 제품 간의 궁합에 대해서 명확하게 이해하지 못하고 있습니다. 성분에 대한 잘못된 정보나 부적절한 제품 조합은 피부 트러블 등의 문제를 유발할 수 있습니다. 이에 정확한 성분 정보 제공과 올바른 화장품 사용 가이드를 제공할 수 있는 도구의 필요성이 대두되었습니다.

## ⭐ 프로젝트 목표
1. 화장품 성분 정보를 사용자에게 명확하고 쉽게 제공하여 올바른 이해를 도움
2. 사용자가 보유한 화장품과의 궁합 분석을 통해 좋은 조합을 추천하고, 나쁜 조합에 대해서는 경고를 제공하여 피부 문제 예방에 도움
3. 맞춤형 성분 분석과 제품 추천을 통해 사용자가 더욱 건강하고 효율적인 피부 관리가 가능하도록 지원

<br/><br/>

# ✅ 기술 스택 & 사용한 모델

## 🔩 기술 스택
<table align="center">
  <tbody>
    <tr>
      <td><strong>Frontend</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><strong>Backend</strong></td>
      <td>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><strong>AI/LLM & RAG</strong></td>
      <td>
        <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge">
        <img src="https://img.shields.io/badge/ChromaDB-FFCC00?style=for-the-badge">
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
        <img src="https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge">
        <img src="https://img.shields.io/badge/QLoRA-8BC34A?style=for-the-badge">
        <img src="https://img.shields.io/badge/RunPod-EE4C2C?style=for-the-badge">
      </td>
    </tr>
  </tbody>
</table>

<br/><br/>

## 🤖 사용한 모델
<table>
  <thead>
    <tr>
      <th>역할</th>
      <th>모델</th>
      <th>플랫폼</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>문서 임베딩</td>
      <td>all-MiniLM-L6-v2</td>
      <td>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
      </td>
    </tr>
    <tr>
      <td>QA 데이터 생성 (RAG 기반)</td>
      <td>GPT-4o</td>
      <td>
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
      </td>
    </tr>
    <tr>
      <td>파인튜닝 사전 학습 모델</td>
      <td>llama-3-Korean-Bllossom-8B</td>
      <td>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
      </td>
    </tr>
  </tbody>
</table>



# 시스템 아키텍처
### 📌 프로젝트 WBS (작업 분해 구조표)

| 단계 | 주요 작업 |
|------|----------|
| 1 | 프로젝트 기획 및 주제 확정 |
| 2 | 데이터 수집 (리뷰, 성분 등) | 
| 3 | 데이터 전처리 및 정제 | 
| 4 | RAG 파이프라인 연결 | 
| 5 | LLM 모델 선택 (Blossom 3B) | 
| 6 | 테스트 질의셋 작성 및 평가 | 
| 7 | QLoRA 세팅 및 파인튜닝 |
| 8 | Streamlit 챗봇 UI 구현 |
| 9 | 통합 테스트 및 튜닝 | 
| 10 | 발표 자료 / 보고서 정리 | 

### 요구사항 명세서
## 📄 문서 기반 질의응답 요구사항 정리 (고칠게 있으면 고쳐야함)

### ✅ 문서 저장 및 검색
- 화장품,화장품 성분 설명, 리뷰  등의 문서를 벡터화하여 ChromaDB에 저장
- ChromaDB 등 벡터DB를 사용해 유사도 기반 검색 수행

### ✅ 문서 메타데이터 관리
- 문서 유형, 브랜드, 제품명 등 메타데이터 태깅
- 조건 필터링 및 고속 검색에 활용

### ✅ LLM 통합
- 검색된 문서 내용을 기반으로 LLM이 자연어 응답 생성
- GPT 계열 모델과 Blossom 모델을 사용하여 파인튜닝 또는 RAG 구성

### ✅ 응답 품질 보완
- 리뷰/성분 데이터를 통한 응답 품질 보완

### ✅ 파인튜닝 활용
- QLoRA로 화장품 궁합 추천, 성분 설명, 사용 주의사항 데이터 학습
- 프롬프트 기반 QA 외에도 지식 삽입 방식으로 정제된 응답 유도

### ✅ 응답 구조화
- 질문에 대한 답변을 단락, 리스트, 강조 키워드 형태로 구성
- "이유 → 추천 → 주의사항" 구조 유지

### ✅ 챗봇 UI 요구사항
- Streamlit 기반 모바일 친화형 인터페이스 제공
- 사용자가 자연어로 질문 → 챗봇이 응답 형태로 출력

### ✅ 대화 기억 기능
- 사용자가 과거에 입력한 보유 화장품, 피부 타입 등을 기억
- 연속 질문에서도 일관된 맥락 유지

### ✅ 응답 속도
- 문서 검색 + LLM 응답 합산 시간 5초 이내 목표
- 필요 시 프리페칭 또는 캐시 적용

7. 수집한 데이터 및 전처리 요약
8. DB 연동 구현 코드 (링크첨부)
9. 테스트 계획 및 결과 보고서
10. 진행 과정 중 프로그램 개선 노력
11. 수행결과(테스트/시연 페이지)
12. 한 줄 회고

