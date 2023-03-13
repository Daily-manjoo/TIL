# 동적 UI 만드는 스텝 (Alert 박스)

UI 만드는 스텝

1. HTML/CSS로 미리 디자인하기(필요하면 미리 숨김)
2. 필요할 떄 보여주는 자바스크립트 짜기

HTML

<div class="alert-box" id="alert"></div>
<button>버튼</button>

CSS

        .alert-box {
            background-color: skyblue;
            padding: 20px;
            color: white;
            border-radius: 5px;
            display: none;
        }

이렇게 하면 css스타일의 display: none으로 인해 버튼 밖에 보이지 않는다.

여기서 다시

HTML

        <div class="alert-box>" id="alert"></div>
        <button onclick="document.getElementById('alert').style.display='block';">버튼</button>

버튼에 onclick 속성을 부여해주면 버튼을 누를 때 display: none이 block으로 바뀌면서 css스타일이 보여진다.
