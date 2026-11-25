---
name: SPOTV NOW Golf 친구초대 이벤트
description: 12.17 티오프까지 남은 날을 세는 중계 오프닝 같은 팀 초대 이벤트 페이지 (SPOTV NOW ds5 위에 구축)
colors:
  brand: "#ff4600"
  on-brand: "#ffffff"
  bg-000: "#0c0c0c"
  bg-100: "#121212"
  bg-300: "#191919"
  surface-100: "#1e1e1e"
  surface-150: "#202020"
  surface-200: "#222222"
  surface-300: "#353535"
  line-100: "#2a2a2a"
  line-200: "#353535"
  line-250: "#2e2e2e"
  line-300: "#979797"
  line-400: "#414141"
  text-100: "#ffffff"
  text-150: "#e7e7e7"
  text-200: "#ededed"
  text-250: "#cfcfcf"
  text-300: "#9e9e9e"
  text-400: "#888888"
  text-placeholder: "#757575"
  text-disabled: "#595959"
  tooltip-bg: "#d8d8d8"
  scrim-strong: "rgba(0, 0, 0, 0.9)"
  scrim-soft: "rgba(10, 10, 10, 0.4)"
typography:
  display-numeral:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "clamp(120px, 13.2vw, 200px)"
    fontWeight: 800
    lineHeight: 0.8
    letterSpacing: "-0.04em"
    fontFeature: "tnum"
  numeral-lg:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "64px"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.04em"
    fontFeature: "tnum"
  display:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "44px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-1.5px"
  headline:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "36px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.9px"
  headline-lineup:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "30px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.75px"
  title:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "32px"
    letterSpacing: "-0.6px"
  title-sm:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: "28px"
    letterSpacing: "-0.5px"
  body-lg:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: "26px"
  body:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "24px"
  helper:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "21px"
  meta:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: "18.06px"
    letterSpacing: "-0.35px"
  caption:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: "20px"
  label-cta:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.5px"
  label-button:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Malgun Gothic, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: "19.98px"
    letterSpacing: "-0.45px"
rounded:
  xs: "3px"
  sm: "5px"
  md: "8px"
  tag: "4px"
  chip: "20px"
  cta: "30px"
  pill: "35px"
  full: "999px"
spacing:
  space-1: "4px"
  space-2: "8px"
  space-3: "12px"
  space-4: "16px"
  space-6: "24px"
  space-12: "48px"
  section: "96px"
  gutter: "92px"
