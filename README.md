<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>정부대전청사공무원노조연합회</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            background: url('배경.png') no-repeat center center/cover;
            width: 100%;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: "Noto Sans KR", sans-serif;
        }

        .box {
            width: 420px;
            padding: 40px 30px;
            border-radius: 20px;
            background: rgba(0, 0, 0, 0.5);
            text-align: center;
            backdrop-filter: blur(4px);
            color: white;
        }

        .title {
            font-size: 20px;
            font-weight: 600;
            margin-bottom: 15px;
        }

        .sub {
            font-size: 15px;
            margin-bottom: 25px;
            opacity: 0.9;
        }

        input {
            width: 85%;
            padding: 12px 14px;
            border-radius: 10px;
            border: none;
            font-size: 16px;
            outline: none;
        }

        button {
            margin-top: 20px;
            width: 90%;
            padding: 12px 0;
            border: none;
            border-radius: 10px;
            background: #ff4f4f;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #e04444;
        }

    </style>
</head>

<body>

    <div class="box">
        <div class="title">정부대전청사공무원노조연합회</div>
        <div class="sub">비밀번호를 입력하시오.</div>

        <input type="password" id="pw" placeholder="비밀번호 입력">

        <button onclick="checkPW()">확인</button>
    </div>

    <script>
        function checkPW() {
            const pw = document.getElementById('pw').value;
            if (pw === "1234") {
                window.location.href = "https://naver.me/xcnavVEs";
            } else {
                alert("비밀번호가 틀렸습니다.");
            }
        }
    </script>

</body>
</html>
