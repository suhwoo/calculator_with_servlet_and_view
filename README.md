# show_member_list_with_view
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

[정확한 설명은 여기에](https://github.com/suhwoo/BookReview/blob/main/Java_Web_WorkBook/Ch.5%20MVC%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90.md)
