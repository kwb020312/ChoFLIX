# 🍹ChoFLIX

이 저장소는 NETFLIX를 클론코딩하여 화면 UI구현 공부를 위해 개발되었음을 미리 밝힙니다.

![NETFLIX](https://user-images.githubusercontent.com/46777310/186431795-8f445bb9-7af6-4840-851c-b51e04c981b2.png)

### 🥞비디오 삽입

비디오 삽입에 앞서 autoplay 속성을 위해선 muted 속성을 같이 주어야 함

**악용 방지** 를 위한 대책 인 것 같다.

```html
<video
  src="./WooYoungWoo.mp4"
  poster="./WooYoungWooPoster.jpg"
  autoplay
  muted
></video>
```

<img src="https://user-images.githubusercontent.com/46777310/187224563-91e81385-a8c9-414e-8615-09726072510a.png">

간단한 UI를 구현해보며 넷플릭스 UI를 따라 구현해보았음
