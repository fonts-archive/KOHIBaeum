# KOHI 배움

[배포처 바로가기](https://csp.kohi.or.kr/user/bbs/BD_selectBbs.do?q_bbsCode=1070&q_bbscttSn=20211118135429370)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `KOHI Baeum`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'KOHI Baeum';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/KOHIBaeum.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/subsets/KOHIBaeum-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KOHIBaeum/subsets/KOHIBaeum-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "KOHI Baeum", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
한국보건복지인력개발원은 보건복지 분야 전문성 강화를 위해 관계 종사자의 ‘배움’을 책임지고 있습니다. 
종사자의 배움은 국민 삶의 질 향상을 위한 ‘나눔’의 실천으로 이어지길 바라는 마음을 담아 한국보건복지인력개발원 서체를 개발했습니다. 
“배움을 통해 나눔을 실천한다”는 의미를 담아 ‘KOHI배움체’와 ‘KOHI나눔체’를 배포합니다. 
 
보건복지 현장 종사자들은 물론 우리나라 국민 모두 무료로 사용 가능하니, 많은 활용 바랍니다. 
 
단, 폰트 파일의 상업적 거래와 파일의 임의변형은 불가합니다.
```
