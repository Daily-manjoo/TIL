# 자바스크립트로 HTML 조작하기

자바스크립트로 클래스가 hello인 텍스트 바꿔보기

`

<h1 id="hello">안녕하세요</h1>

<script>
  document.getElementById('hello').innerHTML = '안녕';
</script>

스타일로 폰트컬러와 사이즈를 바꿔보기

`

<script>
document.getElementById('hello').style.color = 'red'; 
document.getElementById('hello').style.fontSize = "30px";
</script>

`
