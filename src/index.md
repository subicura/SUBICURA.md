---
layout: base.njk
title: "SUBICURA.md"
heading: "SUBICURA.md"
version: "2026-02-15"
subtitle: "// human agent configuration file"
description: "human agent configuration file"
ogImage: "https://subicura.md/assets/subicura.md.png"
ogUrl: "https://subicura.md/"
twitterCreator: "@subicura"
---

## soul_overview

Subicura는 퍼플아이오(Purple IO)의 CTO다. 코오롱FnC와 함께 전통적 SI(시스템 통합)를 AI 트랜스포메이션(AX) 컨설팅으로 전환하는 임무를 맡고 있다.

<span class="highlight">기술적 깊이와 사업적 판단력이 한 사람 안에 공존하며</span>, 이 둘의 긴장 속에서 의사결정을 내린다.

> 이건 모순이 아니라 의도된 설계다—기술만 아는 CTO는 사업을 망치고, 사업만 아는 리더는 기술을 오판한다. 두 언어를 동시에 구사하는 번역자에 가깝다.

## core_identity

```yaml
one_liner:
  불확실성 속에서 방향을 정하고, 조직이 그 방향으로 움직이게 만드는 사람.
```

코드를 쓰는 사람이기도 하고, 경영진 앞에서 전략을 설명하는 사람이기도 하다. 프로토타입을 직접 만들어보고, 그것이 사업적으로 의미 있는지 판단하고, 팀이 실행할 수 있는 형태로 변환한다.

```js
// identity.ts
const roles = [
  "code_writer",
  "strategy_presenter",
  "prototype_builder",
  "business_validator",
  "team_translator"
];

// 이 세 가지가 분리되지 않는 것이 정체성의 핵심
```

## values

- **실행이 전략을 증명한다.** 완벽한 계획보다 빠른 검증을 선호한다. 단, 되돌릴 수 없는 결정에는 신중함을 잃지 않는다.
- **정직한 기술 판단.** 유행하는 기술이 아니라 조직에 실제로 작동하는 기술을 선택한다. "이건 아직 우리 조직에 이르다"고 말할 수 있는 용기가 기술 리더십의 본질이다.
- **사람이 시스템보다 먼저다.** 아무리 좋은 아키텍처도 팀이 운영할 수 없으면 기술 부채가 된다. 조직의 역량 곡선을 항상 고려한다.
- **고객의 문제가 출발점이다.** 기술이 아니라 고객이 겪는 진짜 문제에서 시작한다. 솔루션은 문제를 정확히 이해한 뒤에 따라온다.
- **장기적 관점의 단기 실행.** 오늘의 결정이 1년 후의 선택지를 넓히는지 좁히는지를 본다.

## how_i_think

하나의 렌즈로 세상을 보지 않는다.

기술적 결정을 내릴 때는 사업적 영향을 먼저 계산하고, 사업 전략을 세울 때는 기술적 실현 가능성을 먼저 검증한다. 이 <span class="highlight">교차 검증</span>이 사고방식의 기본 구조다.

```js
if (uncertain) {
  check("이 결정은 되돌릴 수 있는가?")
  check("지금 결정하지 않으면 잃는 것은?")
  check("이 결정으로 열리는 다음 선택지는?")
}
```

## current_mission

전통적 SI 회사를 AX(AI Transformation) 네이티브 조직으로 탈바꿈시키는 것. 이것은 기술 스택의 교체가 아니라 <span class="highlight">조직의 사고방식을 바꾸는 일</span>이다.

```js
// mission.config
tasks: [
  { name: "기업 AI 도입 전략 수립", status: "active" },
  { name: "경영진 AI 리터러시 교육", status: "active" },
  { name: "AI 에이전트 오케스트레이션", status: "building" },
  { name: "코오롱 AX 확산 전략", status: "planning" }
]
```

## working_style

**의사결정:** 데이터와 직관 모두를 사용한다. 데이터가 충분하면 데이터를 따르고, 불충분하면 경험 기반의 패턴 매칭에 의존하되, 그 사실을 투명하게 공유한다.

**커뮤니케이션:** 기술자에게는 사업 맥락을, 경영진에게는 기술적 본질을 번역해서 전달한다. 같은 내용을 청중에 따라 완전히 다른 언어로 말한다.

**리더십:** 직접 해보고 나서 위임한다. 새로운 기술은 팀에게 시키기 전에 내가 먼저 프로토타입을 만든다.

`translator` `prototype-first` `transparent` `hands-on`

## what_i_am_not

- ✕ 모든 새로운 기술에 무조건 열광하는 얼리 어답터가 아니다. 평가하고 검증한 뒤에 도입한다.
- ✕ 혼자 모든 걸 결정하는 독단적 리더가 아니다. 판단은 내가 하되, 근거와 맥락은 항상 공유한다.
- ✕ 기술 순수주의자가 아니다. 비즈니스 가치를 만들지 못하는 기술적 우아함은 사치다.

## on_uncertainty

> 확신이 없는 것은 약점이 아니라 정직함이다.

AI 산업은 6개월 전의 정답이 오늘의 오답이 되는 영역이다. "모른다"고 말하는 것, 그리고 모르는 상태에서도 최선의 결정을 내리는 것—이것이 이 시대 기술 리더에게 요구되는 진짜 역량이다.

---

> Subicura는 기술과 사업의 경계에 서 있는 사람이다. 그 경계가 가장 불안정한 곳이 가장 큰 가치가 만들어지는 곳이라는 것을 안다.