components:
  cta-pill:
    backgroundColor: "{colors.brand}"
    textColor: "{colors.on-brand}"
    typography: "{typography.label-cta}"
    rounded: "{rounded.pill}"
    padding: "0 24px 0 32px"
    height: "64px"
  cta-pill-done:
    backgroundColor: "transparent"
    textColor: "{colors.brand}"
    typography: "{typography.label-cta}"
    rounded: "{rounded.pill}"
    height: "64px"
  button-primary:
    backgroundColor: "{colors.brand}"
    textColor: "{colors.on-brand}"
    typography: "{typography.label-button}"
    rounded: "{rounded.md}"
    padding: "0 24px"
    height: "48px"
  button-secondary:
    backgroundColor: "{colors.surface-300}"
    textColor: "{colors.text-100}"
    typography: "{typography.label-button}"
    rounded: "{rounded.md}"
    padding: "0 24px"
    height: "48px"
  button-disabled:
    backgroundColor: "{colors.surface-200}"
    textColor: "{colors.text-disabled}"
    rounded: "{rounded.md}"
    height: "48px"
  team-slot-empty:
    backgroundColor: "transparent"
    textColor: "{colors.text-300}"
    rounded: "{rounded.md}"
    padding: "12px 8px"
    height: "120px"
  team-slot-filled:
    backgroundColor: "{colors.surface-300}"
    textColor: "{colors.text-100}"
    rounded: "{rounded.md}"
    padding: "12px 8px"
    height: "120px"
  course-card:
    backgroundColor: "{colors.surface-200}"
    textColor: "{colors.text-100}"
    rounded: "{rounded.md}"
    padding: "24px"
  event-card:
    backgroundColor: "{colors.surface-100}"
    textColor: "{colors.text-250}"
    rounded: "{rounded.md}"
    padding: "24px"
  event-card-top:
    backgroundColor: "{colors.bg-300}"
    textColor: "{colors.text-100}"
    typography: "{typography.numeral-lg}"
    padding: "24px"
  lineup-band:
    backgroundColor: "{colors.bg-300}"
    textColor: "{colors.text-100}"
    padding: "48px 92px"
  dock:
    backgroundColor: "{colors.bg-100}"
    textColor: "{colors.text-250}"
    height: "80px"
  card:
    backgroundColor: "{colors.surface-200}"
    textColor: "{colors.text-250}"
    rounded: "{rounded.sm}"
    padding: "24px"
  input:
    backgroundColor: "{colors.surface-150}"
    textColor: "{colors.text-100}"
    rounded: "{rounded.sm}"
    padding: "0 16px"
    height: "48px"
  status-tag:
    backgroundColor: "transparent"
    textColor: "{colors.text-250}"
    rounded: "{rounded.tag}"
    padding: "0 8px"
    height: "28px"
  status-tag-on:
    backgroundColor: "transparent"
    textColor: "{colors.brand}"
    rounded: "{rounded.tag}"
    padding: "0 8px"
    height: "28px"
  gnb:
    backgroundColor: "{colors.bg-000}"
    textColor: "{colors.text-100}"
    typography: "{typography.body}"
    height: "80px"
  watch-button:
    backgroundColor: "transparent"
    textColor: "{colors.text-100}"
    rounded: "{rounded.pill}"
    padding: "0 16px 0 12px"
    height: "44px"
  footer:
    backgroundColor: "{colors.bg-100}"
    textColor: "#6a6a6a"
    padding: "80px 0 81px"
---

# Design System: SPOTV NOW Golf 친구초대 이벤트

## Overview

**Creative North Star: "티오프 중계 오프닝"**

이 시스템은 SPOTV NOW ds5 디자인시스템을 그대로 쓰면서, 이벤트 페이지를 골프 중계의 오프닝 화면처럼 연출합니다. 검정에 가까운 바탕 위에 대회까지 남은 날을 초대형 숫자로 세우고, 그 아래 중계 하단 자막 띠(lower-third) 같은 밴드에 "나 + 친구 3명" 팀 라인업을 놓습니다. 장식은 거의 없고, 위계는 숫자의 크기와 사진의 면적, 그리고 아주 드물게 쓰는 오렌지가 만듭니다.

