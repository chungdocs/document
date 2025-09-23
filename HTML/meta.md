```html
<meta charset="utf-8">
```
문자집합 속성은 브라우저에 사용할 문자 인코딩을 지시
utf-8은 문자포인트를 많이 가지고 있어서 소스코드에 모든 종류의 기호와 이모지를 사용할 수 있음.


```html
<meta name="viewport" content="...">
```
브라우저가 스크린 사이즈(스마트폰, pc 등)에 맞춰 보여질 수 있도록 하는 태그<br>
`width=device-width` 브라우저에 장치 너비의 100% 뷰포트로 하도록 지시<br>
`user-scalable=0` 확대/축소 기능 비활성화<br>
`maximum-scale=1` 최소 및 최대 배율을 사용하여 이러한 값 사이의 확대/축소 기능을 고정할 수 있음

```html
<meta property="og:site_name" content="...">
```
seo와 관련된 open graph tags 

```html
<meta name="apple-mobile-web-app-title" content="...">
```
애플 기기에 웹사이트를 최적화하기 위한 태그,
아이폰 홈 스크린에 웹사이트를 고정하여 네이티브앱처럼 느끼게 함

```html
<meta name="theme-color" content="...">
```
브라우저의 ui 색(테마) 지정 태그

```html
<meta http-equiv="origin-trial" content="...">
```
...
