<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>오픈소스</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #333;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
            margin: 5px;
        }

        .button:hover {
            background-color: #0056b3;
        }

        .hidden {
            display: none; /* 숨김 클래스 */
        }
    </style>
</head>
<body>
    <h1>오픈소스열람e</h1>
    <input type="text" id="searchInput" placeholder="데이터 이름을 입력하세요">
    <button onclick="filterButtons()">검색</button>
    <button onclick="resetButtons()">back</button> <!-- back 버튼 추가 -->

    <div id="buttonContainer">
    <a href="https://github.com/tdotcorperation/opensource" class="button">Github으로 코드 보러가기</a>
        <a href="https://sharehtml.neocities.org/opensources/qrbq" class="button">큐알메이커</a>
        <a href="https://sharehtml.neocities.org/opensources/info" class="button">인포</a>
        <a href="https://sharehtml.neocities.org/opensources/T.PASs/tdpass" class="button">휴대전화정보인증</a>
<a href="https://sharehtml.neocities.org/opensources/number random ppopkki/v.1 basecode/nrpp" class="button">숫자랜덤뽑기</a>
<a href="https://sharehtml.neocities.org/opensources/number random ppopkki/v.1 basecode/the new nrpp" class="button">더 뉴 숫자랜덤뽑기</a>
<a href="https://sharehtml.neocities.org/opensources/datacenter/mypage/v.1 basecode/mypage" class="button">마이 페이지</a>
<a href="https://sharehtml.neocities.org/opensources/acs file/v.1/sirusecureacs" class="button">로그인엑세스시스템</a>
<a href="https://sharehtml.neocities.org/opensources/acs file/v.2 basecode/acs v2" class="button">로그인엑세스시스템버전2</a>
<a href="https://sharehtml.neocities.org/opensources/acs file/v.2 basecode/acs v2.4" class="button">로그인엑세스시스템버전2점4</a><!-- 추가 버튼 예시 -->
    </div>

    <script>
        function filterButtons() {
            const input = document.getElementById('searchInput').value.toLowerCase();
            const buttons = document.querySelectorAll('#buttonContainer .button');

            buttons.forEach(button => {
                const buttonText = button.textContent.toLowerCase();
                if (buttonText.includes(input)) {
                    button.classList.remove('hidden');
                } else {
                    button.classList.add('hidden');
                }
            });
        }

        function resetButtons() {
            const buttons = document.querySelectorAll('#buttonContainer .button');
            buttons.forEach(button => {
                button.classList.remove('hidden'); // 모든 버튼을 다시 표시
            });
            document.getElementById('searchInput').value = ''; // 입력란 초기화
        }
    </script>
</body>
</html>


































# opensource User Guide

This GitHub repository is intended for sharing HTML source code with others.
When using the source code here, please indicate the source and GitHub address.

**Please note!**
If you use open source, if there is an error in the code, it can cause big problems, so please **delete the code and report it to the wiki or the email address listed below the article.**

My address🔽

**td@ulskr**
