ART 341 - Day 12
=======================

1. Work Session


PREP
---------------------------------------
- Post jQuery demo files to blog
- Post design-to-HTML demo files to blog


CLASS
---------------------------------------


### Quiz

- What is jQuery?
- What does it do?
- How can we make all of the p tags disappear?
- How can we make only the p tag we clicked on disappear?
- The thing *after* that p tag?


### Design to HTML demo

- Download files from blog
- Set up Coda (w/ Publish ability?)
- Show completed version
- Walk through how to mark up design with more annotations

Make HTML 
	- Add divs for hover states and to combine content like with big banner image

- Make CSS
	- Float .sidebar
	- Float .thumbs
	- Abs. Pos. the label in the big image






### Forms
- How forms work 
	- POST, GET
	- Input 'name', 'value'
- Types of form elements 
	- text
	- password
	- textarea
	- checkbox
	- select
	- radio
	- file
	- submit
	- button



`<form action="result.html">`

	<label>What is your email address?<br>
		`<input type="email" placeholder="email@domain.com" autofocus required>`
	</label>
	<br>
	<br>
	
	<label>What kind of crappy food would you like?
		<select name="fastfood">
			<option>Burger</option>
			<option>Shake</option>
			<option>Fried Chicken</option>
		</select>
	</label>
	<br>
	<br>
	
	
	Would you like some fries with that shake?<br>
	<label><input type="radio" name="fries" value="yes">Yes</label><br>
	<label><input type="radio" name="fries" value="no">No</label>
	<br>
	<br>
	
	<input type="submit">
	</form>	


- New types of fields
	- email
	- tel
	- url
	- number
	- search
	- range
	- date
	- time

- What do these more specific types of commands do?
	- Good for bringing up proper keyboard
		[HTML5 Form Elements](http://blog.teamtreehouse.com/using-html5-input-types-to-enhance-the-mobile-browsing-experience)
	- Some browsers have built-in validation

- the form tag
	
	<form action="Untitled.php" method="post">

- Optional attributes
	placeholder, autofocus, multiple (files only), required

- Styling Forms
	[Guidelines for Good Web Form Design](http://www.smashingmagazine.com/2011/06/27/useful-ideas-and-guidelines-for-good-web-form-design/)

*At least one form is required in your Project 2 Site*




### Discuss designs

### Work session





HW
---------------------------------------


1. **Make HTML, Start CSS**

	Using your annotated comps and the site template from our blog's Resources page, create your HTML. You can use placeholder text, but put in real text wherever possible. By next week you'll want your HTML finished and a good chunk of your CSS done. We don't have class on Wednesday, so let's make our time count!


2. **Make a "home page" for your PSU web space**

	Create an index.html file to put in your public_html folder on the web server. It doesn't have to be styled--you can if you want--but make sure that all of the sites you've made until now are represented on this page and that each link works. Mine looks like this: [http://web.pdx.edu/~thines/](http://web.pdx.edu/~thines/) . It took me about 30 seconds to make that, and that's all you have to spend to make yours too.


3. **Do CSS Diner**

	Do all the exercises at [CSS Diner](http://flukeout.github.io/) and post a screenshot of the final page to the blog. Don't worry; it's fun!



#### Useful Links
- [HTML5 Form Elements](http://blog.teamtreehouse.com/using-html5-input-types-to-enhance-the-mobile-browsing-experience)
- [Guidelines for Good Web Form Design](http://www.smashingmagazine.com/2011/06/27/useful-ideas-and-guidelines-for-good-web-form-design/)