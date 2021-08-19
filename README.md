# member_management
working with java_web_work_book_ ch5  
ch.5.4  
기존에는 servlet으로 DB접근, 동작, 결과화면 보이기를 했다면  
이제는 뷰를 이용해서 servlet에서는 DB접근과 동작만 하게 하고 결과값은 뷰가 구성해준다.  
해당 코드는 servlet이 DB에서 회원정보를 가져오고 값 객체에 전달하면 뷰(MemberList.jsp)에서 값객체를 가져와 결과화면을 jsp로 구성한다.  
  
ch.5.5  
인클루딩과 포워딩을 통해 일을 위임할수있다.  
Error은 포워딩을 통해 오류가 날 경우, 오류페이지로 이동한다.  
원래 페이지(List page)로는 돌아오지 않는다.  
Header과 Tail은 MemberList.jsp로부터 인클루딩으로 위임받는데, 실행후 MemberList.jsp로 돌아온다.  
  
ch.5.6  
데이터를 보관할때 4가지의 객체 보관소가 있다.  
1. ServletContext  
2. HttpSession
3. ServletRequest
4. JspContext

  
HttpSession을 이용해서 유저의 정보를 저장할 수 있다.  
LoginServlet과 LogOutServlet을 이용해서 로그인 기능을 만든다.  
LoginServlet을 통해 받은 정보를 Member객체에 저장하고 이걸 Header.jsp에서 가져다가 쓴다. 이후 로그아웃을 하면 LogOutServlet을 통해 /auth/login이 다시 호출된다.  
로그인은 이메일:sheet@naver.com 비밀번호:pmma  
  
ch.5.7~5.9  
JSP 액션태그 <jsp:useBean>, EL 블럭 ${}, JSTL을 통해 JSP에서 Java 코드를 지웠다.


[정확한 설명은 여기에](https://github.com/suhwoo/BookReview/blob/main/Java_Web_WorkBook/Ch.5%20MVC%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90.md)
