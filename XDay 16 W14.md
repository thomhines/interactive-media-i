ART 341 - Day 16 - W14
=======================================

1. Project 2 Final Crits


PREP
---------------------------------------



CLASS
---------------------------------------

### Project 2 Final Crits, Part 1

### Demo jQuery

Using [Alex's jQuery demo files](http://teaching.thomhines.com/resources/2_col_html_template_empty.zip) ([complete](http://teaching.thomhines.com/resources/2_col_html_template.zip))

- Link to jQuery
- Add scripts.js
- Add this to scripts.js

	$(function() {
	
		//Toggles a slide on any h2 tags inside the sidebar.
		$('.sidebar h2').click(function() {
			$(this).next().slideToggle();
			
		});
		
		//Toggles a slide on any h2 tags inside the sidebar.
		$('.bigbutton').click(function() {
			$('header h1').fadeToggle(2000);
			$('.main h1').fadeToggle(2000);
			$('.sidebar').fadeToggle(2000);
			$('.rg-gallery').fadeToggle(2000);
			
		});
		
		$('.paragraph').hover(function(){
			//hover in
			$(this).css("background", "yellow");
			//hover out
		}, function() {
			$(this).css("background", "none");
		});
		
		$('.image').hide();
		//$('ul').hide();
		
		$('.bigbutton2').click(function() {
			$('.image').fadeToggle(500);
			
		});
		
		$(".navbox").click(function() {
			$("nav li").animate({
			width: 'toggle',
			opacity: 'toggle',
			easing: 'easein'
			})
		});
		
		$('.checklist li').click(function() {
		
			$(this).addClass('finished');
		});
		
		$('.clear').click(function() {
			$('.finished').hide();
		});
		
		$('.reset').click(function() {
			$('.checklist li').show().removeClass("finished");
		});
	
	});



HW
---------------------------------------

1. **Project 2 Self-Evaluation**

	Please write 1-2 paragraphs on what you thought of the project, how you feel you did, what you learned, what you wish you did differently, etc. I'd like to know how this process was for you. 

2. **Site Launch Checklist**

	If you didn't give it to me in class, please bring it with you next class. I'm not going to grade your assignment if I don't have it! For any elements that you weren't able to check off, please write a small note as to why.


3. **Research Portfolio Sites**

	Find out what other creative-type people are doing in their portfolio sites. Collect as many good ideas as you can (at least three sites), and start taking notes. Post screenshots, notes, thoughts, and URLs to the blog so we can all see what you've found.
	

4. **Project 3 Content Inventory**

	In order to hit the ground running on Project 3, I want you to come prepared to start working on your portfolio on Tuesday (Project 3, fyi, is a portfolio site). You should have your images picked out and preliminary descriptions written about each piece you want to present. Look at other designers and see what they do. Look for inspiration in other sites. If you want to include a resume, bio, or contact page, start writing the copy for those pages now. 

	If you are doing something other than a portfolio site (and have discussed this with me), you still need to have the majority of your content and web pages picked out and brought to class, too. Let's not waste any time, folks!
	
	
5. **jQuery ExTrA CrEdiT!!!!**

	For any of you who are interested in learning more about jQuery or want to get a small bump in their grade, finish the first two [jQuery lessons](http://www.codecademy.com/tracks/jquery) (Introducing jQuery and jQuery Functions), and post a screen shot of your completed lessons to the blog. Like so:
	
	<img src="http://teaching.thomhines.com/resources/Codecademy%20Example.png">