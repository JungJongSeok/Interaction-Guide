# 금융 앱의 인터랙션 가이드를 작성.

iOS 기준으로 작성되었으며, AOS 머터리얼 가이드에 따라 변동 가능성이 있음.

### 1. 페이지 이동

iOS/AOS 동일기본

좌(기준) → 우(이동) 

https://user-images.githubusercontent.com/12586065/119417911-d7699480-bd31-11eb-9215-e1b0f96c1369.mp4\

예외케이스

가장 하위 단위의 페이지에 들어갔을 경우 / 닫기 or 버튼 or 외부 링크를 띄울 경우

하 → 상

https://user-images.githubusercontent.com/12586065/119418008-0849c980-bd32-11eb-8391-4eb3add5cf53.mp4



---

### 2. 캐러셀 

좌, 우의 마진이 동일해야함 

~끝까지 당겼을 때 텐션을 제공해야함~ For iOS

발견의 배너 영역, 투자 태그형태 버튼 등 모두 동일한 인터랙션을 제공하는 것을 목표

https://user-images.githubusercontent.com/12586065/119418084-30392d00-bd32-11eb-9524-bfeb9b2ae8a1.MP4

https://user-images.githubusercontent.com/12586065/119418074-2adbe280-bd32-11eb-9662-0dbb2b9db6a5.MP4



---

### 3. 리스트

리스트 View 영역 selected 영역에 하이라이트 

영역 bg 전체에 연한 회색 그레이 컬러

https://user-images.githubusercontent.com/12586065/119418275-945bf100-bd32-11eb-91fb-4600270ba09b.MP4


---

### 4. 모달 팝업

black 영역이 fade 트랜지션으로 노출

동시에 하단에서 모달 bg 영역이 위로 올라옴

https://user-images.githubusercontent.com/12586065/119418356-ce2cf780-bd32-11eb-921d-ecbebfaf39bb.mp4

---

### 5. 배너 영역

* 배너 진입

발견의 배너, 이벤트 배너 터치 후 페이지 이동 시

이미지 영역이 넓어지면서, 텍스트는 좌상단 기준으로 특정 위치로 이동

https://user-images.githubusercontent.com/12586065/119418363-d127e800-bd32-11eb-93ac-8ab6834e14ac.MP4

* 배너 슬라이드 

배너의 끝까지 이동했을 경우 제일 첫 배너로 이동(Infinite Scroll)

인디케이터 영역은 특정 위치에 고정되어 있고 같이 이동하지 않음

만약 좌우 마진이 있는 Card UI 타입의 배너의 경우 → 배너 전체가 움직이는 것이 아닌, Card Frame 안에서 이동

https://user-images.githubusercontent.com/12586065/119418372-d38a4200-bd32-11eb-90ad-acaf5f16d193.MP4

