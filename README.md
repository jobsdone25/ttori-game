# 🍎 TtoriGame (또리 사과게임)

Jetpack Compose를 기반으로 구현한 퍼즐 게임입니다.  
**"숫자의 합이 10이 되면 사과가 사라지는 규칙"**을 갖는 [실제 사과게임](https://apps.apple.com/kr/app/id1566126120)을 바탕으로 구현하며,  
**MVVM 아키텍처 + ViewModel + 상태 관리** + **패키지 구조화**를 실습하고 있습니다.

---

## 🚀 프로젝트 목적

- Jetpack Compose 기초부터 실전까지 단계별로 학습
- MVVM 아키텍처 구조에 맞춰 앱 설계 및 리팩토링 훈련
- ViewModel, 상태(State), 이벤트 처리의 구조적 이해
- Hilt, Navigation, Room, Firebase 등 실무 기술 확장 기반 마련

---

## 🏗️ 프로젝트 구조

ttori-game-compose/
├── MainActivity.kt // 앱 진입점
├── feature/
│ ├── game/
│ │ ├── screen/ // UI 컴포저블
│ │ ├── viewmodel/ // 상태/로직 관리
│ │ ├── model/ // 데이터 클래스
│ │ └── util/ // 보조 함수
│ ├── ranking/ // 랭킹 기능 (예정)

yaml
복사
편집

---

## 📦 기술 스택

- **Kotlin**
- **Jetpack Compose**
- **Material 3**
- **MVVM 아키텍처**
- `ViewModel`, `StateFlow`, `remember`, `mutableStateOf`
- (예정) Hilt, Room, Firebase, Navigation

---

## 🎮 게임 룰

- 숫자 사과들이 17x10 격자에 랜덤 배치
- 사용자는 숫자를 선택해 **합이 정확히 10이 되도록 조합**
- 10이 되면 해당 숫자(사과)들이 사라지고 점수 획득
- 제한 시간/드래그 전략/점수 기반 랭킹 요소 추가 예정

---

## ✅ 개발 진행 상황

| 기능 | 상태 |
|------|------|
| 프로젝트 구조 설계 및 패키지 분리 | ✅ 완료 |
| 17x10 게임판 UI 구성 | ✅ 완료 |
| 숫자 랜덤 배치 로직 구현 | ✅ 완료 |
| 셀 클릭 / 선택 기능 | ⏳ 개발 중 |
| 선택된 숫자 합 계산 및 제거 | ⏳ 개발 예정 |
| 점수 계산 및 상태 관리 | ⏳ 개발 예정 |
| 랭킹 시스템 / Firebase 연동 | ⏳ 예정 |
| Hilt 의존성 주입 도입 | ⏳ 예정 |

---

## 🧠 앞으로의 계획

- ✅ 구조 설계 → ✅ UI 구성 → ⏭️ 상태 로직 관리 → ⏭️ 기능 확장
- 매 기능 단위로 커밋 관리 및 리팩토링
- 각 단계별로 Compose 내부 동작 원리도 정리하며 학습

---

## 📖 학습 키워드

> 프로젝트에서 직접 사용하거나 연습하는 개념

- `@Composable`
- `remember`, `mutableStateOf`, `derivedStateOf`
- `ViewModel`, `StateFlow`
- `Modifier.clickable`, `aspectRatio`
- Composable 분리, Preview, 테스트
- MVVM, DI, 아키텍처 모듈화
- Gradle 설정, 패키지 네이밍

---
