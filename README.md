<h1 align="center">안녕하세요, 효창입니다. 👋</h1>
<h3 align="center">데이터 파이프라인을 설계하고, AI를 운영 가능한 서비스로 만드는 데이터 엔지니어를 지향합니다.</h3>

<div align="center">
  <a href="https://www.linkedin.com/in/hyochangsung"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://byhy0.tistory.com"><img src="https://img.shields.io/badge/Tech_Blog-Visit-FF5722?style=for-the-badge&logo=tistory&logoColor=white" alt="Blog" /></a>
  <a href="mailto:shc7657@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://myochil.com"><img src="https://img.shields.io/badge/myochil.com-Visit-4CAF50?style=for-the-badge&logo=googlechrome&logoColor=white" alt="myochil" /></a>
</div>
<br/>
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=hyochangsung&label=Profile%20views&color=0e75b6&style=flat" alt="hyochangsung" />
</div>

---

## 🙋‍♂️ About Me

- 🎓 **인천대학교 정보통신공학과** 재학 중이며, **SK Planet 생성형 AI 활용 데이터 엔지니어 과정 2기**를 수강 중입니다.
- ☁️ **데이터 파이프라인 구축과 클라우드 인프라**에 집중하는 **Data Engineer**를 목표로 합니다. Kafka·Airflow 기반 스트리밍 파이프라인부터 AWS 인프라 설계, MLOps 흐름까지 직접 구현해왔습니다.
- 🤖 단순 모델링을 넘어 **AI를 운영 가능한 서비스로 만드는 일**에 관심이 많습니다. RAG·LangGraph·Claude/OpenAI API를 활용한 AI 에이전트를 학습하고 있으며, 현재 **다양한 전공의 학생들과 AI 학습 소모임**을 이끌고 있습니다.
- 💡 기획과 디자인(Figma)을 활용한 시각화에도 흥미가 있어, 데이터를 사람이 쓰는 서비스로 연결하는 과정을 좋아합니다.

---

## 🚀 Projects

### 🛣️ 실시간 포트홀 관리 서비스 — 도로 진단 데이터 파이프라인
> 버스 노선 기반 포트홀 탐지 로그를 수집·처리·시각화하는 **End-to-End 데이터 파이프라인**

- **Edge → Kafka → Airflow → 시각화**로 이어지는 실시간 스트리밍 파이프라인 설계·구현
- 탐지 이벤트를 **RDS(즉시 조회용) + S3 Parquet(분석·재학습용)** 으로 분리 적재하는 이중 적재 구조 설계
- **Airflow DAG** 로 배차 간격 주기 클러스터링 갱신 및 일일 분석 리포트 자동화
- YOLOv8-CLS 추론 결과에 **Conformal Prediction** 을 적용해 신뢰구간 기반 4단계 분류로 오탐 문제 완화
- **MLOps 흐름**(배포 → 모니터링 → HNM 재학습 데이터 수집)까지 모델 개선 루프 연결
- `Kafka` `Airflow` `AWS (EC2·RDS·S3)` `PostgreSQL` `Docker` `FastAPI` `YOLOv8`

🔗 [pothole-airflow-kafka](https://github.com/hyochangsung/pothole-airflow-kafka)

### 📅 myochil — 팀 캘린더 × 날씨 × AI 기상 캐스터 (운영 중)
> 팀 일정과 실시간 날씨 데이터를 결합하고, LLM이 날씨를 해설해주는 웹 서비스

- 기상청 단기예보 API로 날씨 데이터를 수집하고, **OpenAI API(gpt-4o)** 로 'AI 기상 캐스터' 기능 구현
- **FastAPI + SQLAlchemy 2 + MySQL** 백엔드 설계, PyJWT·bcrypt 기반 인증 구현
- **AWS EC2 + Nginx + systemd** 로 직접 배포·운영하고, **GitHub Actions** 로 main 브랜치 푸시 시 자동 배포(CI/CD) 구성
- `FastAPI` `MySQL` `OpenAI API` `AWS EC2` `Nginx` `GitHub Actions` `Vanilla JS` `Tailwind CSS`
- 🌐 [myochil.com](https://myochil.com) *(레포 비공개)*

---

<h3 align="left">🛠️ Tech Stack</h3>

**Data Engineering**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)

**Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**AI / LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat&logo=anthropic&logoColor=white)

---

<h3 align="left">🎨 Tools</h3>

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

---

<p><img align="center" src="https://github-readme-stats.vercel.app/api?username=hyochangsung&show_icons=true&theme=default&hide_border=true" alt="hyochangsung github stats" /></p>
