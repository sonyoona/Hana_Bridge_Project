# 🚀 AIssue – SW 교육생을 위한 AI 기반 코드/에러 해결 커뮤니티

**AIssue**는 SW 교육 과정에서 가장 많이 발생하는 문제인  
> **“에러가 나왔는데 어디에 물어봐야 할지 모르겠어요”**  
를 해결하기 위해 개발된 **AI 기반 코드/에러 리뷰 플랫폼**입니다.

SW 교육생에게 익숙한 *Jitsi, Slack, 오픈채팅방* 등 여러 도구로 흩어져 있던 질문 환경을 통합하여  
**한곳에서 학습 · 질문 · 소통 · 에러 해결이 가능한 서비스**를 목표로 했습니다.


## 🌟 주요 기능

### 🧠 OpenAI 기반 AI 코드/에러 챗봇
- 에러/로그/코드를 입력하면 실시간 해결 방안 제공  
- *초보자 / 전문가 / 커스텀* 등 **답변 수준 선택 기능**  
- “표로 비교해서 설명해줘”, “코드만 보여줘” 등 **프롬프트 커스텀 가능**


### 📝 AI 답변 → 게시글 자동 요약 업로드
- 사용자가 AI 답변을 **채택**하면  
  → 핵심 내용만 요약된 **게시글 자동 생성**
- 언어 / 에러 유형 / 주차 카테고리 자동 분류  
- 다른 사용자도 참고 가능한 **지식 베이스** 역할



### 💬 SW 교육생 전용 커뮤니티 게시판
- 일반 질문 게시판  
- 공지 게시판  
- AI 답변 전용 게시판  
- 학우 간의 자연스러운 소통과 협업 지원



### 📊 관리자 통계 대시보드
- 전체 게시글/사용자 활동 통계 시각화  
- 주차별/언어별/에러 유형별 AI 답변 통계  
- **Prometheus + Grafana** 기반 실시간 모니터링  
- 사용자 경험 기반 서비스 품질 개선 지원



### ⚙️ 실서비스 운영 및 성능 개선 경험
AIssue는 단순한 토이 프로젝트가 아니라, 실제로 배포하여 사용자를 확보한 **실서비스 프로젝트**입니다.

- **JMeter 부하 테스트 진행**
  - 1초 20요청 평균 응답: **45.9초**
  - 1초 4요청 평균 응답: **38.6초**

- OpenAI 요청 집중으로 인해 응답 지연 발생 → 이를 해결하기 위해  
  **OpenAI 전용 Spring Boot 서비스 분리 + RabbitMQ 기반 분산 처리 아키텍처** 설계

이 경험을 통해 실전 수준의  
**트래픽 처리, API 지연 대응, 서비스 운영 능력**을 길렀습니다.



## 🏗️ 기술 스택 (Two-Line Style)

### 🖥️ Frontend
<p>
  <!-- 아이콘 라인 -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="35" />
</p>
<p><b>React.js · JavaScript</b></p>

---

### ⚙️ Backend
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="35" />
</p>
<p><b>Spring Boot 3 · Java 21 </b></p>

---

### 🤖 AI
<p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" width="32" />
  <img src="https://img.shields.io/badge/OpenAI%20GPT%20API-412991?style=flat&logo=openai&logoColor=white" />
</p>
<p><b>OpenAI GPT API · AI 에러 분석 & 요약</b></p>

---

### 🗄️ Database
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="35" />
</p>
<p><b>MySQL · Redis</b></p>

---

### 🏗️ Infra
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" width="35" />
</p>
<p><b>Docker · Nginx</b></p>

---

### 🔄 CI/CD
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="35" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
</p>
<p><b>GitHub Actions</b></p>

---

### 📊 Monitoring
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" width="35" />
</p>
<p><b>Prometheus · Grafana</b></p>

---

### 🛠️ Tools
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="35" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/notion/notion-original.svg" width="35" />
</p>
<p><b>Figma · Git · IntelliJ · VS Code · Notion</b></p>

---

### 🧪 Test
<p>
  <img width="90" height="29" alt="image" src="https://github.com/user-attachments/assets/0c0aa467-c643-43c4-b4a4-b64363a8b1d0" />
</p>
<p><b>JMeter</b></p>

---


## 🧩 시스템 아키텍처
<img width="707" height="764" alt="Frame 1" src="https://github.com/user-attachments/assets/16d1ea9e-8db6-4f13-a0bd-1ca36d9ce450" width="1000"/>


