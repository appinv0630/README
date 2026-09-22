# 사이버 워
# 근시대적 미래에 찾아오는 사이버 보안 전쟁

## 1. Game Overview
## 1. 게임 개요

| 항목 | 내용 |
|---|---|
게임 제목 | Where do we Go? |
| 장르 | FPS / Action |
| 게임 제목 | **Where do we Go?** |
| 장르 | FPS / Action / Survival |
| 개발 엔진 | Unreal Engine 5.4.4 |
| 플랫폼 | PC / 데스크탑 및 노트북 등 |
| 엔진 | Unreal Engine / 언리얼 엔진 |
| 플레이 방식 | Single Player / 싱글 플레이어 (단독) |
| 시점 | First Person / 1인칭 |
| 예상 플레이 시간 | 10~15분 |

## 2. Game Concept
### 한 줄 소개
> 사이버 보안 프로그램을 뚫고 현실과 사이버 공간 바이러스에 감염된 연구 시설에서 적을 처치하고 여러 아이템들을 획득하며, 마스터 보안 카드 키를 획득하여 제한 시간 안에 탈출하는 1인칭 FPS 게임

현실과 가상을 넘나드는 바이러스에 감염된 연구소에서 감염된 적을 피해 탈출하는
1인칭 액션 슈팅 게임
---

## 3. Core Gameplay Loop
## 2. 게임 컨셉

맵 탐색
↓
적 발견
↓
전투 실행
↓
아이템 획득
↓
다음 지역 이동
+플레이어는 정체불명의 현실과 사이버 공간을 넘나드는 감염 사고가 발생한 연구 시설 내부에서 깨어난다.
+
+시설 내부에는 감염된 적들이 등장하며, 플레이어는 무기를 사용, 조준 및 발사의 과정을 통하여 적을 제거하고 탈출에 필요한 ** 마스터 보안 카드 키(Key Card)**를 찾아야 한다.

![Gameplay Loop](images/gameplay_loop.png)
최종적으로 마스터 보안 카드 키를 이용해 출구를 개방하고 감염된 연구 시설을 탈출하면 게임을 클리어한다.

## 4. Player Actions
### 핵심 키워드

- Move
- Look
- Jump
- Run
- Attack
- Interaction
- **Explore** : 연구 시설 맵 탐색
- **Combat** : 적과의 1인칭 FPS 전투
- **Collect** : 탄약 및 보안 카드 키 획득
- **Escape** : 탈출로 개방 및 게임 클리어

## 5. Game System
---

- Character Movement
- Combat System
- Enemy System
- Health System
- Game Clear System
- Game Over System
## 3. 게임 목표

## 6. Level Design
플레이어의 최종 목표는 다음과 같다.

![Map](images/map.png)
1. 연구시설 내부를 탐색한다.
2. 맵 내부에 등장하는 적을 처치한다.
3. 보안 카드키를 획득한다.
4. 맵을 이동하며 보안 카드키를 사용할 탈출로를 찾는다.
5. 마스터 보안 카드 키를 사용하여 잠겨진 보안 문을 연다.
6. 제한 시간 안에 탈출하면 게임 클리어 / 제한 시간 안에 탈출 못할 시 게임 오버

## 7. UI Design
---

![UI](images/ui_mockup.png)
## 4. Core Gameplay Loop

## 8. Development Plan
게임의 핵심 플레이 흐름은 다음과 같다.

| Priority | Feature |
```text
맵을 탐색하며 적을 찾는다.
  ↓
적을 발견한다.
  ↓
무기 조준 및 사격 실행.
  ↓
적 처치 완료.
  ↓
아이템 / 탄약 획득.
  ↓
다음 구역 이동.
  ↓
마스터 보안 카드 키 획득.
  ↓
탈출
```

플레이어는 게임이 종료될 때까지 **탐색 → 전투 → 아이템 획득 → 이동**의 과정을 반복한다.

---

## 5. 플레이어 조작

| 입력 | 기능 |
|---|---|
| 1 | Character Movement |
| 2 | Camera |
| 3 | Combat |
| 4 | Enemy |
| 5 | UI |
| 6 | Game Clear |
| W / A / S / D | 캐릭터 이동 |
| Mouse | 시점 회전 |
| Left Click | 총 발사 |
| Right Click | 조준 |
| Space | 점프 |
| Shift | 달리기 |
| R | 재장전 |
| E | 아이템 획득 / 보안  상호작용 |

---

## 6. 플레이어 기능

### 6.1 이동

플레이어는 1인칭 FPS 방식으로 맵 내부를 자유롭게 이동하며 탐색 및 적과 조우 가능하다.

주요 기능:

- 앞으로 / 뒤로 이동
- 좌 / 우 이동
- 마우스 시점 회전
- 점프
- 달리기
- 무기 조준 및 발사


