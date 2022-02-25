<div align="center">
  <h1>Front-End miniproject</h1><br>
  <img src="https://user-images.githubusercontent.com/12637306/155544844-df44dfb6-3ad6-4d58-a6a4-e53c2a4183b3.jpg" width=500px height=300px></img>
  <br>
</div>

## 📚 너의 책은. 📚

+ 🐱 팀원 : 김민준, 김병조, 반철준
+ 🐹 프로젝트 소개 : 네이버 검색 API를 활용한 도서 검색 사이트 구축
+ 💪 소요 기간 : 22/02/23 ~ 22/02/24
+ 🛠️ Tech
  + HTML
  + CSS
  + Javascript


## 🐭 실행 화면
<div align="center">
  <img src="https://user-images.githubusercontent.com/12637306/155554448-ba3f36fe-f39b-4341-8015-d90c146b0a66.PNG" width=800px height=400px></img><br>
  메인 화면
  <br><br>
  <img src="https://user-images.githubusercontent.com/12637306/155554999-0e6d90ec-2e7f-4f7f-b3dc-fcd7874ecff4.PNG" width=800px height=400px></img><br>
  검색어 입력 시 출력되는 화면, 총 10건이 검색됨.
</div>


## 🎨 LightHouse 측정
<div align="center">
  <img src="https://user-images.githubusercontent.com/12637306/155556350-1b4acb59-2715-4aed-a1b3-00cec8987bf6.PNG" width=550px height=300px></img>
</div>


## 🐯 Issue
+ html, nodejs, API 간의 통신 메카니즘 개념이 제대로 잡히지 않아 일어나는 이슈들이 많았음
+ 다른 책을 검색하고자 할 때 검색 데이터가 이전 데이터에 이어서 출력되는 이슈 : Search 이벤트 호출마다 결과 데이터 출력 영역을 ''로 초기화
+ 검색어로 한글을 넣었을 때 인식하지 못하는 이슈 : encodeURI 메소드를 이용하여 해결


## 🐻 개선해야 할 점
+ 데이터 갈무리를 좀 더 정갈하게 할 필요 있음
+ 검색 개수를 client가 조정할 수 있었더라면 !
+ aside 영역을 활용하여 날씨, 시계 등의 API를 추가
+ 아무 텍스트를 입력하지 않았을 때의 예외 처리



