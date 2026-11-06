# 티샷 공개 자산

**이 저장소는 공개(public)다.** 비밀값을 절대 넣지 않는다.

## 왜 공개인가

인스타그램은 **커버 이미지와 사진을 파일로 받지 않는다.** 「공개된 주소에 있는 이미지」만 가져간다. 그래서 이미지가 올라가 있을 공개 주소가 필요하고, 그 자리가 여기다.

영상·문구·발행 코드는 **`teeshot-publish`(비공개)** 에 있다. 여기에는 **올라갈 이미지만** 둔다.

## 주소 규칙

파일을 올리면 이 주소로 바로 열린다.

```
https://raw.githubusercontent.com/<계정>/teeshot-assets/main/<경로>
```

예 — `EP05/cover.jpg` 를 올렸다면

```
https://raw.githubusercontent.com/<계정>/teeshot-assets/main/EP05/cover.jpg
```

이 주소를 `teeshot-publish` 의 `manifest.json` 에 적는다.

## 넣는 것 / 안 넣는 것

**넣는다** — 릴스 커버, 카드뉴스 이미지, 그 외 인스타가 가져가야 하는 이미지

**안 넣는다** — 토큰·비밀번호·API 키(절대), 미공개 원본, 아직 공개하면 안 되는 편의 이미지

> **올리는 순간 누구나 볼 수 있다.** 게시 예정일 전에 올려두면 그 전에 새어나갈 수 있으니, **올리는 날 같이 올린다.**

## 규격

| | 조건 |
|---|---|
| 릴스 커버 | **JPEG** · 8MB 이하 · sRGB · 9:16 권장 |
| 카드뉴스 | JPEG · 1080×1350 |

출처: developers.facebook.com/documentation/instagram-platform

## 폴더

```
EP05/cover.jpg      EP.05 릴스 커버
```
