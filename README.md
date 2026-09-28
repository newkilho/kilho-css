# kilho-css

kilho.net 에서 사용하는 CSS 입니다.
daisyUI 5 + Tailwind CSS 4 로 빌드한 결과물 한 파일과, 그 파일이 쓰는 서체만 들어 있습니다.

```
css/app.css    빌드 결과 (색 테마 · 국기 아이콘 · daisyUI · Tailwind 유틸리티)
fonts/         Open Sans · Shadows Into Light (woff2, unicode-range 조각)
               title-*.woff2 — 첫 화면 제목 글자만 남긴 Geist · Pretendard (서체 이름 Kilho Title *)
```

`css/app.css` 안의 서체 주소는 `../fonts/…` 상대경로라 폴더 구조를 그대로 두고 씁니다.

## 사용

`css/app.css` 하나를 `<link rel="stylesheet">` 로 부릅니다. `fonts/` 는 같은 위치 기준으로 함께 둡니다.

테마는 `<html data-theme="kilho">`(밝게) / `<html data-theme="kilho-dark">`(어둡게) 로 고릅니다.

한글은 방문자 시스템 서체(윈도 맑은 고딕 · 맥 애플 SD 고딕 네오)를 씁니다.

## 이 저장소는 빌드 결과만 둡니다

소스와 빌드는 사이트 서버에서 합니다. 이 저장소의 파일을 직접 고치지 마세요 — 다음 배포 때 덮어써집니다.

## 포함된 서드파티

| 이름 | 라이선스 |
|---|---|
| [Tailwind CSS](https://tailwindcss.com) | MIT |
| [daisyUI](https://daisyui.com) | MIT |
| [Open Sans](https://fonts.google.com/specimen/Open+Sans) | SIL Open Font License 1.1 — `fonts/OFL-OpenSans.txt` |
| [Shadows Into Light](https://fonts.google.com/specimen/Shadows+Into+Light) | SIL Open Font License 1.1 — `fonts/OFL-ShadowsIntoLight.txt` |
| [Geist](https://github.com/vercel/geist-font) (`fonts/title-latin.woff2`, 글자 일부만) | SIL Open Font License 1.1 — `fonts/OFL-Geist.txt` |
| [Pretendard](https://github.com/orioncactus/pretendard) (`fonts/title-ko.woff2` · `title-ja.woff2`, 글자 일부만) | SIL Open Font License 1.1 — `fonts/OFL-Pretendard.txt`. 예약 이름 조항에 따라 고친 판의 서체 이름은 Kilho Title KO · JA |
| [flag-icons](https://github.com/lipis/flag-icons) (국기 15개, data URI) | MIT |

MIT 라이선스 코드의 저작권 표시는 `THIRD-PARTY-NOTICES.md` 에 있습니다.

## 라이선스

`css/app.css` 는 [MIT](LICENSE) (Copyright (c) 2026 Kilho Oh) 입니다. 안에 든 서드파티 코드는 위 표의 각 라이선스를 따릅니다.
`fonts/` 의 서체는 MIT 가 아니라 각 서체의 라이선스(SIL Open Font License 1.1, `fonts/OFL-*.txt`)를 따릅니다.
