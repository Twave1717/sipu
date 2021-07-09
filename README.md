# sipu
<html>
	<head>
		<meta charset="utf-8">
		<title>수행평가 공지 페이지</title>
	</head>
	<body>
		
		<iframe name='action' width="0" height="0" frameborder="0" scrolling='yes'></iframe>
		
		<h1>대충 수행평가 공지 게시판</h1>
		<h2>수행1</h2>
		<p> 시프 앱인벤터 활용 ~~~만들기</p>
		<h2>수행2</h2>
		<p> 시프 앱인벤터 활용 ~~~만들기</p>
		<h2>수행3</h2>
		<p> 시프 앱인벤터 활용 ~~~만들기</p>
		<h2>수행4</h2>
		<p> 시프 앱인벤터 활용 ~~~만들기</p>
		<h2>수행5</h2>
		<p> 시프 앱인벤터 활용 ~~~만들기</p>
		
		
		

<form name="addForm" method="post" target="action" action="/notice/notice_add_act.jsp">
<table>
 <tr>
  <td>

   <table>
    <tr>
     <td>공지사항</td>
    </tr>
   </table>

   <table>
    <tr>
     <td>아이디</td>
     <td><input name="user_id" size="50" maxlength="50"></td>
    </tr>
    <tr>
     <td>제목</td>
     <td><input name="subject" size="50" maxlength="100"></td>
    </tr>
    <tr>
     <td>내용</td>
     <td><textarea name="contents" cols="50" rows="13"></textarea></td>
    </tr>
   </table>

   <table>
    <tr>
     <td><input type="image" src="이미지주소" border="0" alt="저장"></td>
     <td><a href="/notice/notice_list.jsp"><img src="이미지주소" border="0" alt="취소"></a></td>
    </tr>
   </table>

  </td>
 </tr>
</table>
</form>
	</body>
</html>
