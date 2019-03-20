#### jQuery selectors
1. $( '#header' ); select the element with an ID of 'header'
2. $( 'li' );      select all list items on the page
3. $( 'ul li' );   select list items that are in unordered lists
4. $( '.person' ); select all elements with a class of 'person'
5. $("img");  Get all img elements on the page
6. $(":first");  Get first element on the page
7. $("div:last")  Get the last div on the page
8. $("[href]")  Get all elements that have an attribute of href


#### changing HTML/CSS with jQuery
1. $("p").css("background-color");
2. $("p").css("font-family");
3. $("li").css("color", "red");
4. $("ul").css("background-color", "darkgrey");
5. $("li").css("color", "white");
6. $("li").css("font-size", "2em");
7. $("h2").css("text-decoration", "underline");
8. $("#my_footer").html();
   <p id="copyright">Copyright Infomation</p>
9. $("body").html();
10. $("#my_footer").html("<h4> This is my fancy new content, thx jQuery! </h4>");
11. $("#my_footer").text(" This is my fancy new content, thx jQuery again!!");  to replace the text
12. $("#myElement").append("<p>This is a new element</p>"); //append new element <p> to the element with myElement ID
13. $("#my_footer").append("<span>&copy; 2017. </span>");  //append copyright sign to footer
14. 

