[![Header](https://capsule-render.vercel.app/api?type=waving&color=0E1128&fontColor=ffffff&height=200&section=header&text=고필규%20|%20Game%20Client%20Programmer&fontSize=36&animation=fadeIn&desc=UE5%20/%20C%2B%2B%20/%20GAS%20기반%20멀티플레이%20전투%20시스템%20개발&descSize=16&descAlignY=75)](https://github.com/kofeeel)

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2962FF&center=true&vCenter=true&width=520&lines=GAS+Combat+Pipeline+Architect;Network+Optimization+%7C+83→22+bytes;Data-Driven+Game+Development;Steam+Demo+Published+%7C+GameAnalytics)](https://git.io/typing-svg)

</div>

---

## 🛠️ Tech Stack

<div align="center">

**Engine & Language**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Unreal Engine 5](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Tools & Collaboration**

![Perforce](https://img.shields.io/badge/Perforce-404040?style=for-the-badge&logo=perforce&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Rider](https://img.shields.io/badge/Rider-000000?style=for-the-badge&logo=rider&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

</div>

```
🎯 GAS         ExecCalc · AttributeSet · GameplayCue · Custom EffectContext · Meta Attribute
🌐 Network     Replication · NetSerialize · Bit-Packing · COND_OwnerOnly · Network Profiler
🎨 Rendering   Dynamic Material Instance · MPC · Opacity Masking · Niagara · Cascade
📦 Data        DataTable · DataAsset · CurveTable · GameplayTag · Data-Driven Architecture
🔧 Tools       Tilemap Editor · Binary Serialization · Python Automation · MCP · AI Tools
📋 Planning    Level Design · Game Design · Task Management · Perforce Commit Convention
```

---

## 🎮 Projects

<br>

### [Omega Protocol](https://github.com/kofeeel/OmegaProtocol)

**GAS 기반 3인 협동 로그라이트 슈터 · Steam Demo 출시**

<a href="https://store.steampowered.com/app/3891070/Omega_Protocol_Demo/">
  <img src="https://github.com/kofeeel/OmegaProtocol/blob/main/Image/omegaimage.png?raw=true" width="600"/>
</a>

<br>

[![Steam Demo](https://img.shields.io/badge/Steam-Demo%20플레이-1b2838?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com/app/3891070/Omega_Protocol_Demo/)
[![YouTube](https://img.shields.io/badge/YouTube-플레이%20영상-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/Iia-4RZ8x-8?si=UYuBpHaU8vrV6uMW)
[![GitHub](https://img.shields.io/badge/Code-GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kofeeel/OmegaProtocol)

> `Unreal Engine 5` `GAS` `C++` `Perforce` · **프로그래머 5인 · 8주** (2025.06 ~ 2025.08)

<details>
<summary><b>담당 역할 — 전투 시스템 · 네트워크 최적화 · 기획 · 레벨디자인 · 스팀 배포</b></summary>
<br>

| 영역 | 구현 내용 |
|:--|:--|
| **GAS 전투 파이프라인** | ExecCalc 중앙화로 20여 종 스킬의 데미지 연산(치명타·넉백·흡혈·디버프)을 단일 파이프라인으로 통합 |
| **네트워크 최적화** | Custom Context NetSerialize — bool 4개 비트 패킹 + FVector 양자화로 패킷 **83 → 22 bytes** (73% 절감) |
| **렌더링 최적화** | Multicast RPC → Static GameplayCue + 클라이언트 필터링으로 다인 교전 시 부하 **~67% 감소** |
| **데이터 무결성** | Meta Attribute(IncomingDamage) 패턴으로 무적·쉴드 예외 검증 후 체력 반영 |
| **데이터 설계** | DataTable/CurveTable 기반 스킬·캐릭터·적 밸런싱 — 코드 수정 없이 CSV로 즉시 반영 |
| **시야 시스템** | MPC 기반 쿼터뷰 오브젝트 마스킹 (내적 계산 + Dithered Opacity Mask) |
| **적 AI** | BehaviorTree + DataAsset 연동 네임드 몬스터 — 5개 어빌리티, 거리 기반 행동 분기 |
| **기획 & 레벨디자인** | 캐릭터·스토리·스킬 기획 전담, 모듈식 레벨 5개 스테이지 직접 제작 |
| **스팀 배포** | SteamGUI 빌드 배포, 상점페이지 작성, GameAnalytics 연동으로 노출수·플레이타임 분석 |
| **협업 리딩** | Perforce 커밋 컨벤션·폴더별 관리 규칙 수립, 태스크 관리표·간트차트 운영 |

</details>

<br>

---

<br>

### [Run Better Run (타계)](https://github.com/kofeeel/RunBetterRun)

**C++ 레이캐스팅 기반 2.5D 공포 탈출게임**

<a href="https://kofeeel.itch.io/transmundus">
  <img src="https://github.com/leebo155/RunBetterRun/raw/main/screenshots/main.png" width="600"/>
</a>

<br>

[![Play on itch.io](https://img.shields.io/badge/itch.io-플레이-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white)](https://kofeeel.itch.io/transmundus)
[![GitHub](https://img.shields.io/badge/Code-GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kofeeel/RunBetterRun)

> `C++` `WinAPI` `SDL` `Git` · **프로그래머 4인 · 2주** (2025.04 ~ 2025.05)

<details>
<summary><b>담당 역할 — 타일맵 에디터 · 데이터 직렬화 · 맵/데이터 매니저</b></summary>
<br>

| 영역 | 구현 내용 |
|:--|:--|
| **타일맵 에디터** | 5가지 편집 모드(Tile·Start·Item·Monster·Obstacle) · 드래그 배치 · 뷰포트 컬링 |
| **데이터 직렬화** | 바이너리(.dat) 저장 · 파일 시그니처 기반 무결성 검증 · DataManager 패턴 |
| **아키텍처** | 에디터 ↔ 게임 로직 분리 설계 · 동적 좌표 변환(ScreenToTile, TileToScreen) |
| **예외 처리** | DDA 알고리즘 ray.distance=0 → 에디터 입력 단계에서 인접 벽 검증으로 크래시 원천 차단 |

</details>

<br>

---

## 🎓 Education

```
📘 원티드 포텐업 2기 수료     2025.02 ~ 2025.08    UE5 멀티플레이 프로젝트 · WinAPI 프로젝트 2개
🎓 수원대학교 학사 졸업       2018.03 ~ 2025.02    컴퓨터학부 전공 · 학점 3.5/4.5
```

---

## 📈 Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=kofeeel&theme=tokyo-night&hide_border=true&area=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=kofeeel&theme=github-light&hide_border=true&area=true">
  <img alt="GitHub Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=kofeeel&theme=tokyo-night&hide_border=true&area=true">
</picture>

---

## ⚡ Fun Facts

```
🎮 최애 게임     몬스터 헌터, 니케
⚽ 스포츠        축구 
🎬 휴식          드라마 · 영화 감상
```

---

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0E1128&height=100&section=footer&animation=twinkling)](https://github.com/kofeeel)
