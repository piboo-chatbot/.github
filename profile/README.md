# 🌸 PiBoo: 성분부터 궁합까지, 똑똑한 화장품 도우미

# 👥 팀 소개
> SK네트웍스 Family AI 캠프 11기 3차 프로젝트 <br/>
> 팀 명:  <br/>
> 기간: 2025.05.08 - 2025.05.15 <br/>

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
      <img src="https://github.com/misong-hub.png" width="200" alt="misong"/><br />
      <a href='https://github.com/misong-hub'>백미송</a><br />
    </td>
  </thead>
</table>

<br/><br/>

# 🩷 프로젝트 개요

> 사용자의 피부 타입, 피부 고민, 보유 중인 화장품 등의 정보를 바탕으로, 궁합이 잘 맞는 기초 화장품이나 스킨케어 제품을 추천 서비스를 개발해 단순한 제품 매칭을 넘어, 화장품 성분 분석과 실제 사용자 리뷰 데이터를 기반으로 한 신뢰도 높은 추천을 제공하는 챗봇 

<br/>

## ☝🏻 프로젝트 필요성
최근 화장품을 선택할 때 제품의 성분을 중요시하는 소비자가 급격히 증가했습니다. 하지만 대다수의 소비자들은 화장품 성분의 구체적인 효능과 서로 다른 제품 간의 궁합에 대해서 명확하게 이해하지 못하고 있습니다. 성분에 대한 잘못된 정보나 부적절한 제품 조합은 피부 트러블 등의 문제를 유발할 수 있습니다. 이에 정확한 성분 정보 제공과 올바른 화장품 사용 가이드를 제공할 수 있는 도구의 필요성이 대두되었습니다.
<br/>

