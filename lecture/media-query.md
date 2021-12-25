# 화면 해상도(조건)에 따른 구현

```css
// 500px안에 있을 때 이 조건을 따라라
@media (max-width: 500px) {
}
```

```css
@media (min-width: 500px) and (max-width: 1000px) {
  background-color: red;
}
```

@media 쿼리 뒤에 아무것도 없지만 사실
@media all and (min-width: 500px) and (max-width: 1000px)
와 같은 내용이 들어 있는 것이다.

@media not 을 붙이면 뒤에 있는 조건을 모두 뒤집어서 출력하게 된다.

# 디자인을 할 때 한가지 기준으로 하고 나머지를 나중에 미디어 쿼리로 처리해 준다

모바일로 시작해서 -> 브라우저로
브라우저에서 시작해서 -> 모바일로
