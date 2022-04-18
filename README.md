# dropdown-selectbox

## 어려웠던점

1.원래는 `<select>`과 `<option>`을 사용해서 구현하려 했지만 `<option>`의 default 값으로 인해 css 설정을 해주는게 어려워서 `<ul>`,`<li>`태그로 대체하여 진행하였다.

- 아래태그는 `<select>`태그의 기존 default값인 화살표 모양을 초기화해주는 css코드이다.

  ```css
  select {
    -o-appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
  }

  select::-ms-expand {
    display: none;
  }
  ```

2. 드롭다운버튼 클릭시 아이콘 이미지 변경기능을 구현하지 못했다.
