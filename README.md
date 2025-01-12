# 구름 산스

모두가 개발자가 되는 비전으로, [구름](https://goorm.co/)의 정체성을 담은 새로운 전용 서체를 개발했습니다.

> **구름 산스**
> 디자인용 서체 구름산스는 3가지 타입으로 다양한 매체에 사용이 가능하고 안정적인 골격과 일정한 자폭으로 가독성을 높인 서체입니다. 다양한 두께로 가독성을 높이고 싶다면 구름 산스를 이용해 보세요.

> **구름 산스 코드**
> 코딩용 서체 구름 산스 코드는 한국어를 포함하여 개발자들이 언어의 장벽 없이 코딩에 집중할 수 있도록 도우며, 한글과 영문 자폭이 코드 내에서 일관된 간격이 적용되어 효과적인 시각적 구분을 제공합니다.

## 서체 저작권

> 구름 산스의 지적재산권은 구름이 소유하고 있으며, SIL Open Font License를 따릅니다.
>
> ‘구름 산스, 구름 산스 코드’는 모두에게 무료로 제공합니다.
>
> 글꼴의 단독 판매 또는 글꼴을 변경하여 상업적 목적을 취하는 것은 제한됩니다.
>
> 구름 산스는 사용, 수정, 재배포가 가능하며 모든 파생 작업은 본 라이센스를 따릅니다.
>
> 문의사항 : contact@goorm.io

## 사용 방법

```html
<link href="https://cdn.jsdelivr.net/npm/goorm-sans@1/index.css" rel="stylesheet" />

<style>
  body {
    font-family: 'Goorm Sans', sans-serif;
  }
  pre,
  code {
    font-family: 'Goorm Sans Code', monospace;
  }
</style>
```

<details>
  <summary>패키지 설치 방식</summary>

```shell
npm i goorm-sans
```

폰트 패밀리 지정

```css
body {
  font-family: 'Goorm Sans', sans-serif;
}
pre,
code {
  font-family: 'Goorm Sans Code', monospace;
}
```

CSS 파일 불러오기

```
node_modules/goorm-sans/index.css
```

[Vite](https://vite.dev/) 상에선 다음과 같이 불러올 수 있습니다.

```css
@import url('goorm-sans'); /* CSS */
```

```ts
import 'goorm-sans'; // JavaScript, TypeScript
```

</details>

## 파일 크기

<!-- tree -P "*.woff2" -h --du -->

```
[806K]  .
├── [262K]  goorm-sans-bold.woff2
├── [276K]  goorm-sans-medium.woff2
└── [268K]  goorm-sans-regular.woff2
```

```
└── [451K]  goorm-sans-code.woff2
```