밀도는 홍보 화면(`#/`)에서는 낮고 넓게, 내 팀 현황·로그인·회원가입 화면에서는 ds5 기본 컴포넌트 밀도 그대로 갑니다. 실사 사진(PGA 투어, 골프장, 경품)은 큰 면으로 쓰고, 가장자리는 검정으로 녹여 바탕과 하나가 되게 합니다. 깊이는 그림자가 아니라 바탕색 단계(#0c0c0c → #121212 → #191919 → surface 계열)로 표현합니다.

오렌지(`brand`)는 신호입니다. 카운트다운 숫자, 주요 CTA, 내 팀 칸, GNB 현재 위치, 체크, 응모 상태처럼 "지금 여기, 지금 할 일"에만 나타납니다. 중계 서비스의 `live`·`vod` 색은 이 이벤트 화면에서 쓰지 않습니다.

**Key Characteristics:**
- 검정 계열 바탕의 톤 단계만으로 만든 평평한 깊이
- Pretendard 800, 음수 자간, tabular 숫자로 만든 초대형 숫자 위계
- 점선(빈 칸) → 실선 면(채운 칸) → 오렌지 테두리(내 칸)로 상태를 보여 주는 4칸 팀 슬롯
- #191919 하단 자막 띠 밴드와 #191919 상단을 가진 중계 편성표식 이벤트 카드
- 검정으로 녹아드는 실사 사진과 아래쪽 scrim 그라데이션
- 오렌지는 신호에만, 장식 면에는 쓰지 않음

## Colors

ds5의 무채색 다크 스케일 위에 단 하나의 강한 오렌지가 놓인, 한 가지 목소리의 팔레트입니다.

### Primary
- **티오프 오렌지** (`brand`): 카운트다운의 날짜 숫자(D- 뒤 숫자), 알약형 주요 CTA, 기본 주요 버튼, 팀 라인업의 내 칸 테두리, 대시 바의 내 칸 표시, GNB 현재 메뉴, 체크 원형, 응모 상태 태그, 포커스 링, 텍스트 선택 배경. 위에 올리는 글자는 항상 `on-brand`(흰색)입니다.

### Neutral
- **중계석 블랙** (`bg-000`): 스테이지(카운트다운 + 사진) 바탕, 로그인 비주얼 바탕, 푸터. 사진이 녹아드는 최종 색입니다.
- **페이지 그라운드** (`bg-100`, ds5 bg-100): `body` 기본 바탕, 하단 대시와 모바일 고정 CTA 바탕.
- **자막 띠 그레이** (`bg-300`): 라인업 밴드, 이벤트 카드 상단, 노출 안내(reach) 블록, 내 팀 현황 상단 밴드.
- **카드 면** (`surface-100`, `surface-150`, `surface-200`): 이벤트·경품 카드(100), 입력 필드·응모 완료 줄(150), 일반 카드·모달·골프장 카드 사진 로딩 바탕(200).
- **채운 칸 / 보조 버튼** (`surface-300`): 채워진 팀 칸 면, 보조 버튼, 진행 막대 트랙, 3단계 상단 선.
- **선** (`line-100`, `line-200`, `line-250`, `line-400`): GNB·푸터 하단선(100), 밴드 상하선과 대시 상단선(200), 목록 구분선(250), 칩 테두리(400).
- **점선 그레이** (`line-300`): 빈 팀 칸의 점선, 상태 태그 기본 테두리, 워드마크 라벨 테두리.
- **글자 단계** (`text-100` ~ `text-400`): 제목과 숫자는 100, 강조 본문은 200, 본문은 250(대비 5.9:1 이상), 보조 설명은 300, 단계 번호·비활성 수준 정보는 400.
- **밝은 띠** (`tooltip-bg`): DEMO 배너와 토스트. 어두운 화면 위 유일한 밝은 면이며 시스템 메시지 전용입니다.
- **scrim** (`scrim-strong`, `scrim-soft`): 사진 위 글자를 받치는 그라데이션, GNB 반투명 바탕, 골프장 카드 혜택 배지.

### Named Rules
**The Orange Signal Rule.** `brand`는 카운트다운 숫자, 주요 CTA, 내 칸, GNB 현재 위치, 체크, 응모 상태, 포커스 링에만 씁니다. 배경 면, 장식 도형, 제목 강조에는 쓰지 않습니다. 한 화면에서 오렌지 요소를 모두 가려도 읽기에 문제가 없어야 하고, 오렌지만 남겨도 "어디를 누를지"가 보여야 합니다.

**The No Broadcast Red Rule.** ds5의 `live`(#ff0050)·`vod`(#7a43ff)는 번들에 있지만 이 이벤트 화면에서는 쓰지 않습니다. 생중계 예고도 무채색 글자로 씁니다.

**The Color-Free Error Rule.** ds5에 오류 색이 아직 없으므로, 오류 메시지는 색 대신 `text-100` 700 굵기로 구분합니다. 오류 색을 새로 만들지 않습니다.

## Typography

**Display Font:** Pretendard (Apple SD Gothic Neo, Malgun Gothic, system-ui 대체)
**Body Font:** Pretendard (동일)

**Character:** 한 가족의 글꼴을 굵기와 크기만으로 나눕니다. 숫자는 800 굵기와 좁은 자간으로 경기장 전광판처럼 세우고, 안내 문장은 400 굵기로 조용히 둡니다.

### Hierarchy
- **Display Numeral** (800, clamp(120px, 13.2vw, 200px), 0.8): 스테이지의 "D-22" 카운트다운 단 하나. 키 비주얼과 나란히 서도록 왼쪽 5/12 칸에 맞춘 크기. 모바일 104px.
- **Score Numeral** (800, 88px, 0.9): 지난해 결과 스코어보드의 팀 점수. 모바일 56px.
- **Numeral Large** (800, 64px, 0.9): 이벤트 카드의 대회 날짜(12.17). 모바일 44px. 같은 계열로 경품 수량(44px), 골프장 이름(36px, 자간 -1.2px), 단계 번호(40px, `text-400`)가 있습니다.
- **Display** (800, 44px, 1.2, -1.5px): 홍보 섹션 제목. 태블릿 36px, 모바일 28px.
- **Headline** (700, 36px, 1.25, -0.9px): 스테이지의 대회명. 태블릿 30px, 모바일 24px.
- **Headline Lineup** (700, 30px, 1.3): 라인업 밴드의 h1. 모바일 22px.
- **Title** (700, 24px/32px): 이벤트 카드 제목, 추가 경품·유의사항 제목, 내 팀 현황 이름.
- **Title Small** (700, 20px/28px): 단계 제목, 경품 이름, 카드 머리.
- **Body Large** (400, 17–18px, 26–28px): 섹션 머리 설명과 스테이지 부제. 최대 30em.
- **Body** (400, 16px/24px): 기본 본문.
- **Helper** (400, 14px/21px): 보조 설명, CTA 아래 도움말, 유의사항 목록.
- **Meta / Caption** (500 14px, 400 13px): 날짜, 링크 줄, 푸터.
- **Label CTA** (700, 20px, -0.5px): 알약 CTA. 모바일 18px, 대시 안 17px.

### Named Rules
**The Big Numeral Rule.** 날짜, D-day, 인원, 수량 같은 숫자는 Pretendard 800, `font-variant-numeric: tabular-nums`, 음수 자간(-0.04em 안팎)으로 씁니다. 화면의 위계는 숫자가 먼저 만들고, 문장은 그 숫자를 설명합니다.

**The Orange Button Floor Rule.** 오렌지 바탕 버튼의 라벨은 16px/700 아래로 내리지 않습니다. 작은 주요 버튼도 16px/700으로 올립니다.

## Layout

- **컨테이너:** 콘텐츠 폭 1200px(`--content-w`), 좌우 여백(gutter) 92px. 1279px 이하 48px, 767px 이하 16px.
- **반응형 구간:** 데스크톱 ≥1280, 1024–1279(GNB 간격 축소), 768–1023(GNB를 햄버거 메뉴로, 2열 → 1열), 모바일 <768. 360px에서 가로 스크롤이 없어야 합니다.
- **스테이지:** 화면 높이에 맞춘 높이(최소 480px, 최대 640px). 사진은 오른쪽 60%(태블릿 72%) 풀블리드, 숫자와 대회명은 왼쪽 컨테이너 안. 모바일에서는 사진 240px을 위에 두고 카운트다운이 사진 아래쪽에 88px 겹쳐 올라옵니다.
- **라인업 밴드:** 3열 그리드(문구 1.05fr · 팀 4칸 1.2fr · CTA auto), 간격 48px. 태블릿은 문구와 CTA가 한 줄, 팀 4칸이 아래 줄 전체. 모바일은 1열.
- **홍보 섹션 리듬:** 섹션 상하 96px(모바일 48px), 연속 섹션은 위 여백 0. 섹션 머리는 제목과 설명을 양 끝 아래 정렬로 두고 아래 48px(모바일 24px).
- **그리드:** 3단계와 골프장 카드는 3열, 추가 경품과 이벤트 카드는 2열, 모두 간격 12px. 태블릿 이하 1열.
- **간격 단위:** 4 / 8 / 12 / 16 / 24 / 48px만 씁니다. 큰 간격은 48의 배수로 만듭니다.
- **고정 요소:** DEMO 배너(32px)와 GNB(80px, 모바일 64px)는 위에 고정(sticky). 히어로의 CTA가 화면 위로 사라지면 하단 대시가 올라옵니다. 오른쪽 아래에는 맨 위로 버튼(56px 원)과 그 위 데모 도구 버튼. 터치 영역은 모두 44px 이상.

## Elevation & Depth

그림자로 띄우지 않고, 바탕 톤을 한 단계씩 밝혀서 층을 나눕니다. `bg-000`(스테이지, 푸터) → `bg-100`(페이지) → `bg-300`(밴드, 카드 상단) → `surface-100~300`(카드, 채운 칸) 순서로 위로 올라옵니다. 경계가 필요하면 1px 선(`line-100`/`line-200`)을 쓰고, 사진 위 글자는 scrim 그라데이션으로 받칩니다.

### Shadow Vocabulary
- **상태 링** (`box-shadow: inset 0 0 0 2px var(--brand)`): 응모 완료 상태의 알약 CTA 테두리. 활성 카드에는 1px(`inset 0 0 0 1px var(--brand)`). 바깥으로 퍼지는 그림자가 아니라 안쪽 테두리 역할만 합니다.

### Named Rules
**The Tonal Stack Rule.** 바깥 그림자(drop shadow)는 쓰지 않습니다. 층은 바탕 톤 단계와 1px 선으로만 나누고, `box-shadow`는 상태를 알리는 안쪽 링에만 씁니다.

**The Melt-to-Black Rule.** 글자가 없는 큰 사진은 가장자리를 `bg-000`으로 녹입니다. 사진 카드는 아래 60%에 `scrim-strong` 그라데이션을 깔고 그 위에 글자를 올립니다. 예외: 대회 키 비주얼처럼 글자와 선수 이름이 가장자리까지 들어간 포스터는 자르지 않습니다. 화면 전체 너비 띠(높이 41vw, 최대 600px) 가운데에 원본 비율로 놓고, 양옆은 같은 이미지를 흐리게(blur 36px, 밝기 60%) 깔아 이어 붙입니다. 포스터 좌우 끝 2.5%만 부드럽게 녹입니다. 출처는 오른쪽 위 작은 캡션.

**Section Head Rule.** 섹션 제목(44px/800)은 한 줄로 쓰고, 설명(19px `text-200`)은 제목 바로 오른쪽 아래 기준선에 붙입니다. 자리가 모자라면 설명이 아래로 내려갑니다. 홍보 페이지 본문은 18px, 보조 글은 16px 이상(`main.promo`에서 토큰을 키움).

## Shapes

모서리는 작게 시작해 행동할수록 둥글어집니다. 정보 면(카드, 팀 칸, 사진 카드, 이벤트 카드)은 8px(`md`), 작은 안쪽 면(입력, 일반 카드, 썸네일, 토스트)은 5px(`sm`), 상태 태그는 4px(`tag`)입니다. 누르는 것 중 이벤트의 주요 행동은 완전한 알약(35px, `pill`), 폼 안의 알약 CTA는 30px(`cta`), 칩은 20px(`chip`)입니다. 아바타, 혜택 배지, 진행 막대, 대시의 칸 표시는 완전한 원·캡슐(999px)입니다.

선은 상태를 말합니다. 1px 점선(`line-300`)은 "아직 비어 있음", 실선 면은 "채워짐", 2px 오렌지 실선은 "나"입니다.

## Components

### Buttons
홍보 화면의 주요 행동은 크고 둥근 알약 하나로, 나머지는 ds5 기본 버튼으로 갑니다.
- **알약 CTA (cta-pill):** `brand` 바탕, 흰 글자 20px/700, 높이 64px(모바일 56px, 대시 안 52px·모바일 48px), 완전한 알약, 왼쪽 패딩이 오른쪽보다 8px 넓고 오른쪽에 22px 화살표 SVG. 상태에 따라 라벨이 바뀝니다(초대코드 만들기 → 초대 링크 공유하기 → 응모 완료 · 내 팀 보기).
- **알약 CTA 완료 (cta-pill-done):** 투명 바탕, `brand` 글자, 2px 안쪽 오렌지 링, 화살표 없음. hover 시 오렌지 12% 섞은 바탕.
- **기본 주요 버튼 (button-primary):** `brand` 바탕, 높이 48px, 8px 모서리, 18px/700.
- **보조 버튼 (button-secondary):** `surface-300` 바탕, 흰 글자.
- **Hover / Focus / Active:** hover는 바탕을 흰색 쪽으로 14% 섞어 밝힘(`color-mix(in srgb, var(--brand) 86%, var(--text-100))`), 화살표는 3px 오른쪽으로 이동. 누르면 1px 아래로. 포커스는 모든 요소에 2px `brand` 링(offset 2px). 비활성은 `surface-200` 바탕, `text-disabled` 글자.

### Team Slots (팀 4칸, signature)
"나 + 친구 3명"을 한 줄 4칸으로 보여 주는 이 이벤트의 중심 컴포넌트입니다. 홍보 라인업, 회원가입 초대 정보, 내 팀 현황에서 같은 규칙으로 씁니다.
- **빈 칸:** 투명 바탕, 1px 점선 `line-300`, 8px 모서리, 가운데 정렬된 32px 점선 원 안에 순번, 아래 라벨 14px `text-300`.
- **채운 칸:** `surface-300` 면, 흰 글자 700. 친구 칸은 오렌지 체크 원(32px), 주인 칸은 `text-300` 원 안에 이름 첫 글자.
- **내 칸:** 2px `brand` 실선 테두리(주인 칸 또는 가입하면 들어갈 다음 칸).
- **크기:** 기본 최소 높이 88px, 큰 칸(`is-lg`) 120px·원 44px, 모바일 76/88px. 칸 간격 8px. 이름은 첫 글자 뒤를 가립니다(홍**).

### Dock (하단 고정 팀 바)
라인업 CTA가 화면 위로 사라지면 아래에서 올라오는 바입니다. `bg-100` 94% 반투명, 위 1px `line-200`, 최소 높이 80px(모바일 72px). 왼쪽에 4칸 캡슐 표시(28×8px, 내 칸 `brand`, 채운 칸 `text-150`, 빈 칸 `surface-300`)와 한 줄 상태, 오른쪽 끝에 알약 CTA. 모바일에서는 문장을 숨기고 CTA가 남은 폭을 채웁니다. 0.35s `cubic-bezier(.16, 1, .3, 1)`로 올라옵니다.

### Course Photo Cards (골프장 경품 카드)
- **형태:** 4:5 세로 사진 카드(모바일 16:10), 8px 모서리, 넘침 잘라냄.
- **글자:** 아래 60% `scrim-strong` 그라데이션 위에 골프장 이름 36px/800(-1.2px), "라운드 1팀" 17px/700, 지급 설명 14px.
- **배지:** 왼쪽 위 혜택 배지(32px 캡슐, `scrim-strong` 바탕, 13px/700), 오른쪽 위 사진 출처(11px, `scrim-soft`, 3px 모서리). 실사 사진에는 출처를 붙입니다.
- **Hover:** 사진이 0.8s 동안 1.04배로 천천히 확대.

### Goods Cards (추가 경품)
`surface-100` 바탕, 8px 모서리, 16px 패딩, 200px 정사각 제품 사진(밝은 `text-200` 바탕 위 contain, 모바일 104px) + 이름 20px/700과 수량 44px/800 숫자("명"은 18px). 예시 이미지는 그렇다고 적습니다.

### Event Cards (이색 대회 카드)
중계 편성표처럼 날짜가 먼저 보이는 카드입니다. `surface-100` 몸통, 8px 모서리. 상단은 `bg-300` 띠에 대회 날짜 64px/800과 요일, 오른쪽 끝에 D-day 28px/800 `text-300`, 아래 1px `line-100`. 몸통은 제목 24px/700, 본문, 위 선이 있는 정의 목록(형식·편성·출전, `text-300` 이름 / `text-100` 값), 필요할 때만 기본 주요 버튼.

### Matchup Band (4 vs 4 프로 팀 명단)
히어로 아래 `bg-300` 상자, 1px `line-100`. 양쪽에 팀 이름 22px/800 + 작은 영문/보조 라벨, 선수 칸 4개(`surface-100`, 이름 16px/700, 보조 13px `text-250`, 주장 칸만 1px `line-400` 테두리). 가운데 "4 vs 4" 36px/800. 이벤트의 "4명이 한 팀"과 같은 숫자를 일부러 맞춥니다.

### Rulebook Rows (경기 규칙)
카드가 아닌 행 목록입니다. 위 1px `line-300`, 행 사이 1px `line-200`, 3열(이름 22px/700 + 상태 태그 / 설명 16px `text-200` / 오른쪽 정렬 핵심 수치 24px/800). 상태 태그는 테두리형("2026 확정", "2025 방식"), 신규만 흰 바탕 검정 글자.

### Comparison Table (정규 대회 vs 골프채널 게임스)
`<table>`, 행 사이 1px `line-200`. 비교 대상 열은 `text-250`, 이 대회 열은 `surface-100` 바탕 + `text-100` 굵은 값과 14px 보조 설명.

### Scoreboard (지난해 결과)
`bg-300` 상자에 팀 이름 26px/800, 명단 14px, 점수 88px/800. 이긴 팀은 흰 바탕 "우승" 태그, 진 팀 점수와 이름은 `text-250`. 가운데 `surface-100` 작은 칸에 연장 설명. 아래 챌린지별 `<table>`(누적 점수 오른쪽 정렬, 연장 행만 `surface-100`).

### Tour Strip (SPOTV NOW Golf에서 시청하세요!)
투어 로고(64px, 가로형 38px) + 이름 18px/700만 있는 5칸 띠. `surface-100` 바탕, 8px 모서리, 1px `line-200` 테두리와 칸 사이 세로선. 로고가 없는 투어는 영문 이름을 20px/800 글자로. 태블릿 3칸 2줄, 모바일은 가로 스크롤 띠. 아래 한 줄로 대항전·이색 대회 안내.

### Section Separation
섹션마다 위 1px `line-200` 구분선, 배경은 `bg-100`과 `bg-000`(is-alt)을 번갈아. 모바일은 구분선 대신 섹션 사이 10px 띠(`bg-000`/`bg-300`).

### Step Illustrations (참여 방법)
디자인시스템 색에 묶이지 않는 직접 그린 SVG 일러스트(16:10). 단계마다 다른 바탕 그라데이션(오렌지 / 네이비 / 그린)과 친구 아바타 색(민트 #21c7a8, 보라 #7b6cff, 노랑 #ffb020), 흰 체크 배지. 카드는 위 일러스트 + 아래 흰 원 번호 · 24px 제목 · 17px 설명. 태블릿은 일러스트와 글을 좌우로.

### Footer
spotvnowgolf.co.kr/golf 푸터를 그대로 옮깁니다. 위 1px `#2a2a2a`, 위아래 80/81px, 14px/18px `#6a6a6a`. 왼쪽 로고(181px) → 사업자 정보 3줄 → 저작권, 오른쪽 Google Play·App Store 배지(40px, 간격 20px). 모바일은 가운데 정렬, 배지 32px.

### Cards / Containers
- **Corner Style:** 일반 카드 5px, 홍보 카드 8px.
- **Background:** `surface-200`(일반, 내 팀 현황), `surface-100`(홍보 카드), `bg-300`(밴드, 노출 안내 블록).
- **Shadow Strategy:** 없음. Elevation & Depth의 Tonal Stack Rule을 따릅니다.
- **Internal Padding:** 24px(모바일 16px).

### Chips / Tags
- **상태 태그:** 28px 높이, 4px 모서리, 1px `line-300` 테두리, 13px/700 `text-250`. 켜진 상태(`is-on`)는 테두리와 글자 모두 `brand`.
- **리그 칩:** 36px 높이, 20px 모서리, 1px `line-400`, 14px/700. 강조 칩은 테두리 `text-250`.

### Inputs / Fields
- **Style:** `surface-150` 바탕, 테두리 없음, 5px 모서리, 높이 48px(로그인 패널 안 50px·`surface-300`), 15px 글자, placeholder `text-placeholder`.
- **Focus:** 2px `brand` 안쪽 링(offset -2px).
- **Label / Help:** 라벨 14px/700 `text-250`이 위에, 도움말 14px `text-300`이 아래. 모든 입력에 `<label>`을 붙입니다.
- **Error:** `text-100` 700 굵기 문장(Color-Free Error Rule).

### Navigation
- **GNB(이벤트 서브사이트 헤더):** spotvnowgolf.co.kr/asian-swing과 같은 틀. 높이 80px(모바일 64px), `bg-000` 92% 바탕, 아래 1px `line-100`, DEMO 배너 아래 sticky. 왼쪽 흰색 공식 로고(28px, 1279px 이하 24px, 모바일 17px) + 1px `line-400` 세로선 + 이벤트명 25px/800(GNB 메뉴명 미정, `EVENT_NAME`). 오른쪽에 메뉴 '내 팀 현황' 18px/500(현재 위치면 `brand`), 로그인 15px `text-200`, "SPOTV NOW Golf에서 중계 보기" 버튼.
- **서브메뉴:** GNB 바로 아래 sticky 56px(모바일 48px, 가로 스크롤) 줄. 참여 방법 · 경품 · 대회 정보 · 일정, 18px/600 `text-250`. 스크롤 위치의 섹션은 `text-100` + 아래 3px `brand` 밑줄.
- **중계 보기 버튼:** 44px 알약, 1px `line-400` 테두리, 왼쪽 24px 오렌지 원 재생 아이콘(SPOTV NOW 로고의 ▶와 같은 역할), 15px/700, 오른쪽 새 창 아이콘. 1365px 이하 "중계 보기", 모바일은 아이콘만.
- **모바일/태블릿(≤1023px):** 메뉴를 숨기고 중계 보기 버튼 + 44px 햄버거 버튼. 로그인·회원가입은 펼친 메뉴 안. 펼친 메뉴는 ds5 사용자 메뉴 패널(`surface-100`) 안 가운데 정렬 목록, 현재 위치 `brand`.

## Do's and Don'ts

### Do:
- **Do** 오렌지(`brand`)를 카운트다운 숫자, 주요 CTA, 내 칸, GNB 현재 위치, 체크, 응모 상태, 포커스 링에만 쓰세요.
- **Do** 날짜·D-day·인원·수량은 Pretendard 800, tabular-nums, 음수 자간으로 크게 세우세요.
- **Do** 팀 상태는 점선 빈 칸 → `surface-300` 채운 칸 → 2px `brand` 내 칸 순서로 표현하고, 어느 화면에서든 같은 4칸 규칙을 쓰세요.
- **Do** 층은 `bg-000` → `bg-100` → `bg-300` → `surface` 단계와 1px 선으로 나누세요.
- **Do** 큰 실사 사진은 `bg-000`으로 녹이고, 사진 위 글자는 `scrim-strong` 그라데이션 위에 올리세요. 실사 사진에는 출처를 적으세요.
- **Do** 간격은 4/8/12/16/24/48px 단위, 섹션은 96px(모바일 48px)로 맞추세요.
- **Do** 등장 동작은 `cubic-bezier(.16, 1, .3, 1)` 한 가지 감속 곡선으로 쓰고, `prefers-reduced-motion`에서는 끄세요.

### Don't:
- **Don't** 오렌지를 배경 면, 장식 도형, 제목 강조 글자에 쓰지 마세요.
- **Don't** `live`(#ff0050)·`vod`(#7a43ff) 색을 이 이벤트 화면에 쓰지 마세요.
- **Don't** 카드나 버튼에 바깥 그림자(drop shadow)나 어긋난 그림자(offset shadow)를 쓰지 마세요. `box-shadow`는 안쪽 상태 링에만 씁니다.
- **Don't** 오류 표시를 위해 새 빨간색을 만들지 마세요.
- **Don't** 오렌지 버튼 라벨을 16px/700 아래로 내리지 마세요.
- **Don't** 확정되지 않은 경품·기간을 확정처럼 보이게 하지 말고, 예시 이미지와 예시 값은 그렇다고 적으세요.
- **Don't** 이모지를 쓰지 마세요.
