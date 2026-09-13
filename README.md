<div align="center">

### AI를 더해 기술을 비즈니스 가치로 연결하는 풀스택 개발자

AI로 빠르게 구현하고, 판단과 검증에 집중합니다.<br>
혼자서도 팀의 속도로 **기획부터 개발, 배포까지** 완주합니다.

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)

</div>

---

## 🚀 Live Products

지금 바로 열어볼 수 있는, 설계부터 배포까지 직접 만든 서비스입니다.

| 서비스 | 무엇을 | 기술적 핵심 |
|---|---|---|
| **[ProWith](https://prowith.kr)**<br><sub>MLM 정산 솔루션</sub> | 그누보드5 레거시를 새로 구축한 **멀티테넌트** 정산 플랫폼 | 추천·후원 **이중 트리 정산 엔진**(수당 최대 13종 × 마감 4종) · 마감 취소 시 스냅샷 복원<br>NestJS **19개 모듈 · 290여 REST API** · 관리자 화면 60개 · 설정값 215개 DB 중앙 관리 |
| **[Recoeve](https://recoeve.com)**<br><sub>소셜 큐레이션 플랫폼</sub> | 레거시 Java(Vert.x) 서비스를 **Turborepo 모노레포로 재구축** | BullMQ 워커 기반 **LLM 파이프라인**(Haiku 요약 → Sonnet 생성)<br>JWT(RS256) + RBAC · Google/Kakao OAuth · 실패 시 **멱등 환불** |
| **[GENYS Lotto AI](https://lotto.genys.kr)**<br><sub>통계 분석 + AI 예측</sub> | 역대 추첨 데이터 기반 패턴 분석 서비스 | AWS Lambda + EventBridge **서버리스 수집 파이프라인**<br>분석 API **966ms → 31ms** · 예측 API **10초 → 2초** |

> 💡 **ProWith**는 로그인 화면의 `DEMO Login` → `시스템 관리자`로 들어가면 계정 없이 전체 관리 기능을 볼 수 있습니다.<br>
> 세 서비스의 코드는 비공개 저장소로 관리하고 있습니다.

---

## 🤖 Harness Engineering

**설계 방향과 합격 기준은 직접 정하고, 구현과 검증은 AI 워크플로우로 돌립니다.**

- **반복 운영 업무를 에이전트 스킬 6종으로 표준화** (ProWith)
  - 신규 고객사 셋업을 명령 한 번으로: DB · GitHub · AWS · Vercel · 도메인 연결 · 배포
  - 보상플랜 문서(hwp · pptx) → 규격 문서 → 설정 반영 → 마감 검증까지 **체인으로 연결**
- **검증까지 자동화**
  - 보상플랜 **불변식(invariant) 검사** + 운영 덤프 **재마감 전수 대조**, 한 건이라도 어긋나면 통과하지 않음
- **AI를 제품 기능으로** (Recoeve)
  - LLM 호출을 결제 트랜잭션처럼 설계: row lock 차감 · 캐시 · 입력 소스 5종 폴백 · 실패 시 멱등 환불

---

## 🛠 Tech Stack

| | |
|---|---|
| **Backend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Infra** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **AI** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![Anthropic API](https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white) |

---

## 🏆 Background

- 벤처 창업 · **정부 기술개발 과제 총괄책임** (성공 판정)
- 중소기업진흥공단 **개발기술 사업화 사업 선정**
- 중소기업청장상 · 지식경제부장관상
