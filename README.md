# AIXAC.RX.SW.SB — Releases

X-ray 보안 검색 장비(**AIXAC.RX.SW.SB**) 자동 업데이트용 **Velopack 릴리즈 바이너리** 전용 저장소입니다.

## 저장소 역할

| 저장소 | 가시성 | 용도 |
|---|---|---|
| [iriss-sw-team/AIXAC.RX.SW.SB](https://github.com/airiss-sw-team/AIXAC.RX.SW.SB) | 🔒 Private | 소스코드 (개발) |
| **`airiss-management/AIXAC.RX.SW.SB-releases`** (여기) | 🌐 Public | 릴리즈 바이너리 (배포) |

장비는 이 저장소의 **Releases** 페이지만 조회합니다. 인증 불필요(익명).

## 자동 업데이트

장비 측 앱은 [Velopack](https://velopack.io)을 사용해 본 저장소의 최신 릴리즈를 받습니다.

- 사용자가 앱 안에서 `시스템 설정 → 소프트웨어 업데이트` 탭의 ①②③ 버튼으로 수동 트리거
- 자동 푸시 없음 (보안 검색 장비 인증/변경관리 정책)

상세: 소스 저장소의 [`docs/auto-update/GUIDE-AUTO-UPDATE.md`](https://github.com/airiss-sw-team/AIXAC.RX.SW.SB/blob/master/docs/auto-update/GUIDE-AUTO-UPDATE.md)

## 채널

- **stable** — 정식 출시 (운영 장비 기본)
- **beta** — 사내 테스트용 (`-pre` 플래그)

## 라이선스

본 저장소의 모든 바이너리는 © AIRISS. All Rights Reserved.