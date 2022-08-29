# 🍹ChoFLIX

이 저장소는 NETFLIX를 클론코딩하여 화면 UI구현 공부를 위해 개발되었음을 미리 밝힙니다.

![NETFLIX](https://user-images.githubusercontent.com/46777310/186431795-8f445bb9-7af6-4840-851c-b51e04c981b2.png)

### 🥞 새로운 사실

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

img 태그의 src속성 말고도

```html
<!-- srcset 속성이 있는데 한장 이상의 사진을 선언하는데 사용됨 -->
<img src="" alt="" srcset="" />
```

CSS의 > 선택자는

```css
/* 아래 두 코드는 서로 다르다 */

/* Parent 클래스 하위의 모든 Child 클래스를 선택 */
.Parent .Child

/* Parent 클래스 직속 하위의 Child 클래스만을 선택 */
.Parent > .Child;
```

<img src="https://user-images.githubusercontent.com/46777310/187224563-91e81385-a8c9-414e-8615-09726072510a.png">

간단한 UI를 구현해보며 넷플릭스 UI를 따라 구현해보았음
