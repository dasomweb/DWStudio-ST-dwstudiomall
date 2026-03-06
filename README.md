# dasomweb/DWStudio-ST-dwstudiomall

DW Studio Shopify Theme — **디자인 전용** 레포 (dwstudiomall).

- 이 레포에는 **디자인 오버레이**만 포함합니다 (templates, assets, config 등).
- 배포 시 **Core** 레포와 merge 후 Shopify에 push됩니다.
- 디자인 수정은 이 레포에서 진행하세요.

## 구조

- `templates/` — 페이지별 섹션 구성 (JSON)
- `assets/` — 프로젝트 전용 CSS/JS (선택)
- `config/` — settings_data.json 오버레이 (선택)
- `sections/`, `snippets/`, `locales/`, `layout/` — 필요한 경우만 추가

## Core 레포 연동

Core 레포 **Settings → Variables** 에서 `DESIGN_REPO` = `dasomweb/DWStudio-ST-dwstudiomall` 로 설정 후,  
해당 워크플로우에서 이 레포를 체크아웃해 merge 후 theme push 합니다.
