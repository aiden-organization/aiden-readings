# Claude, 데이터 대시보드와 설명용 애니메이션까지 만든다

![Claude가 자전거 공유 데이터를 바탕으로 만든 대시보드](https://assets.claude.com/7688d4d3b888c17cf4b3553f537f291882a92656.png)

*이미지 출처: Anthropic*

Anthropic이 10월 8일 **Claude Dashboards와 Claude Motion**을 공개했습니다. 데이터를 살펴보는 대시보드부터 발표에 사용할 애니메이션까지, 대화로 만들 수 있게 됩니다. 아래 내용은 [공식 발표](https://claude.com/ko/resources/articles/dashboards-and-motion)를 바탕으로 정리했습니다.

## 01. 질문하면 만들어지는 데이터 대시보드

**Claude Dashboards**는 회사의 데이터를 연결하고, 자연어로 질문해 대시보드를 만드는 기능입니다.

원문에서는 다음과 같은 요청을 예로 듭니다.

> 이번 분기 매출을 지역별로 보여주는 대시보드를 만들어 줘.
>
> 이번 주 가입자 수는 지난달과 비교하면 어떤가?

BigQuery·Databricks·Snowflake 같은 데이터 플랫폼이나 Salesforce를 연결해 사용할 수 있습니다. 데이터가 바뀌면 대시보드도 최신 상태로 유지합니다.

**숫자가 어떻게 나왔는지 확인할 수 있다는 점**도 특징입니다. 수치를 클릭해 데이터를 조회한 쿼리를 확인하거나 Claude에게 설명을 요청할 수 있고, 차트에는 마지막 갱신 시점이 표시됩니다.

## 02. 글과 차트를 움직이는 설명 자료로

**Claude Motion**은 텍스트·차트·도형·이미지에 움직임을 넣어 설명용 애니메이션을 만듭니다.

원문에서 소개한 활용처는 다음과 같습니다.

- 분기 보고서를 전사 회의용 30초 설명 자료로 만들기
- 발표 자료의 차트에 움직임 추가하기
- 고객 온보딩용 제품 사용 안내 만들기

Claude가 **애니메이션 코드를 작성하는 방식**이므로 문구, 숫자, 재생 시간을 수정할 수 있습니다. 편집기나 대화로 수정한 뒤 MP4로 내려받습니다.

## 03. 문서·슬라이드·디자인도 정식 제공

Docs·Slides·Design은 베타를 종료하고 무료 플랜까지 확대됩니다.

팀 공동 편집, 관리자 허용에 따른 외부 공유, 모바일 편집을 지원합니다. 슬라이드는 PowerPoint·PDF로 내려받거나 편집 가능한 Google Slides 파일로 보낼 수 있습니다.

## 04. 이용 조건은 기능마다 다르다

| 기능 | 발표 기준 제공 범위 |
|---|---|
| Dashboards | 유료 플랜, 베타 |
| Motion | Team·Enterprise, 베타 |
| Docs·Slides·Design | 무료 포함 모든 플랜, 정식 제공 |

Enterprise에서는 Dashboards와 Motion을 관리자가 활성화해야 합니다. 자세한 조건은 [공식 안내](https://claude.com/ko/resources/articles/dashboards-and-motion)에서 확인할 수 있습니다.