![image](https://github.com/user-attachments/assets/c9ef7647-1f9b-4564-a872-bca302756757)
![image](https://github.com/user-attachments/assets/2898b6ea-94df-4591-a18b-a7ba737a4fa5)


<br/>

## ⭐ 프로젝트 목표
1. 화장품 성분 정보를 사용자에게 명확하고 쉽게 제공하여 올바른 이해를 도움
2. 사용자가 보유한 화장품과의 궁합 분석을 통해 좋은 조합을 추천하고, 나쁜 조합에 대해서는 경고를 제공하여 피부 문제 예방에 도움
3. 맞춤형 성분 분석과 제품 추천을 통해 사용자가 더욱 건강하고 효율적인 피부 관리가 가능하도록 지원

<br/><br/>

# ✅ 기술 스택 & 사용한 모델

## 🔩 기술 스택
<table>
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

<br/><br/>

# 🪼 시스템 아키텍처
![llm_architecure](https://github.com/user-attachments/assets/8cf82757-389a-4f43-9fb6-cb00f33dac3f)

<br/><br/>

# 📌 WBS

<table border="1">
  <thead>
    <tr>
      <th>단계</th>
      <th>주요 작업</th>
      <th>기간</th>
      <th>담당자</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>프로젝트 기획 및 주제 확정</td>
      <td>25.05.04-25.05.08</td>
      <td>ALL</td>
    </tr>
    <tr>
      <td>2</td>
      <td>화장품, 성분 데이터 수집</td>
      <td>25.05.08-25.05.10</td>
      <td>김성지, 오정현, 현유경</td>
    </tr>
    <tr>
      <td>3</td>
      <td>데이터 전처리 및 정제</td>
      <td>25.05.10</td>
      <td>김성지, 오정현, 현유경</td>
    </tr>
    <tr>
      <td>4</td>
      <td>RAG 시스템 구조 설계 및 분석</td>
      <td>25.05.11-25.05.13</td>
      <td>현유경</td>
    </tr>
    <tr>
      <td>5</td>
      <td>VectorDB 구조 설계 및 구축 (ChromaDB)</td>
      <td>25.05.13-25.05.14</td>
      <td>현유경</td>
    </tr>
    <tr>
      <td>6</td>
      <td>테스트 질의셋 작성 및 평가</td>
      <td>25.05.13</td>
      <td>백미송</td>
    </tr>
    <tr>
      <td>7</td>
      <td>QLoRA 세팅 및 파인튜닝</td>
      <td>25.05.14-25.05.15</td>
      <td>김성지, 백미송, 현유경</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Streamlit 챗봇 UI 구현</td>
      <td>25.05.12-25.05.14</td>
      <td>백미송, 오정현</td>
    </tr>
    <tr>
      <td>9</td>
      <td>FastAPI 백엔드 구현</td>
      <td>25.05.14-25.05.15</td>
      <td>오정현, 현유경</td>
    </tr>
    <tr>
      <td>10</td>
      <td>통합 테스트 및 튜닝</td>
      <td>25.05.14-25.05.15</td>
      <td>ALL</td>
    </tr>
    <tr>
      <td>11</td>
      <td>발표 자료 / 코드 정리</td>
      <td>25.05.15</td>
      <td>ALL</td>
    </tr>
  </tbody>
</table>

<br/><br/>

# 📄 요구사항 명세서
![image](https://github.com/user-attachments/assets/6472fb8e-f88b-4bc8-ad8b-72a7fab0a9b8)

# 📜 수집한 데이터 및 전처리 요약
> 1. `oliveyoung.csv`: 올리브영 사이트의 스킨케어 항목에서 `화장품 이름`, `브랜드`, `가격`, `사용방법`, `화장품의 성분 목록`, `리뷰` 크롤링 <br/>
> 2. `coos.csv`: COOS 사이트에서 `성분`, `성분의 설명` 데이터 크롤링 <br/>

## ☝🏻 전처리 과정

### 🫒 oliveyoung.csv
- 원본 데이터
![image](https://github.com/user-attachments/assets/03f7d5ea-19a9-4730-83bb-41142f4e9b41)
**1. product_name 이름 전처리**
![image](https://github.com/user-attachments/assets/07856015-f137-4f05-8465-8006780a3dde)
![image](https://github.com/user-attachments/assets/0dcbbf83-c0c4-48ec-a070-4fda4f9b27c9)

**2. usage 전처리**
![image](https://github.com/user-attachments/assets/3e329f19-d1c3-4f90-b80e-cd0b76fe31b7)
![image](https://github.com/user-attachments/assets/32da1dfa-a02b-4e80-862e-1455da468c27)

**3. ingredient 전처리**
![image](https://github.com/user-attachments/assets/0293a1ef-c404-4025-abe4-a0a5363d9410)
![image](https://github.com/user-attachments/assets/650c7f04-f442-4976-93ce-a2e1a9d712d5)

**4. reviews 전처리**
![image](https://github.com/user-attachments/assets/1ec661ff-3bcb-4ab4-9626-27101d750ac5)
![image](https://github.com/user-attachments/assets/e25a6c5b-fa3e-4098-b8b2-24eefa7db30f)



### 💄 coos.csv
- 원본 데이터
![image](https://github.com/user-attachments/assets/8adc2d02-731e-43af-9ea7-f76c35aee0f9)

<br/>

**1. ingredient 이름 전처리하기**
   - 줄바꿈 문자 삭제
   - 영어 삭제
   - 결과
  ![image](https://github.com/user-attachments/assets/c9ae5f66-199d-4467-8b7a-61acb516f2a7)

<br/>

**2. NaN 제거하기**
   - dropna 사용
  ![image](https://github.com/user-attachments/assets/6b7afef0-a3fe-4e9b-b67c-01979f3993b9)

<br/><br/>

# DB 연동 구현 코드

8. DB 연동 구현 코드 (링크첨부)
9. 테스트 계획 및 결과 보고서
10. 진행 과정 중 프로그램 개선 노력
11. 수행결과(테스트/시연 페이지)
"Bllossom/llama-3.2-Korean-Bllossom-3B
![image](https://github.com/user-attachments/assets/28906fa3-9824-4b20-97a0-58772c5c850c)
![image](https://github.com/user-attachments/assets/b6486782-00f6-4927-b0d4-64528b3fa315)
![image](https://github.com/user-attachments/assets/2673e2c2-e5bc-4415-b9ac-dae1753e97e2)


13. 
14. 한 줄 회고

