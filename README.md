#### jQuery selectors
1. $('#header'); select the element with an ID of 'header'
2. $('li');      select all list items on the page
3. $('ul>li');   select list items that are direct child of ul
4. $('ul li');   select list items that are child of unordered lists
5. $('.person'); select all elements with a class of 'person'
6. $("img");  Get all img elements on the page
7. $(":first");  Get first element on the page
8. $("div:last")  Get the last div on the page
9. $("[href]")  Get all elements that have an attribute of href


#### changing HTML/CSS with jQuery
1. $("p").css("background-color");   //query style property
2. $("p").css("font-family");
3. $("li").css("color", "red");     //change text color of all li element to red
4. $("ul").css("background-color", "darkgrey");
5. $("ul").css("border", "1px solid #ccc")    //add a 1px wide border to ul element
5. $("li").css("color", "white");
6. $("li").css("font-size", "2em");
7. $("h2").css("text-decoration", "underline");
8. $("#my_footer").html(); to get the content of the element with "myfooter" ID
9. $("body").html();
10. $("#my_footer").html("<h1> This is my fancy new content, thx jQuery! </h1>");  to change the content of div.myfooter
11. $("#my_footer").text(" This is my fancy new content, thx jQuery again!!");  another way to replace the text
12. $("#myElement").append("<p>This is a new element</p>");   append new element to the element with myElement ID
13. $("#my_footer").append("<span>&copy; 2017. </span>");     append copyright sign to footer
14. $("a").remove();   remove all links from the page.  <strong>!!! do not put $("li").remove() </strong>
15. $("a").empty();   
16. We can also use the console to temporarily enable jQuery on pages that don’t already have it loaded. Run the following three commands in the console, to manually add jQuery to the page’s DOM: 
var script = document.createElement('script'); script.src = "code.jquery.com/jquery-latest.min.js"; document.head.appendChild(script); 
