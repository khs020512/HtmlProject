# HtmlProject
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <h1>수습 국원 모집</h1>

  <h2>방송에 관심 있는 새내기 여러분 환영합니다</h2>
  <p>교내 방송국에서 신입생을 대상으로 수습 국원을 모집합니다. 학부와 전공은 상관없습니다.<br>방송에 관심 있는 여러 학우의 지원 바랍니다.</p>
</head>

<body>
  
  <script src="script.js"></script>

  <ul>
    <li><b>모집 기간 : </b>3월 2일 ~ 3월 11일</li>
    <li><b>모집 분야 : </b>아나운서, PD, 엔지니어</li>
    <li><b>지원 방법 : </b>양식 작성 후 이메일 접수</li>
    <dd><em>지원서 방식은 교내 방송국 홈페이지 공지 게시판에 있습니다.</em></dd>
  </ul>
  <h3>혜택</h3>
  <ol type='a'>
    <li>수습기자 활동 중 소정의 활동비 지급</li>
    <li>정기자로 진급하면 장학금 지급</li>
  </ol>
  <img src="/tmp/guest-5gnsbp/Desktop/mic.jpg" alt="카메라">
  <script src="https://replit.com/public/js/replit-badge-v2.js" theme="dark" position="bottom-right"></script>
</body>

</html>


<!DOCTYPE html>
<html>

<head>
<h1>수습 국원 지원 양식</h1>
</head>

<body>
<table>
  <colgroup>
    <col style="background-color:#eee;">
    <col style="background-color:#eee;">
    <col style = "background-color:#eee;width:200px">
    <col style = "background-color:#eee;width:200px">
  </colgroup>
  <thead></thead>
  <tbody>
    <tr>
    <td rowspan="3">개인정보</td>
    <td>이름</td>
    <td>      </td>
  </tr>
  <tr>
    <td>학과/학번</td>
    <td>      </td>
  </tr>
  <tr>
    <td>연락처</td>
    <td>      </td>
  </tr>
  <tr>
    <td>지원 분야</td>
    <td colspan="2"></td>
  </tr>  
  </tbody>
  
</table>
</body>

</html>
\






<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8">
    <title>연습문제 2</title>
    <style>
			#container { 
				width:520px;
				border:1px solid black;
				padding:20px 40px;
				margin:0 auto;
			}
      fieldset { margin-bottom:15px; }
      legend { font-weight:bold; }
			ul {list-style-type: none;}
			li { line-height:30px;}
    </style>
  </head>
  <body>
		<div id="container">
			<h1>프런트엔드 개발자 지원서 </h1>
			<p>HTML, CSS, Javascript에 대한 기술적 이해와 경험이 있는 분을 찾습니다.</p>
			<hr>
			<form>
				개인 정보
        <ul>
          <lable for="r-name">이름</lable>
          <input type="text" id="r-name" placeholder="공백 없이 입력하세요" required>
          <br>
          <lable for="r-phone">연락처</lable>
          <input type="tel" id="r-phone" required>
        </ul>
        지원 분야
        <ul>
          <input type="radio" name="web_pub" id="web_pub" value="web_pub">
          <label for="web_pub">웹 퍼블리싱</label>
          <br>
          <input type="radio" name="web_api" id="web_api" value="web_api">
          <label for="web_api">웹 애플리케이션 개발</label>
          <br>
          <input type="radio" name="dev_atm" id="dev_atm" value="dev_atm">
          <label for="dev_atm">개발 환경 개선</label>
        </ul>
        지원동기
        <br>
        <br>
        <textarea cols="40" rows="4" placeholder="본사 지원 동기를 간략히 써 주세요."></textarea>
        <br>
        <input type="button" value="접수하기">
        <input type="button" value="다시쓰기">
			</form>
		</div>
  </body>
</html>
