# 🌿 Branch Strategy

## 🏷 Main Branches

- `main`: 최종 배포 브랜치 
- `develop`: 기능 개발 통합 브랜치 (서비스 코드 중심)

## 🧪 Working Branches

### 🚀 feature/*
- 새로운 기능 개발 시 사용
- `from`: `develop` → `to`: `develop`
- 예: `feature/study`
- 예: `feature/auth-login`

### 🐞 fix/*
- 버그 수정 시 사용
- `from`: `develop` → `to`: `develop`
- 예: `fix/signup`
- 예: `feature/learning-record`

## 🔁 Merge Rule
- 모든 작업 브랜치는 **`develop` 브랜치로 병합**하는 것을 원칙으로 합니다.
- **Pull Request 필수**
- 최소 1명 이상 코드 리뷰 후 병합
- 코드 및 문서 리뷰 후 병합
- 머지 방식: **Squash and Merge**

## 🧾 Branch Naming Convention

- **소문자**와 **하이픈(`-`)** 사용
- 브랜치 유형 접두사로 시작:
  - `feature/`
  - `fix/`
- 형식: `<type>/<category>` 또는 `<type>/<category>-<description>`
  - 예: `feature/auth-google-login` (권장, 필수 아님)
  - 예: `fix/learning-grading-bug` (권장, 필수 아님)
  - 예: `feature/login` (간단한 형태도 가능)