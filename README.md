# 생활코딩 JavaScript for Web Browser 과정
## 과정을 따라가면서 나만의 기록을 남기는 Repositorie



## 기록을 남기는 방식(예제 class01)
```javascript

<html>
<head>
	<title></title>
</head>
<body>
	<input type="botton" onclick="alert('Hello World')" value="Hello World" /> 
	<!-- 여기 보면 onclick이라는게 있는데 이게 html의 속성이야
	// 이 속성은 사용자가 클릭했을 때 자바스크립트 코드가 실행되도록 하게 되었는게 onclick이야 그리고 이렇게 효과가 발동되는걸 이벤트라고 불러
	// onclick=" " 여기 까지는 Html의 문법이고 alert('Hello World')이게 자바 스크립트의 문법이야.
	// 그리고 이 문법 즉 이 하이브리드 같은 문법의 단점이자 장점이 바로 서로 다른 문법이 같이 있다는거야 
	// 사용하긴 편하지만 만약 이걸 따로따로 통제해야되는 상황이라면? 문제가 어려워지지.
	// HTML은 여러 정보를 담당하고, JAVASCRIPT는 제어를 담당하는데 정보안에 제어가 있으면? 문제가 다루기 어려워져 그래서 이 다음 것을 사용하게되.



	// 여기부터 중요해
  -->
	<input type="botton" id="DU" value="Hello World" />  
  <!-- // 왼쪽을 보면 이제 HTML 코드안에 더 이상 javascript코드가 존재하지 않는다. -->

	<script type="text/javascript"> // script 뒤에 내용들은 사실 없어도 작동은 한다. 그리고 여기까지! 가 HTML의 문법이고 이 이후 스크립트가 닫히기 직전까지는 javascript의 문법으로 되어 있다. 즉, 정보문과 제어문이 구분되어지게 된다.


		var DU = document.getElementById('DU');   // 이 뜻을 보면 document안에 id값이 DU인 elements(원소)를 가져와라.
		DU.addEventListener('click', function(){alert('Hello World');})
		// 가져온 것에 이벤트리스너(내가 하는 동작이 선행되어야 하는 후반응형 메소드가 리스너류들이다.) 기능을 추가하는데 이 이벤트는 클릭 시 'Hello World'를 출력하게 하는 것 이다.
		// 이렇게 정보와 제어를 구분하면 무엇이 좋은가? 유지보수 측면에서 굉장히 유리하다.
	</script>
<!-- 그리고 이렇게 스크립트 종단부는 무조건 바디의 종단부와 붙는게 좋다. 이유는 이렇게 해야 정보데이터와 제어 데이터를 명확히 분리시켜놓을 수 있기 때문이다. -->
</body>
</html>

```





## 해당 강의 유튜브 링크
[JavaScript](https://www.youtube.com/watch?v=ImTA5-r9TNc&list=PLuHgQVnccGMDTAQ0S_FYxXOi1ZJz4ikaX)





## 내 수강 내역
* JavaScript 기본 수업
  * JavaScript를 로드
    * inline 방식
    * script 태그 이용
    * 외부 파일 로드
    * onload
  * Browser Object Model
    * 전역객체 window
    * 사용자와 커뮤니케이션(1/3) : alert
    * 사용자와 커뮤니케이션(2/3) : confirm
    * 사용자와 커뮤니케이션(3/3) : prompt


* JavaScript를 이용한 실습





## 수강률 테이블
JavaScript학습기록|발전|믿음|완강률|
---|---|---|---|
2019.12.15|prompt까지 학습|나는 무조건 성공한다.|11.82%|





## 믿음 신뢰
> 할 수 없는 것은 없다 아직 시작하지 않았을 뿐. 

> 또한 완강은 끝이 아니라 작업의 시작이다. 

**초석을 다졌으면 건물을 올리자.**
