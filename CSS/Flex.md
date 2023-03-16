# Flex란?

하나의 플렉스 아이템이 자신의 컨테이너가 차지하는 공간에 맞추기 위해 크기를 키우거나 줄이는 방법을 설정하는 속성

---

### `justify-content`: 가로선 상에서 정렬

- **`flex-start`**: 요소들을 컨테이너의 왼쪽으로 정렬합니다.
- **`flex-end`**: 요소들을 컨테이너의 오른쪽으로 정렬합니다.
- **`center`**: 요소들을 컨테이너의 가운데로 정렬합니다.
- **`space-between`**: 요소들 사이에 동일한 간격을 둡니다.
- **`space-around`**: 요소들 주위에 동일한 간격을 둡니다.


![https://samanthaming.gumlet.io/flexbox30/12-justify-content-row.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/12-justify-content-row.jpg.gz?format=auto)

![https://samanthaming.gumlet.io/flexbox30/13-justify-content-column.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/13-justify-content-column.jpg.gz?format=auto)

### `align-items` :  세로선 상에서 정렬

- **`flex-start`**: 여러 줄들을 컨테이너의 꼭대기에 정렬합니다.
- **`flex-end`**: 여러 줄들을 컨테이너의 바닥에 정렬합니다.
- **`center`**: 여러 줄들을 세로선 상의 가운데에 정렬합니다.
- **`space-between`**: 여러 줄들 사이에 동일한 간격을 둡니다.
- **`space-around`**: 여러 줄들 주위에 동일한 간격을 둡니다.
- **`stretch`**: 여러 줄들을 컨테이너에 맞도록 늘립니다.

![https://samanthaming.gumlet.io/flexbox30/17-align-items-column.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/17-align-items-column.jpg.gz?format=auto)

### `flex-direction`:

- **`row`**: 요소들을 텍스트의 방향과 동일하게 정렬합니다.
- **`row-reverse`**: 요소들을 텍스트의 반대 방향으로 정렬합니다.
- **`column`**: 요소들을 위에서 아래로 정렬합니다.
- **`column-reverse`**: 요소들을 아래에서 위로 정렬합니다.

![https://samanthaming.gumlet.io/flexbox30/9-flex-direction.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/9-flex-direction.jpg.gz?format=auto)

### `order`:  요소의 상대적 위치를 값으로 정의

![https://samanthaming.gumlet.io/flexbox30/20-order.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/20-order.jpg.gz?format=auto)

### `align-self`: `align-items`가 받는 속성을 개별 요소에 적용

### **`flex-wrap`:** flex 컨테이너로 지정된 flex 요소들의 줄바꿈 설정

- **`nowrap`**: 모든 요소들을 한 줄에 정렬합니다.
- **`wrap`**: 요소들을 여러 줄에 걸쳐 정렬합니다.
- **`wrap-reverse`**: 요소들을 여러 줄에 걸쳐 반대로 정렬합니다.

![https://samanthaming.gumlet.io/flexbox30/10-flex-wrap.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/10-flex-wrap.jpg.gz?format=auto)

### `flex-flow`: `flex-direction`과 `flex-wrap` 옵션을 다 같이 줄 수 있음.

### `align-content`: 세로선 상에서 아이템들의 간격을 정렬

- **`flex-start`**: 여러 줄들을 컨테이너의 꼭대기에 정렬합니다.
- **`flex-end`**: 여러 줄들을 컨테이너의 바닥에 정렬합니다.
- **`center`**: 여러 줄들을 세로선 상의 가운데에 정렬합니다.
- **`space-between`**: 여러 줄들 사이에 동일한 간격을 둡니다.
- **`space-around`**: 여러 줄들 주위에 동일한 간격을 둡니다.
- **`stretch`**: 여러 줄들을 컨테이너에 맞도록 늘립니다.

![https://samanthaming.gumlet.io/flexbox30/18-align-content.jpg.gz?format=auto](https://samanthaming.gumlet.io/flexbox30/18-align-content.jpg.gz?format=auto)

출처:

[https://dirask.com/posts/CSS-justify-content-in-flexbox-flex-direction-row-1enA8D](https://dirask.com/posts/CSS-justify-content-in-flexbox-flex-direction-row-1enA8D)

[https://www.samanthaming.com/](https://www.samanthaming.com/)