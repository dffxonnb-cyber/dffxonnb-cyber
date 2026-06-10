# 최다빈 | Data Analyst · Spatial Data Analyst

> **의사결정 전에 확인해야 할 위험 신호와 판단 순서를 설계합니다.**

데이터를 단순히 요약하거나 좋은 후보를 추천하는 데서 멈추지 않습니다.  
문제를 다시 정의하고, 흩어진 데이터를 판단 가능한 구조로 바꾸고, 지표와 검증 근거를 설계한 뒤 문서·대시보드·웹 기반 의사결정 화면으로 연결합니다.

`Define → Structure → Measure → Validate → Communicate → Implement`

[**Portfolio · Signal Archive**](https://signal-archive.vercel.app/) · [**3분 리뷰 가이드**](https://signal-archive.vercel.app/start-here) · [**Main Project · Redveil**](https://dffxonnb-cyber.github.io/Seoul-Storefront-Redveil/) · [GitHub](https://github.com/dffxonnb-cyber) · [Email](mailto:dffxonnb@gmail.com)

## About

저는 **무엇을 추천할 것인가**보다 먼저 **왜 보류해야 하는가, 무엇을 먼저 확인해야 하는가**를 설명하는 데이터 분석가입니다.

공공데이터, 공간·도시·상권 데이터, CRM·리테일 데이터를 다루며 다음 흐름으로 문제를 해결합니다.

- 모호한 요청을 실제 의사결정 질문으로 다시 정의합니다.
- 원천 데이터를 분석 가능한 grain, 이벤트, 공간 단위로 구조화합니다.
- KPI, 위험 신호, 세그먼트, 우선순위 기준을 설계하고 검증합니다.
- 결과를 README, 분석 문서, Tableau, 대시보드, 웹 기반 검토 도구로 구현합니다.
- 공개 가능한 근거와 재현 범위, 한계 조건을 함께 남깁니다.

관심 역할은 **Data Analyst, Spatial Data Analyst, Business Data Analyst, CRM / Marketing Data Analyst, Public / Urban / Commercial Data Analyst**입니다.

## Start With Signal Archive

[**Signal Archive**](https://signal-archive.vercel.app/)는 프로젝트를 단순 나열하는 사이트가 아니라, 각 분석을 **문제 정의 → 판단 질문 → 근거 → 검증 → 결과물**의 흐름으로 다시 구성한 포트폴리오 허브입니다.

Vercel에 배포된 Next.js 기반 사이트에서 대표 프로젝트, 상세 분석, Case Studies, 검증 가능한 산출물을 한 흐름으로 확인할 수 있습니다.

**추천 검토 순서:** [Start Here](https://signal-archive.vercel.app/start-here) → [Projects](https://signal-archive.vercel.app/projects) → [Case Studies](https://signal-archive.vercel.app/case-studies) → [Seoul Storefront Redveil](https://signal-archive.vercel.app/projects/seoul-storefront-redveil)

## Focus

| Focus | 제가 설계하는 것 | 대표 증거 |
| --- | --- | --- |
| **Public Data / Spatial Analysis** | 공간 위험도를 자원 배분과 시설 설치 우선순위로 변환 | [LH Traffic Safety](https://signal-archive.vercel.app/projects/lh-traffic-safety-analysis) |
| **Commercial Risk Analysis** | 추천보다 먼저 읽어야 할 가격 부담, 유동성, 경쟁도, 수요 취약 신호 | [Seoul Storefront Redveil](https://signal-archive.vercel.app/projects/seoul-storefront-redveil) |
| **CRM / Customer Analytics** | 고객군을 반응 가능성, 유지·재활성화 액션, 확인 KPI로 번역 | [Starbucks Promotion](https://signal-archive.vercel.app/projects/starbucks-promotion-analysis) · [UK Online Retail](https://signal-archive.vercel.app/projects/uk-online-retail-segment-analysis) |
| **Dashboard / Decision Interface** | 분석 결과를 사용자가 비교하고 다음 행동을 결정할 수 있는 화면으로 구현 | [ShopEasy](https://signal-archive.vercel.app/projects/shopeasy) · [Redveil Live](https://dffxonnb-cyber.github.io/Seoul-Storefront-Redveil/) |
| **AI-assisted Workflow** | 아이디어 구조화, 코드 초안, 디버깅, 문서화에 AI를 활용하고 문제 정의·지표·해석은 직접 검토 | [Signal Archive Repo](https://github.com/dffxonnb-cyber/signal-archive) |

## Selected Projects

| Project | Reframed Decision Question | Evidence & Output | Review |
| --- | --- | --- | --- |
| **Signal Archive** | 채용 검토자가 프로젝트 수가 아니라 분석 방식과 역할 적합성을 어떻게 빠르게 판단할 수 있는가? | 구조화된 프로젝트·Case Study 콘텐츠, Next.js 웹 포트폴리오, Vercel 배포, typecheck·lint·build 검증 | [Live](https://signal-archive.vercel.app/) · [Start Here](https://signal-archive.vercel.app/start-here) · [Repo](https://github.com/dffxonnb-cyber/signal-archive) |
| **Seoul Storefront Redveil** | 어떤 상권이 좋아 보이는가가 아니라, 매입 전에 먼저 보류해야 할 신호는 무엇인가? | 서울 **25개 구**, **428개 행정동**, 취약 상권 **1,570개**, 거래 **12,074건** 검토. 가격 부담·거래 유동성·경쟁도·수요 취약도를 보류 사유와 대체 후보로 연결한 정적 웹 프로토타입 | [Detail](https://signal-archive.vercel.app/projects/seoul-storefront-redveil) · [Live](https://dffxonnb-cyber.github.io/Seoul-Storefront-Redveil/) · [Repo](https://github.com/dffxonnb-cyber/Seoul-Storefront-Redveil) |
| **LH Traffic Safety Analysis** | 사고 이력이 부족한 신도시에서도 어디에 안전시설을 먼저 설치해야 하는가? | 격자 기반 공간 위험도와 설치 우선순위 설계. **Mean AUC 0.8604**, **Top-10% Lift 4.39x**, Worst holdout AUC 0.7979. 위험 후보와 추천 사유를 함께 제시 | [Detail](https://signal-archive.vercel.app/projects/lh-traffic-safety-analysis) · [Repo](https://github.com/dffxonnb-cyber/LH-traffic-safety-analysis) |
| **Starbucks Promotion Analysis** | 어떤 고객군에 어떤 오퍼를 어떤 채널로 제안해야 하는가? | 반정형 이벤트 로그를 고객-오퍼 분석 테이블로 재구성. **AUC 0.8147**, **Recall 0.8712**, **F1 0.7657**. 프로모션 후보와 Tableau 의사결정 화면으로 연결 | [Detail](https://signal-archive.vercel.app/projects/starbucks-promotion-analysis) · [Repo](https://github.com/dffxonnb-cyber/starbucks-promotion-analysis) |
| **UK Online Retail Segment Analysis** | 고객을 어떻게 나눌 것인가가 아니라, 누구를 유지·재활성화 우선순위로 볼 것인가? | RFM, 파레토, ANOVA / Kruskal-Wallis 기반 검증. 상위 **20% 고객 = 매출 73.5%**, 이탈위험 고객군 **84.2% MoM 감소**. 세그먼트를 캠페인과 KPI로 번역 | [Detail](https://signal-archive.vercel.app/projects/uk-online-retail-segment-analysis) · [Repo](https://github.com/dffxonnb-cyber/UK-OnlineRetail-Segment-analysis) |
| **ShopEasy** | 주문 감소에서 어떤 전환 병목을 먼저 검증하고 개선해야 하는가? | 주문 **1,000건**, 사용자 **500명**, 세션 **2,000회**를 카테고리·진입·디바이스·이탈 흐름으로 분해. Mobile CVR **6.38%**, 전자기기 완료율 **52.34%**, A/B 테스트 제안 | [Detail](https://signal-archive.vercel.app/projects/shopeasy) · [Live](https://dffxonnb-cyber.github.io/ShopEasy/) · [Repo](https://github.com/dffxonnb-cyber/ShopEasy) |

## Analysis Workflow

| Stage | 핵심 질문 | 남기는 결과물 |
| --- | --- | --- |
| **Define** | 분석 주제를 어떤 판단 질문으로 바꿔야 하는가? 무엇을 추천하기 전에 보류해야 하는가? | 문제 정의, 의사결정 질문, 분석 범위 |
| **Structure** | 어떤 grain, 조인 기준, 이벤트 정의, 공간 단위가 필요한가? | 분석 테이블, 공간 격자, CSV / JSON payload |
| **Measure** | 어떤 KPI, 위험 신호, 세그먼트, 우선순위가 판단을 돕는가? | 지표 정의, 리스크 점수, 후보 순위 |
| **Validate** | 결과가 우연·누수·과도한 일반화가 아닌지 어떻게 확인할 것인가? | 통계 검정, 시간·지역 전이 검증, smoke test, CI, 한계 문서 |
| **Communicate** | 읽는 사람이 무엇을 먼저 보고 다음에 무엇을 확인해야 하는가? | README, 분석 문서, Tableau, 대시보드 |
| **Implement** | 분석 결과를 실제로 비교·검토 가능한 화면으로 어떻게 연결할 것인가? | Static Web, GitHub Pages, Next.js / Vercel 기반 의사결정 인터페이스 |

## Tech Stack

| Area | Tools |
| --- | --- |
| **Analysis & Modeling** | Python, SQL, pandas, NumPy, SciPy, scikit-learn, statsmodels, Jupyter |
| **Spatial Analysis** | GeoPandas, QGIS, GeoJSON, Shapely, PyProj, spatial grid analysis |
| **CRM / BI / Visualization** | Tableau, RFM Analysis, Statistical Testing, Matplotlib, Seaborn, Plotly, Streamlit / pydeck |
| **Web & Delivery** | HTML, CSS, JavaScript, TypeScript, React, Next.js, Static Web, GitHub Pages, Vercel |
| **Validation & Workflow** | GitHub Actions, public artifact checks, smoke tests, reproducibility docs, data quality checks |
| **AI-assisted Workflow** | 분석 아이디어 구조화, 코드 초안·디버깅, SQL / Python 오류 분석, 문서화 보조. 최종 문제 정의·지표 설계·해석은 직접 검토 |

## Portfolio Links

- [Signal Archive · Portfolio Home](https://signal-archive.vercel.app/)
- [Start Here · 3분 리뷰 가이드](https://signal-archive.vercel.app/start-here)
- [Projects · 전체 프로젝트 아카이브](https://signal-archive.vercel.app/projects)
- [Case Studies · 반복해서 사용하는 판단 방식](https://signal-archive.vercel.app/case-studies)
- [Resume · 역할 적합성과 프로젝트 근거](https://signal-archive.vercel.app/resume)
- [Seoul Storefront Redveil · Main Proof Project](https://dffxonnb-cyber.github.io/Seoul-Storefront-Redveil/)

## Contact

- Email: [dffxonnb@gmail.com](mailto:dffxonnb@gmail.com)
- GitHub: [github.com/dffxonnb-cyber](https://github.com/dffxonnb-cyber)
- Portfolio: [signal-archive.vercel.app](https://signal-archive.vercel.app/)
