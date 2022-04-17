# 🔖 weniv-login


## 🖋 개요

- [프론트엔드 스쿨] HTML, CSS로 weniv 로그인 화면 구현 실습
- 피그마를 사용한 디자인 참고
<br>

## 💻 주요 기능

- ID, password에 required 속성 부여하여 입력하지 않을 시 form 제출 불가
- 자바스크립트 대신 로그인 상태 유지에 'input[type="checkbox"] 가상 요소 사용 및 클릭시 다른 이미지로 변경
- '또는' 좌우의 구분선을 가상요소로 설정. width 값을 지정하지 않고 flex-grow를 적용하여 유연한 사이즈 조정
- 앞으로 추가할 기능 : 필수 입력값인 ID, password 미입력시 input의 outline을 다른 색으로 변경한 뒤 입력 요청하는 문구 띄우기 + 유효성 확인
<br>

## 💬 프로젝트를 하며 느낀 점

- height, width 등 고정값을 주지 않고 유연한 css를 적용하는 것의 중요성과 유용함을 다시 한번 느끼게 되었다. (꼭 필요한 경우 제외)
- 익숙한 코드로 계속 작업하는 경향이 있다. position:absolute,relative를 float으로, flex를 grid로 바꾸는 등 새로 배운 속성을 적극적으로 활용할 예정이다.
<br>

## 🔎 실제 구현 화면
![image](https://user-images.githubusercontent.com/80025366/163715091-e244bf38-7789-4a89-9938-33e2dc7a9119.png)
