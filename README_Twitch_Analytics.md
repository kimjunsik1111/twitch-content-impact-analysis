# 🟣 Twitch Analytics Portfolio

> **개인방송 플랫폼(Twitch)**의 사용자 행태, 커뮤니티 구조, 콘텐츠 영향력에 대한 정량 분석 프로젝트입니다.  
> 플랫폼/운영자/광고주 입장에서 의미 있는 전략적 인사이트 도출을 목표로 합니다.

---

## 📂 프로젝트 구성

| 파일명 | 설명 |
|--------|------|
| `1. twitch-content-impact-analysis.ipynb` | 📈 **콘텐츠 시작 전후 시청자 변화 분석**<br>특정 스트리머 콘텐츠가 플랫폼 전체 유입에 미치는 영향을 정량 분석합니다. |
| `2. Twitch Viewer–Streamer Network Analysis.ipynb` | 🌐 **시청자–스트리머 네트워크 분석**<br>PyVis 기반 시각화를 통해 커뮤니티 중심 노드, 연결 구조, 커뮤니티 클러스터를 식별합니다. |
| `3. Twitch Chat Behavior Analysis copy.ipynb` | 💬 **채팅 행동/감정 분석**<br>유저 유형별 채팅 빈도, 세션 지속시간, 감정 분포 및 욕설률을 기반으로 커뮤니티 건강도를 진단합니다. |

---

## 📌 주요 인사이트 예시

### 📈 콘텐츠 유입 분석
- 감스트, 마병대 등 콘텐츠 전후 채널 시청자 수 급등 → **콘텐츠 중심 유입 파악**
- 트래픽 피크 시간 비교로 **컨텐츠 영향력 가시화**

### 🌐 커뮤니티 네트워크 분석
- **중심 스트리머 vs 주변 스트리머 구조** 시각화
- 클러스터별 연결 강도 파악 → **커뮤니티 분화/응집도 평가**

### 💬 채팅 행동 분석
- **유입/정착/코어 유저** 세그먼트 기반 분석
- `sodapoppin` 코어 유저 비율 28.8%, 평균 채팅 2,500회 이상 → **몰입도 최상급**
- `xqcow`는 유입은 많으나 리텐션/몰입도는 낮음

---

## 🧠 사용된 기술 스택

- **데이터 처리**: `pandas`, `numpy`
- **시각화**: `matplotlib`, `seaborn`, `networkx`, `PyVis`
- **감정 분석**: `TextBlob`, `custom profanity filter`
- **네트워크 분석**: `degree centrality`, `community detection`

---

## 📥 데이터 출처

- [Kaggle - Twitch Chat & User Activity Datasets](https://www.kaggle.com/)
- XQCOW, SODAPOPPIN 채팅 로그, 관계 그래프 등

---

## 💡 활용 방향

- 플랫폼 운영자: 콘텐츠 영향력 기반 큐레이션 전략
- 브랜드/광고주: 안전한 커뮤니티 선별 (욕설률, 감정 분석)
- 데이터 사이언티스트: 스트리밍 서비스 유저 세분화 및 행동 모델링

---

## 🙋‍♂️ Contact

> 본 프로젝트는 **[닉네임 또는 이름]** 의 개인 리서치 기반이며,  
> 더 많은 분석 및 확장 제안은 언제든지 환영합니다.

- 📫 email@example.com  
- 📁 [포트폴리오 웹사이트 / Notion 링크]  
- 🐙 GitHub: [github.com/yourusername]
