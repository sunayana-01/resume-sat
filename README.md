# resume-sat

Step 1: Create HTML file with CodeSwing

Step 2: Creating a HTML Structure

```html
<html>
	<head>
		<link href="styles.css" rel="stylesheet">
		<title>Your Name resume</title>
	</head>

	<body>
        	<div class="container">
			<header id="header">
			    <!-- resume header with your name and title -->
			    <h1><b>YOUR</b>NAME</h1>
			    <hr>
			        YOUR TITLE (EX: SOFTWARE ENGINEERING STUDENT)
			    <hr>
		    	</header>
		    	<main>
			    <article id="mainLeft">
				<section>
					<h2>CONTACT</h2>
					<!-- contact info including social media -->
                    		</section>
				<section>
					<h2>SKILLS</h2>
					    <!-- your skills -->
                    		</section>
				<section>
					<h2>EDUCATION</h2>
					<!-- your education -->
                    		</section>            
			    </article>
			    <article id="mainRight">
				<section>
					<h2>ABOUT</h2>
					<!-- about you -->
                        	<section>
					<h2>WORK EXPERIENCE</h2>
					<!-- your work experience -->
                    		</section>
			    </article>
		    	</main>
        	</div>
	</body>
</html>
```
Step 3: Adding Content to HTML Page
Social Links
```html
<p>
    <i class="fa fa-envelope" aria-hidden="true"></i>
    <a href="mailto:your-email@example.com">your-email@example.com</a>
</p>
```

Work Experience
```html
<h3>JOB TITLE</h3>
<p>
		Company Name | 2008 - 2010
</p>
<ul>
		<li>Cool accomplishment</li>
		<li>Cool accomplishment</li>
		<li>Cool accomplishment</li>
</ul>
```

Your skills
```html
    <p>HTML, CSS, GitHub, VS Code...</p>
```

Your education
```html
<h3>YOUR MAJOR</h3>
	<p>
		Your university or school
	</p>
	<p>
		2018-2022
	</p>
```

About You
```html
<p>A brief paragraph about you and what kind of job/company you are looking to work for.</p>
```

Step 4: Adding CSS
body
```css
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 12px;
    max-width: 960px;
    margin: auto;
    backgound-color: black;
}
```
sizing
```css
h1 {
    font-size: 3em;
    letter-spacing: .6em;
    padding-top: 1em;
    padding-bottom: 1em;
}

h2 {
    font-size: 1.5em;
    padding-bottom: 1em;
}

h3 {
    font-size: 1em;
    padding-bottom: 1em;
}
```
creating grid
```css
    main { 
        display: grid;
        grid-template-columns: 40% 60%;
        margin-top: 3em;
    }
```
remaining style rules
```css
header {
    text-align: center;
    margin: auto 2em;
}

section {
    margin: auto 1em 4em 2em;
}

i {
    margin-right: .5em;
}

p {
    margin: .2em auto
}

hr {
    border: none;
    background-color: lightgray;
    height: 1px;
}

h1, h2, h3 {
    font-weight: 100;
    margin-bottom: 0;
}
```
selecting elements by id
```css
#mainLeft {
    border-right: 1px solid lightgray;
    background-color: rgb(28,28,35);
    color: white;
}
```

```css
.container{
	background-color: white;
	margin: 10% 10% 10% 10%
}
```

add icon format in title tag of html file
```html
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
```

Step 5: Host it on GitHub Pages
