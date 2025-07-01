# ALX Intermediate Frontend

* This project focuses on building a solid foundation in semantic HTML while emphasiszing accessibility, SEO optimization, and the implmentation of ARIA roles for enhanced usability trough incremental tasks.

## Learning Objectives
- Master Sematic HTML:
Learn to structure web pages using semantic elements such as header, main, article, section, and footer for better content organization and accessibility.

- Optimize for SEO:
Understand how to improve the visibility of your webpage through appropriate usage of meta tags and proper document structure.

- Enhanced Accessibility: 
Implement ARIA roles and attributes to make web forms and content more accessible to users with disabilities.

- Understand Form Design Best Practices:
Learn to create accessible and user-friendly forms using modern HTML techniques.

- Adopt Incremental Development:
Practice progressive enhancement by building upon the foundation of each previous task.

### Task 0:
__Objective__: Practice tructuring a simple HTML document using semantic elements.

* Create your first file 0-index.html with:
	* inside the html tag, create the head and body tags(empty in this order):
	* Inside the body tag:
	* Add a header that contains a nav with at least three links.
	* Create a main section that the contains the an article, and inside the article, add an h1 tag for the title and a section for the content.
	* Add a footer with some copyright information
**NB**: Remember to structure the HTML file in a doctype.


#### Task 1:
__Objective__: To enhance the structure of the HTML docuent by adding meta tags for improved SEO, accessibility, and responsiveness, while properly defining the document's character set and title.

**NB**: Copy the contett f 0-index.html into 1-index.html. Inside the '''html <head>''' tag:
* Add a meta tag inside the head*
* Add th charset attribute with the value utf-8
* Add 4 more meta tags with the following
	* Tag 1: name=description content=A blig pist about semantic HTML and accessibility practises
	* Tag 2: name=keywords content=HTML, Semantic, Accessibility, Blog, SEO
	* Tag 3: name=author content=
	* Tag 4: name = viewport content=width: device-width, initial-scale=1.0

*Add a title with the message: "Semantic HTML Blog Post"

### Task 2:
__Objective__: Apply Semantic elements to create a blog post layout.

**NB**: Copy the content file 1-index.html into 2-index.html
* Inside the header tag
	* Add an h1 tag with the content "My Blog"
	* Add a nav tag
* Inside the nav tag, create a "ul" tag with 3 "li" tags referencing the following respectively
	* Home
	* About 
	* Contact
* Inside the article tag in the main tag:
	* Add a header tag with the "h2" tag text, "Understanding Semantic HTML"
	* Add a "p" tag with the text: Published on '''html <time datetime="2024-09-10"> September 10.
* Inside the section tag, add a:
	* "H3" tag with the text, "Introduction"
	* "p" tag with the text, "Semantic HTML helps improve the accessibility of and SEO of your website. In this post, we'll explore its benefits and how to implement it." Ensure You close the tags.
* Below the previous section tag, add another section tag
* In the newly created section tag, add:
	* "h3" tag with the text, "Main Content"
	* A "p" tag with the text
		'''html
			### Using elements like
			<code>&lt;article&gt;<code>
			<code>&lt;section&gt;<code>
			<code>&lt;header&gt;<code>
		'''
		* ensures that both users and search engines can better understand the structure and content of a webpage.`
	* A "figure" tag with:
		* an "img" tag with a src="", and an "alt" attribute with the text, "example"
	* A figcaption with the txt, "By adopting semantic HTML, you enhance your site's accessibility, improve SEO, and make the content easier to navigate."
	* Add a "footer" tag, and inside the footer tag, add:
		* A "p" tag with the text, "written by <name>"
		* Another "p" tag with the text, "Published on 2024-09-11"
**NB** Remember to close each tag created and note that all the changes have been made in the article tag insde the main tag.

### Task 3:
__Objective__: Implement ARIA roles to improve accessibility in a form

* Copy the content of 2-index.html into 3-index.html
* Inside the main element, add a new section tag
* In the section tag add:
	* A "form" tag with the following attributes:
		* action=”#”
		* method=”POST”
		* aria-labelledby=”form-title”
		* role=”form”
	* Add a div tag. Inside the div tag, add a/an:
		* label tag with a for attribute:name
		* input tag with the following attributes:
			* type:- “text”
			* id : “name”
			* name: “name”
			* aria-required: “true”
	* Add another div tag inside the form tag, inside it, add a/an:
		* label tag with a "or" attribute:name
		* input tag with the same attributes as the previous. Just replace “name” text with “email”
	* Add another div, and insde it, add a/an:
		* "button" tag with the following attributes:
			* type = submit
			* aria-label: Submit the Form
	* Add another div tag with the following attributes:
		* aria-live: polite
		* role: alert
**NB**: Remember to close tags.