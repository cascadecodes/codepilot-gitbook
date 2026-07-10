# 필요한 스크린샷 목록

문서에서 참조하고 있지만 아직 `images/` 에 없는 파일입니다.
아래 **파일명 그대로** `images/` 에 넣으면 한글판과 영문판에 동시에 반영됩니다.

문서 안에서는 각 위치에 `{/* SCREENSHOT: ... */}` 주석으로 무엇을 찍어야 하는지 표시해 두었습니다.
파일을 넣은 뒤 해당 주석은 지워주세요.

---

총 **1장**이 남았습니다. (IDE 1 · Admin 0)

> CLI 탭은 나중에 작성하기로 하여 문서에서 제거했습니다. CLI 스크린샷 4장(`CLI_WELCOME` · `CLI_LOGIN` · `CLI_SLASH` · `CLI_HEADLESS`)은 그때 다시 목록에 추가하면 됩니다.

> 완료: 설치·로그인(`IDE_INSTALL` · `IDE_INSTALL_EXT_PANEL` · `IDE_FIRST_RUN` · `IDE_LOGIN` · `IDE_LOGIN_LOCAL` · `IDE_LOGIN_LICENSE`) · 채팅 모드 5장 · AI 모델 5장 · `IDE_ACCOUNT` · `IDE_ACCOUNT_ORG` · `IDE_HOOKS` · `IDE_AGENTS` · `ADMIN_LOGIN`
>
> 촬영 시 화면에 무엇이 함께 찍히는지 확인하세요. 이 저장소는 공개(public)이고, 나중에 이미지를 바꿔도 git 히스토리에는 남습니다.

---

## IDE — 남은 1장

| 파일명 | 무엇을 찍나 | 사용 위치 |
|--------|------------|----------|
| `IDE_INLINE_COMPLETION.png` | 에디터에서 회색 Ghost Text로 코드 제안이 뜬 상태 (Tab 수락 전) | 주요 기능 |

---

## IDE — AI 모델 연결 (완료)

AI 모델 연결 문서의 스크린샷 5장이 모두 반영됐습니다: `IDE_AI_MODEL.png`(주 흐름) · `IDE_MODEL_KEY_SOURCE.png`(관리자 키 전환) · `IDE_MODEL_ADD.png` · `IDE_MODEL_FORM_GEMINI.png` · `IDE_MODEL_TEST.png`.

> `IDE_MODEL_ADD.png` · `IDE_MODEL_TEST.png`는 Bedrock 모델 ARN에 AWS 계정 ID(12자리)가 찍혀 있어, 해당 ARN 줄을 검은 박스로 마스킹한 뒤 커밋했습니다. 원본을 다시 쓸 일이 있으면 계정 ID가 다시 노출되지 않게 주의하세요.

---

## Admin (완료)

Admin 콘솔 스크린샷 13장이 모두 반영됐습니다: `ADMIN_LOGIN` · `ADMIN_DASHBOARD` · `ADMIN_ONBOARDING` · `ADMIN_ORG_CREATE` · `ADMIN_ORG_JOIN` · `ADMIN_PENDING` · `ADMIN_PROFILE` · `ADMIN_API_KEY` · `ADMIN_TEAM` · `ADMIN_HOOKS` · `ADMIN_AGENTS` · `ADMIN_ACCESS_LOG` · `ADMIN_ERROR_LOG`.

> `ADMIN_DASHBOARD.png`는 최근 활동·프로필에 실명과 이메일이 찍혀 있어 해당 부분을 검은 박스로 마스킹한 뒤 커밋했습니다. 나머지 Admin 화면은 테스트 계정 기준으로 원본 그대로 반영했습니다.

---

## 촬영 시 참고

- **개발 환경 감추기**: 터미널·디버거·문제 패널을 닫고, 타사 확장이 사이드바에 보이지 않는 창에서 촬영하세요. 내부 빌드 경로나 바이너리 이름이 찍히면 안 됩니다.
- **개인정보 마스킹**: 실제 이메일, 실제 조직명, 실제 API 키가 보이지 않도록 데모 계정으로 촬영하세요.
- **API 키**: `cpk_` 뒤의 값은 반드시 가려주세요.
- **테마**: 기존 이미지가 다크 테마이므로 다크 테마로 통일하는 것을 권장합니다.
- **폭**: 기존 이미지와 비슷한 가로폭으로 촬영하면 문서에서 자연스럽게 보입니다.

---

## 더 이상 사용하지 않는 이미지

- `IDE_OPEN_SETTING.png` — 명령 팔레트. 설치 문서에서 해당 안내를 제거하면서 참조가 사라졌습니다. 보관하거나 삭제해도 됩니다.

그 외 기존 이미지 43장은 모두 그대로 재사용하고 있습니다.
