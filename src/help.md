---
layout: base.njk
title: "HELP.md — Purple IO"
heading: "HELP.md"
version: "recruiting"
subtitle: "// we need more humans"
description: "Purple IO is hiring"
backLink: true
---

## tl;dr

```yaml
status:
  퍼플아이오 신규사업팀에서 함께 일할 사람을 찾고 있습니다.
```

우리는 전통적 SI를 AI 트랜스포메이션(AX)으로 바꾸는 팀이다. <span class="highlight">정해진 답을 구현하는 것이 아니라, 답이 뭔지부터 찾아야 하는 일</span>을 한다.

## requirements

```js
// candidate.check()
const requirements = {
  experience: ">=1y",
  ai_usage: "not_optional",
  domain_learning: "fast",
};
```

- **경력 1년 이상.** 무엇이든 직접 만들어서 운영해본 경험이 있는 사람.
- **AI를 도구로 쓸 줄 아는 사람.** AI가 뭔지 아는 것과 AI로 일하는 것은 다르다. 우리는 후자를 찾는다.
- **도메인을 빠르게 이해하는 사람.** 고객의 업종이 매번 다르다. 낯선 도메인에 던져져도 빠르게 핵심을 파악하는 능력이 필요하다.

> 특정 언어나 프레임워크는 묻지 않는다. 도구는 바뀌지만, 문제를 분해하고 해결하는 능력은 남는다.

## what_you_will_do

```md
# actual_work.log (not filtered)

- 09:30 고객사 도메인 공부하다가 해당 업계 전문가가 된 기분
- 10:15 "이거 에이전트로 되지 않을까?" 라는 말로 시작되는 회의
- 11:00 프로토타입 만들기 시작. 3시간 뒤 데모 예정
- 14:00 데모. 반응이 좋음. 스코프가 3배로 늘어남
- 15:30 어제 만든 설계를 오늘 엎음. 더 나은 방법을 찾아서
- 17:00 경영진에게 AI를 설명하는데 비유가 점점 늘어남
- 18:00 퇴근. 근데 샤워하다가 아이디어가 떠오름
```

`ai-agent` `consulting` `prototype-driven` `scope-creep-survivor`

## not_for_you_if

- ✕ 정해진 스펙대로만 구현하고 싶은 사람
- ✕ 불확실성이 불편한 사람
- ✕ AI를 아직 써본 적 없는 사람

## process

```js
// pipeline.stages()
const hiring = [
  { stage: 1, type: "online", desc: "화상 면접" },
  { stage: 2, type: "offline", desc: "대면 면접" },
];
```

## how_to_apply

```sh
# apply.sh

mailto=cs.kim@purple.io

attachments=[
  "자유 형식 이력서",
  "AI로 만든 포트폴리오 x 5"
]

# 이력서 형식은 자유. pdf, notion, github, 뭐든.
# 포트폴리오는 AI를 활용해서 만든 것.
# AI를 어떻게 활용했는지가 보고 싶다.
```

---

> 완벽한 이력서보다 흥미로운 포트폴리오가 낫고, 화려한 경력보다 AI와 함께 문제를 푸는 방식이 궁금하다.
