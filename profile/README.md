# 🌸 PiBoo: 성분부터 궁합까지, 똑똑한 화장품 도우미

# 👥 팀 소개
> SK네트웍스 Family AI 캠프 11기 3차 프로젝트 <br/>
> 팀 명: 미피 (美Pi, MePi)🐰 <br/>
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

> 사용자의 피부 타입, 피부 고민, 보유 중인 화장품 등의 정보를 바탕으로, 궁합이 잘 맞는 기초 화장품이나 스킨케어 제품을 추천 서비스를 개발해 단순한 제품 매칭을 넘어, 화장품 성분 분석과 실제 사용자 리뷰 데이터를 기반으로 한 신뢰도 높은 정보를 제공하는 챗봇 

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
      <td>오정현, 현유경</td>
    </tr>
    <tr>
      <td>5</td>
      <td>VectorDB 구조 설계 및 구축 (ChromaDB)</td>
      <td>25.05.13-25.05.14</td>
      <td>김성지, 현유경</td>
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
      <td>llama-3-Korean-Bllossom-8B, 
mistralai/Mistral-7B-Instruct-v0.1</td>
      <td>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
      </td>
    </tr>
  </tbody>
</table>

<br/><br/>


# 📄 요구사항 명세서
![image](https://github.com/user-attachments/assets/6472fb8e-f88b-4bc8-ad8b-72a7fab0a9b8)

<br/><br/>

# 🪼 시스템 아키텍처
![Untitled](https://github.com/user-attachments/assets/52b9f510-8926-40d2-b36b-e19023ff675d)


<br/><br/>

# 📜 수집한 데이터 및 전처리 요약
> 1. `oliveyoung.csv`: 올리브영 사이트의 카테고리 항목에서 스킨케어,마스크팩,클랜징,선케어 4가지의 항목을 크롤링
> 2. `coos.csv`: COOS 사이트에서 `성분`, `성분의 설명` 데이터 크롤링 <br/>

## 올리브영 크롤링
<img width="864" alt="olive_crw" src="https://github.com/user-attachments/assets/318ce004-9f6c-4dd0-a06d-78b9d50cf804" />
<img width="864" alt="olive_crw_pro" src="https://github.com/user-attachments/assets/1f74f92b-f959-405b-a032-4c0ffab54c63" />
<img width="864" alt="olive_crw_using" src="https://github.com/user-attachments/assets/592756a0-0509-43bb-aa01-2f2c166b1309" />
<img width="864" alt="olive_reviews" src="https://github.com/user-attachments/assets/bb3ec61b-a4f2-4659-8771-a01897aca5fa" />

## 쿠스 크롤링
<img width="864" alt="coos_crw" src="https://github.com/user-attachments/assets/09da20e2-7178-478a-80fc-eee3f1120590"> </br> 

<br/>

## ☝🏻 전처리 과정

### 🫒 oliveyoung.csv </br> 
- 원본 데이터  </br> 
<img width="800" src="https://github.com/user-attachments/assets/03f7d5ea-19a9-4730-83bb-41142f4e9b41"> </br>

**1. product_name 이름 전처리**
  - 괄호 `()` 와 대괄호 `[]` 안의 내용 삭제  
  - 특정 패턴 (예: 숫자+종, 기초 2종, 택1 등) 제거  
  - 슬래시(`/`) 뒤의 내용 삭제하고 앞 부분만 사용  
  - 용량 단위 (예: 170ml, 50g 등) 삭제  
  - 리필, 증정, 기획, 한정 등 마케팅성 문구 삭제  
  - 마스크팩 관련 숫자+매수 패턴 삭제 (예: 10+1매, 10매)  
  - `'+'` 기호와 그 주변 공백을 적절히 정리  
  - 중복된 공백을 하나로 줄이고 양쪽 공백 제거  </br> 
<img width="800" src="https://github.com/user-attachments/assets/07856015-f137-4f05-8465-8006780a3dde">  </br> 
<img width="800" src="https://github.com/user-attachments/assets/0dcbbf83-c0c4-48ec-a070-4fda4f9b27c9"> </br> 

**2. usage 전처리**  
  - 특수기호 (■) 제거   
<img width="800" src="https://github.com/user-attachments/assets/3e329f19-d1c3-4f90-b80e-cd0b76fe31b7"> </br> 
<img width="800" src="https://github.com/user-attachments/assets/32da1dfa-a02b-4e80-862e-1455da468c27"> </br> 
 
**3. ingredient 전처리** 
  - 맨 앞 특수기호 (예: `*`, `+`, `/`, `-`, `:`) 제거  
  - 대괄호 안에 콜론(`:`)으로 시작하는 내용 삭제  
  - 숫자+ppm 단위 삭제  
  - 괄호 `()` 와 대괄호 `[]` 안의 내용 삭제  
  - 숫자+% 삭제  
  - 특수기호 및 구성품 관련 문구 삭제  
  - 주석/설명 문장 삭제 (특정 시작 문구 기준)  
  - 쉼표와 공백 정리  
<img width="800" src="https://github.com/user-attachments/assets/0293a1ef-c404-4025-abe4-a0a5363d9410"> </br> 
<img width="800" src="https://github.com/user-attachments/assets/650c7f04-f442-4976-93ce-a2e1a9d712d5"> </br> 

**4. reviews 전처리** 
  - 줄바꿈 문자 삭제 또는 마침표로 변환  
  - 괄호 `()`, `[]`, `{}` 등 모든 괄호 제거  
  - 한글 자음/모음만 있는 경우 마침표로 변환  
  - 따옴표 제거  
  - 쉼표 및 마침표 2개 이상 → 하나로 통일  
  - 중복 공백 제거 및 마침표로 변환  
  - 가격/수치 정보 삭제 (예: 100%, 5백원)  
  - 의미가 적은 외래어 및 홍보어 삭제 (예: good, best, 강추 등)  
  - 한글, 숫자, 공백, 마침표 외 문자 삭제 (이모지 등 포함)  
  - 표준어 사전을 활용한 오타 및 비표준어 치환 (예: 네용 → 네요, 해용 → 해요 등)
<img width="800" src="https://github.com/user-attachments/assets/1ec661ff-3bcb-4ab4-9626-27101d750ac5"> </br> 
<img width="800" src="https://github.com/user-attachments/assets/e25a6c5b-fa3e-4098-b8b2-24eefa7db30f"> </br> </br> 



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
[구글 드라이브 링크](https://drive.google.com/drive/u/0/folders/1IpsUk4_NFOL92nppOb0HCspDQQ6YUbRr)


### 1️⃣ 벡터 DB 변경

- 초기에는 Faiss를 사용했으나, 대규모 데이터에 최적화된 라이브러리여서  
  40,000개 정도의 데이터 규모에는 적합하지 않다고 판단

- 스타트업에서 많이 사용하는 Chroma로 변경하여,  
  LangChain과의 호환성 및 개발 편의성을 높임 </br> 

### 2️⃣ 프롬프트 수정
- 프롬프트에 구체적인 질문-답변 예시를 포함시켜 모델이 더 정확하고 자연스럽게 응답할 수 있도록 개선 </br> 
```python
[질문 & 답변 예시3]
질문: 세척력 좋은 클렌징폼 추천해줘
답변:
세척력이 좋은 클렌징폼을 찾고 계시다면, 모공 속 노폐물까지 깔끔히 제거해주는 제품 위주로 추천드릴게요.

1. 아니스프리 화산송이 모공 클렌징 폼
   - 추천 이유: 제주 화산송이 파우더가 피지와 노폐물을 강력하게 흡착하여 모공까지 깨끗하게 세정해줌.
   - 세정력: ★★★★★

2. 라로슈포제 에빠끌라 퓨리파잉 클렌징 젤
   - 추천 이유: 징크 PCA(피지 조절 성분)와 라로슈포제 온천수가 과도한 유분을 잡아주며 자극 없이 세정함
   - 세정력: ★★★★

3. AHC 클렌징 폼 (퓨어 리얼 아이 크림 폼)
   - 추천 이유: 마데카소사이드와 히알루론산이 세정 후에도 피부를 진정시키고 보습을 유지시켜 당김 없이 클렌징 가능
   - 세정력: ★★★★
```

<br/><br/>

# ☁️ 테스트 계획 및 결과 보고서
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Test ID</th>
      <th>목적</th>
      <th>입력 예시</th>
      <th>기대 결과</th>
      <th>실제 결과</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CASE01</td>
      <td>질문 의도에 적합한 답변 반환</td>
      <td>건성 피부가 겨울철에 사용할만한 크림 추천해줘</td>
      <td>화장품 목록 + 실제 사용자의 리뷰</td>
      <td><img src='https://github.com/user-attachments/assets/1059344b-d9b7-4189-a4b9-03fb6ed5966b'></td>
    </tr>
    <tr>
      <td>CASE02</td>
      <td>화장품의 성분을 참고한 답변 반환</td>
      <td>잡티 제거에 좋은 성분을 가진 화장품은?</td>
      <td>질문에 알맞는 성분 추천 + 화장품 추천 + 화장품의 주요 성분</td>
      <td><img src='https://github.com/user-attachments/assets/f099b5a8-4e0e-4a0c-a549-6eab0d7ef1e0'></td>
    </tr>
    <tr>
      <td>CASE03</td>
      <td>사용자가 실제 사용하고 있는 화장품과의 궁합 반환</td>
      <td>내가 넘버즈인 글루타치온 흔적 앰플을 가지고 있는데 이거랑 비타민이 함량된 세럼을 같이 써도 돼?</td>
      <td>질문 의도에 적합한 답변 + 궁합이 좋은 화장품 추천 + 화장품과의 궁합</td>
      <td><img src='https://github.com/user-attachments/assets/1dd1b90c-c024-4634-b168-bb8e777ca706'></td>
    </tr>
    <tr>
      <td>CASE04</td>
      <td>특정 기능에 대한 시각화</td>
      <td>세척력 좋은 클렌징폼 추천해줘</td>
      <td>세척력이 좋은 화장품 + 화장품의 성분 설명과 함께 추천 이유 전달 + 세정력 시각화</td>
      <td><img src='https://github.com/user-attachments/assets/2723220b-4cb0-4ef6-8b21-76b59969c516'></td>
    </tr>
  </tbody>
</table>



<br/><br/>

# 수행결과(테스트/시연 페이지)
## 🎨 Frontend  
Figma로 설계된 디자인 시안을 바탕으로,  Streamlit을 통해 간단하고 빠른 사용자 인터페이스를 구현
<div align="center">
  <img src="https://github.com/user-attachments/assets/fef2d7ab-0a4a-469a-b423-272d55d02f69" width="300"/>
  <img src="https://github.com/user-attachments/assets/423424d3-8938-4e8c-8b3f-776d20f7b04e" width="300"/>
  <img src="https://github.com/user-attachments/assets/0785f9b4-aea6-49dd-9500-b176800a257c" width="300"/>
</div>

<br/>

## 🛠️ Backend

#### 주요 기능 및 처리 흐름
##### 모델과 프롬프트 체인 결합  
- 파인튜닝된 QLoRA 모델과 프롬프트 템플릿을 결합하여 하나의 체인 생성  
- 프롬프트 내에 대화 이력을 포함하여 문맥을 유지하며 응답 생성 
</br>


<strong>체인 생성</strong>

</br> 

  ```python
def get_chain_with_model(model):
    prompt = ChatPromptTemplate.from_messages([
        ('system', 
         """
        당신은 화장품 전문가입니다. 아래 예시처럼 질문에 답변하세요.
        
        [1.규칙]
        (생략)
        
        [2.성분 정보 추가 시]
        (생략)
        
        [3.궁합 포인트 추가 시]
        (생략)
        
        [4.추천 이유 추가 시]
        (생략)
        
        [5.세정력 추가 시]
        (생략)
        
        [6.주요 리뷰 추가 시]
        (생략)
        
        [7. 답변 스타일]
        - 아래 예시처럼 자세하고, 사용자 친화적인 문장으로 작성합니다.
        
        [질문 & 답변 예시1~5]
        ... (생략) ...
                 """
         ), 
        MessagesPlaceholder(variable_name='history'),
        ('human', '{query}')
    ])
    chain = prompt | model
    return RunnableWithMessageHistory(
        chain,
        get_session_history=get_by_session_id,
        input_messages_key='query',
        history_messages_key='history'
    )
```

</br></br>

## 🔧 Finetuning
### 사용자 질문 데이터 생성 및 학습  
- 100개의 예시 사용자 질문 생성
- 크롤링한 화장품 성분 및 리뷰 문서로 RAG 모델에 질의  
- 총 100쌍의 질문-답변 초안 데이터를 생성  
- 이 중 100쌍을 선별하여 QLoRA 기법으로 사전 학습(파인튜닝) 진행 
</br>

### 대상 모델 
--- 
#### 🪷 Bllossom/llama-3.2-Korean-Bllossom-3B
Bllossom 모델을 QLoRA 방식으로 100개 데이터로 파인튜닝한 결과, 초기에는 손실이 빠르게 감소했지만 후반부로 갈수록 수렴 속도가 둔화되었으며, 향후 추가 개선이 필요한 것으로 분석 

<img src="https://github.com/user-attachments/assets/28906fa3-9824-4b20-97a0-58772c5c850c">
<div align="center">
  <img src="https://github.com/user-attachments/assets/b6486782-00f6-4927-b0d4-64528b3fa315" width="400"/>
  <img src="https://github.com/user-attachments/assets/2673e2c2-e5bc-4415-b9ac-dae1753e97e2" width="400"/>
</div>

---

#### 🌊 mistralai/Mistral-7B-Instruct-v0.1 
Mistral 모델을 QLoRA 방식으로 100개 데이터에 파인튜닝한 결과, 훈련 손실과 검증 손실이 모두 점차 감소했으며 약 72 스텝 이후 EarlyStopping 조건을 만족하여 학습이 조기에 종료 

<img src="https://github.com/user-attachments/assets/0a8fc297-a32a-42f5-a46b-7e2f20ea6f7f">
<img src="https://github.com/user-attachments/assets/f83893ec-25e1-43b5-8dad-3f94d5de241e">

</br></br>

# 🚨 개선 사항

1. **QLoRA 파인튜닝 모델 성능 한계**  
   현재 사용된 QLoRA 파인튜닝 모델은 약 100개의 QA 데이터셋으로 학습되었기 때문에,  
   다양한 질문에 대한 일반화 성능에 한계가 있습니다.  
   향후에는 보다 많은 데이터를 추가하여 학습시킴으로써 모델의 응답 품질을 향상시킬 예정입니다.

2. **웹 버전 UI 개선 계획**  
   현재 PiBoo의 사용자 인터페이스는 모바일 최적화된 휴대폰 화면 형태로 디자인되어 있습니다.  
   하지만 다음 프로젝트에서는 Django와 HTML 기반의 웹사이트 제작을 배우게 되어,  
   웹 버전 형태로 구현하여 다양한 환경에서도 원활하게 사용할 수 있도록 개선할 계획입니다.

3. **문서 임베딩 처리 오류 개선**  
   현재 문서 임베딩 과정에서 토큰 수가 많은 리뷰 데이터가 포함될 경우,  
   임베딩 처리 중 오류가 발생하거나 VectorDB에 저장되지 않는 문제가 발생합니다.  
   이를 해결하기 위해 리뷰 데이터를 요약하여 토큰 수를 줄이고, 오류를 최소화하는 방안을 적용할 예정입니다.
</br> 

# ✅ 한 줄 회고
| 팀원  | 한 줄 회고                 |
|-------|----------------------------|
| 미송  | 처음으로 Figma로 UI를 설계하고 Streamlit으로 직접 구현하면서 시행착오를 겪으며 프론트엔드의 흐름을 익혔고, 파인튜닝에도 도전해본 경험이 특히 의미 있었다. 이번 프로젝트를 통해 AI 서비스 개발의 전체적인 구조와 협업 방식, 다양한 도구의 활용법을 폭넓게 배울 수 있었다 |
| 정현  | 크롤링과 LangChain을 직접 실습해보며 이해를 더욱 깊이 할 수 있는 좋은 시간이었습니다. 저는 이번에 QLoRA를 시도해보지 못해서, 다음 기회에 학습시켜보고 싶습니다. |
| 유경  | RAG 흐름과 VectorDB 구축에 대해 정확히 공부할 수 있었고, 적은 데이터였더라도 파인튜닝을 해보면서 이해도를 높일 수 있었습니다! 다들 너무 수고 많았고, 다음 4회차 프로젝트로 파이팅합시다~  |
| 성지  | 크롤링과 전처리 과정은 비교적 수월했지만, 모델을 생성하고 학습시키는 과정에서는 다양한 오류와 제약에 부딪히며 아쉬움이 컸다. 이번 프로젝트를 통해 단순한 모델 사용을 넘어, LLM의 구조 설계와 프롬프트 구성의 중요성을 깊이 체감할 수 있었다 |
