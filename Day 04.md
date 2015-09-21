ART 341 - Day 4
=======================================

1. Discuss HW - Make HTML/CSS from design comp
2. CSS Shorthand
3. Lecture on CSS Positioning
4. Discuss wireframes in groups


PREP
---------------------------------------
- Prepare an HTML file on the server for doing quiz.
- Post [multi-column template](http://teaching.thomhines.com/resources/2_col_html_template_empty.zip) and [completed version](http://teaching.thomhines.com/resources/2_col_html_template.zip)
- Load up links in browser
- Load up CSS Layout keynote file
- Post [CSS Layout Presentation](http://teaching.thomhines.com/resources/CSS%20Layout%20Presentation.pdf) to blog



CLASS
---------------------------------------

### Quiz

Use this [codepen](http://codepen.io/thomhines/pen/aqfvJ)

- How do we add CSS to our HTML?
- How would we change our paragraphs to helvetica?
	- How would we give them more leading?
	- How could we add more space between them?
- What if we only wanted to style the first paragraph?
	- How would we make it green?
	- How would we give it a border on top?
- How can we make the first H1 tag blue? (by adding a class OR styling `header h1`)


### Discuss HW
- Convert comp into HTML/CSS
	- Who had a working version? Show a couple students who got close to replication.
	- What problems did you guys run into? How did other students fix that?

- Go through process of how I might do it, with help from students.
	- Firebug to debug
	- Validation
		- W3C Validator
			- [HTML Validator](http://validator.w3.org/)
			- [CSS Validator](http://jigsaw.w3.org/css-validator/)
		- Coda
		







### [CSS Shortcuts](http://cssdog.com/css_shortcuts.html)

- background
	- background: #fff url(image.gif) no-repeat top left
	- background-color
	- background-image
	- background-position
	- background-repeat

- margin/padding
	- margin: 20px;
	- margin: 20px 10px;
	- margin: 20px 10px 40px;
	- margin: 20px 10px 40px 100px;
	- margin-top, margin-bottom, margin-left, margin-right

- border
	- border: 3px solid #333;
	- border-width
	- border-color
	- border-style (solid, dashed, dotted)






### Lecture on CSS Positioning

Have students download [multi-column template](http://teaching.thomhines.com/resources/2_col_html_template_empty.zip)

Open up CSS Layout Presentation

#### Demos:
- **Display**
	- Show how items that are set to display will always take up their own line, even if they are surrounded by inline elements.
	- Set nav li to display: inline
- **CSS Reset**
- **Containers**
	- Add container to body, set width to 700 and margin to auto.
	- Show how section.main and section.sidebar are sections too
- **Floats**
	- Make pull quote go to right side
	- Add width and float to .sidebar
	- then margin to .main 
	- Clearfix for advanced. students
- **Box-sizing: border-box**
	- Show how columns no longer fit when you add padding, border
	- Add box-sizing and adjust values again
	- Describe vendor prefixes
- **Positioning**
	- Make .badge position: absolute; top: −15px; right: −15px;
	- Add position: relative; to .main
	- Add position: relative to .container and remove it from .main





### BREAK




### Discuss Wireframes
- Break into small groups, talk about wireframes. 20 min.
- Go around to each group, have them talk about any similarities between designs.
- Have them mention any stand-out wire-frames and/or design decisions






#### Adv. Students
- Media Queries
- CSS Transitions
- LESS/SASS/Compass
- AJAX
- jQuery Touch/Mobile platform?





HW
---------------------------------------

Nice job keeping up today, class! That was (probably) the last three-hour presentation of the term. From now on, it will be much more about looking at your designs, working on specific skills/tools, and a lot of coding. You guys did a great job following along, you asked great questions, and NO TEARS! Like I've said before, it gets easier as we go along, so the worst is always behind us.

For the weekend, here are the things I want you to do:

1. **Duplicate Multi-Column Website**

	Use this [template](http://teaching.thomhines.com/resources/class-4-copy-comp-layout.pdf), and try to replicate it in HTML/CSS. The styles don't have to be exact, but just do your best to make the overall layout match the one you're attempting to copy. Then, upload the site files for your version to the web server. Lastly, post a link and a screenshot to WordPress. 
	

2. **Web Design Research**
	
	Find a site that exhibits what you think of as good web design, and write ten things you like about it. You can comment on aesthetics, usability, interesting navigation structures, typography… whatever. Post your synopsis along with a working link and as many screenshots as necessary to demonstrate your points.


3. **Design Comps**

	I want to see at least **three (3)** unique and distinct directions of design here, with as much detail as you can get. You should be looking at layout, color, type, etc. Start to consider which [web fonts](http://www.google.com/fonts/) would work well in your designs. These three directions can all come from the same set of wireframes, or from a couple if you want still want to explore your underlying design decisions. You aren't obligated to, but consider making your designs to fit a screen that is 1024px wide (and make your Photoshop file as tall as you need to fit all your content). These, as with all homework, should be posted to the blog. 