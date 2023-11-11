## Introduction 💡

간단하게 메모를 입력할 수 있는 todo list 스타일의 웹앱입니다

기본적으로는 to do, doing, done을 제공하며,

localStorage에 저장된 데이터가 있을 때에는 그에 맞는 form을 제공합니다

<br>

  📌 Point

* reate-hook-form 사용한 이유
실제 앱을 빌드 한다고 가정했을 때 form은 단 하나의 input만 필요하지는 않다.
그렇다면 form에 많은 state들을 등록하게 되고 큰 규모의 앱을 만든다면 form validation이 필요하다.
일반적으로 또 다른 input이 있다면 또 다른 onChange를 만들어야 한다
ex) 회원가입을 위한 form이 있다고 생각했을 때 이름, 성, 아이디, 이메일, 전화번호, 비밀번호, 비밀번호 확인
... 아이디와 아이디 에러, 이메일과 이메일 에러... 모두 state로 가져야 한다.
  이걸 더 나아지게 할 수 있는 라이브러리
* recoil selector를 이용하면
  어떤 state를 가져다가 다른 state를 만들 수 있다.
  state를 원하는 대로 변형 가능
  selector는 atom의 output을 변형시키는 도구
* https://blog.naver.com/skatksdml1/223242059648

<br>

## Skills & tools 🛠

✔ typescript

✔ React.js v17

✔ recoil

✔ styled-components

✔ react-beautiful-dnd

✔ react-icons

✔ react-hook-form

✔ localStorage

<br>
<br>
