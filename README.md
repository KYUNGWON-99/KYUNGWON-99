<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=250&section=header&text=Kyungwon%20Lim&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Engineer%20|%20AI%20Developer&descAlignY=55&descAlign=50)

### 👋 안녕하세요, 데이터 엔지니어 임경원입니다!

![Hits](https://img.shields.io/badge/GitHub-KYUNGWON--99-blue?style=flat-square&logo=github)

</div>

---

## 🙋‍♂️ About Me

- 🎓 **대전대학교** 전자정보통신공학과 졸업 (2018.03 ~ 2024.02)
- 🎓 **DSC 공유대학** 차세대통신융합과 복수전공 (2022.03 ~ 2024.02)
- 💼 **COMIZOA** HW개발팀 근무 (2023.08 ~ 2025.03)
- 📚 **SK Networks Family AI Camp 15기** 수료
- 🏆 **최종 프로젝트 1등** 수상

---

## 💼 Career

### COMIZOA / HW개발팀 (2023.08 ~ 2025.03)

**CE 인증 - Project Manager** (2024.06 ~ 2025.01) / 업무 기여도 80%

DAQ, Motion Controller, Serial Communication 등 30여 종의 제품에 대한 케이블 배선 설계와 CE 인증 전용 프로그램 개발을 총괄하며 프로젝트를 주도했습니다. 제품별 구조와 환경이 상이한 점을 고려하여 공통 배선 구조와 프로그램 통합 체계를 구축하였고, 이를 통해 여러 제품이 한 번의 시험으로 인증을 통과할 수 있도록 절차를 최적화했습니다.

또한 각 제품의 기능을 동시에 테스트하고, 실행 중 특이 사항이나 버그가 발생할 경우 즉시 중단 및 로그 기록을 통해 개발자에게 알리는 자동 검증 프로그램을 C++ 기반으로 개발하였습니다. 이를 통해 인증 과정의 신뢰성과 효율성을 모두 확보하였으며, 결과적으로 **인증 소요 시간과 비용을 대폭 절감**하는 성과를 거두었습니다.

**Quality Control - Developer** (2024.11 ~ 2025.01) / 업무 기여도 70%

Digital Input/Output(DIO) 및 Analog Input/Output(AIO) Board의 품질 관리 전용 JIG와 검사 프로그램 개발을 담당했습니다. JIG는 Mentor Artwork 프로그램을 활용하여, 각 제품의 기능을 한 번에 확인할 수 있는 PCB 형태의 검사 장비로 설계했습니다.

또한 AIO Board의 주요 기능을 자동으로 검증하고, 출력·입력 신호가 정확한 값을 유지하도록 Offset과 Gain 값을 자동 보정(Calibration)하는 품질 검사 프로그램을 C++ 기반으로 개발하여 검사 과정을 완전 자동화했습니다. 특히 JIG와 프로그램 간의 통신 구조를 안정적으로 설계함으로써 테스트 효율성과 정확도를 크게 향상시켰고, 그 결과 **제품 품질의 신뢰도를 높이는 동시에 생산 및 검사 소요 시간을 대폭 단축**하는 성과를 거두었습니다.

---

## 🏆 Featured Projects

### 🏠 ASSEMBLE - AI 기반 인테리어 디자인 자동화 프로그램
> 🥇 **SK Networks Family AI Camp 최종 프로젝트 1등**

**🎯 프로젝트 개요**
- 한샘 디자이너 업무 혁신을 위한 맞춤형 AI 솔루션
- 고객 요구사항(스타일, 예산, 분위기)을 입력하면 AI가 맞춤형 인테리어 시안 이미지와 전문 컨설팅 텍스트를 자동 생성
- 디자이너 초안 작업 시간 **70% 단축** 기대

**📊 데이터 수집 및 처리**
- 크롤링으로 한샘 가구 4,612건, 인테리어 제품 342건, 시공 사례 1.1만건(이미지 23만장) 수집
- RAG 구현을 위한 블로그 700건, 뉴스 200건, 학술 논문 300건 추가 확보
- 노이즈 20% 제거로 학습 품질 향상

**🤖 모델 성능**
- sLLM: Midm-2.0-Mini 선정 후 LoRA SFT 파인튜닝
- 성능 향상: BLEU 843%↑, ROUGE-L 747%↑, METEOR 453%↑, BERTScore 32%↑
- 이미지 생성: Nano-Banana 선정 (방 구조 유지력 우수)

**🛠 Tech Stack**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**🔗 Repository**: [SKN15-FINAL-4TEAM](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN15-FINAL-4TEAM)

---

### 🛒 Instacart 고객 이탈 예측 및 마케팅 대시보드
> SK Networks Family AI Camp 2nd 프로젝트

**🎯 프로젝트 개요**
- 현대 이커머스 시장에서 기존 고객 유지의 중요성에 착안
- Instacart 데이터 기반 고객 이탈 정의 및 개인화 마케팅 전략 제안 대시보드 제작
- 역할: Data Engineer, Database Administrator (기여도 50%)

**📊 담당 업무**
- **DBA**: 원시 데이터 분석 및 ERD 설계 (6개 테이블: products, departments, aisles, orders, order_products_prior/train)
- **Data Engineer**: 고객 이탈 정의, 데이터 전처리, 관계 분석, 인사이트 도출
- **이탈 기준 정의**: 업계 표준(30일) 벤치마킹 + 고객별 구매 주기 분석 → 이탈계수 1.35 도출

**🤖 모델 성능**
- XGBoost: AUC 0.98, 정확도 95%, 정밀도 96%, 재현율 89%, F1 92%
- Decision Tree: AUC 0.90, 정확도 91%, 정밀도 83%, 재현율 89%, F1 86%

**📌 기대효과**
- 고객 이탈률 감소 및 유지율 향상
- 충성 고객/신규 고객 차별화 전략 제공
- 마케팅 및 CRM 팀 의사결정 지원 도구로 활용

**🛠 Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**🔗 Repository**: [SKN15-2nd-4Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN15-2nd-4Team)

---

### 💬 문서기반 RAG Chatbot
> SK Networks Family AI Camp 4th 프로젝트

**🎯 프로젝트 개요**
- 대규모 강의 환경에서 교수와 학생 간의 효율적인 소통을 지원하는 AI 기반 질의응답 시스템
- 시스템 아키텍처 구성 및 PostgreDB 구조 설계

**📌 결과**
- 문서 처리 파이프라인의 성능을 개선하고, PostgreSQL과 VectorDB를 결합하여 답변의 정확도 향상

**🛠 Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**🔗 Repository**: [skn15-4th-1team](https://github.com/SKNETWORKS-FAMILY-AICAMP/skn15-4th-1team)

---

### 🚗 인공지능 교통 단속 카메라
> 대전대학교 졸업 프로젝트

**🎯 프로젝트 개요**
- YOLO 모델을 기존의 단속 카메라와 융합
- 모델 학습을 위한 데이터 수집 및 모델 선정

**📌 결과**
- 기존 후방 단속 카메라와 같이 번호판을 인식하며, 추가적으로 이륜 자동차 운전자의 헬멧 착용 여부를 인식

**🛠 Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

---

## 🛠 Tech Stack

### 📝 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🤖 AI & ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logoColor=black)

### 🌐 Frontend & Backend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

### 💾 Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### ☁️ DevOps & Tools
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

## 📜 Certificate

| 자격증 | 발급기관 | 취득일 |
|--------|----------|--------|
| 컴퓨터활용능력 1급 | 대한상공회의소 | 2021.02 |
| 정보처리기사 | 한국산업인력공단 | 2025.09 |
| 데이터분석 준전문가 (ADsP) | 데이터자격검정 | 2025.09 |
| SQL 개발자 (SQLD) | 데이터자격검정 | 2025.09 |

---

## 📈 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=KYUNGWON-99&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=667EEA&icon_color=764BA2)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=KYUNGWON-99&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=667EEA)

</div>

---

## 📫 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KYUNGWON-99)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rudwon7819@gmail.com)

</div>

---

<div align="center">

### 💡 *"데이터와 AI로 실질적인 가치를 만드는 엔지니어가 되겠습니다"*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=120&section=footer)

</div>
