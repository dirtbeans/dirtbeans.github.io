Women, Wine, & Web Design
=========

# ADDITIONAL RESOURCES NOT FROM THE PRESENTATION:
- Check out this very good course/online textbook for absolute beginners: https://internetingishard.com/html-and-css/
- For simple, content-driven pages (like a blog, about me, or an event page), I recommend looking at Jekyll and/or Github Pages. You can use one of their templates, or create your own by following along with tutorials and YouTube videos. Here's one to get you started: https://guides.github.com/features/pages/


# PRESENTATION CONTENT:
# MAKE SURE YOU HAVE..

1. Wifi (Network: *r1Public*, Password: *StartupCBUS17*) 
2. Installed and opened **Google Chrome**
3. A picture or two, for funsies
4. Opened the Glitch remix link to create a copy of the project:
*https://glitch.com/edit/#!/remix/amenable-editorial* 

---

# BEFORE WE GET STARTED..

1. Please ask questions when you have them!
2. Don't worry if things don't click at first.
3. Work together if you'd like- pairing is great!
4. Seriously, don't struggle in silence! Someone likely has the same problem too.

---

![](https://images.unsplash.com/photo-1522542550221-31fd19575a2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80)

## UNPACKING WEB PAGES

---

| CONTENT + | HTML + | CSS | 
| :---: | :---: | :---: |
| :memo: | :office: | :ribbon: |
| *stuff* | *structure* | *style* |

---

## HTML (STRUCTURE)
### HTML = *Hypertext Markup Language*
### A web page is composed of *elements*
### Elements are designated by *tags*
```html
<p>This is a paragraph element.</p>
<a href="https://www.google.com/">This is a link.</a>
<div>This is a div.</div>
<img src="./images/something-nice.jpg"> <!-- < That is an image. -->
<!-- And this is a comment! -->
```

---

## *Container elements* include an opening and a closing tag:
```html
<article>
    <p>The paragraph element is contained in the article element..
    and this text is the content of the paragraph element.</p>
</article>
```
## *Void elements* are self-closing:
```html
<img src="./images/happy_puppy.jpg">
<br>
```

---

## *Semantic elements* clearly define their **content**:
```html
<section>
    <article>
        <h1>This heading is a heading :)</h1>
        <p>The section defines a section of the document.</p>
        <p>The article specifies independent, self-contained content.</p>
        <p>The paragraph defines a paragraph.</p>
    </article>
</section>
```

---
![left fit](https://internetingishard.com/html-and-css/semantic-html/html-sectioning-elements-00c3fd.png)
## A FEW TYPES OF *SEMANTIC ELEMENTS*
- `<header>...</header>`
- `<nav>...</nav>`
- `<aside>...</aside>`
- `<section>...</section>`
- `<article>...</article>`
- `<figure>...</figure>`
- `<footer>...</footer>`

---

## Element Attributes (*class*, *id*, etc.) provide **information** about the HTML element
```html
    <article class="content-box" id="experience">
        <h1 class="text-fancy">Five Jobs I've Had</h1>
		<ul class="text-dark">
			<li>Theatrical costume design</li>
			<li>Writing obituaries</li>
			<li>Changing diapers</li>
			<li>Listing snails on eBay</li>
			<li>Drinking wine & demystifying HTML</li>
		</ul>
    </article>
```

---

## ...Then we use that **information** to *style* our content!
```css
#experience {
    background-color: #000000;
}
article.content-box {
    background-color: #FFFFFF;
}
.text-fancy {
    Font-family: 'Cursive';
}
ul.text-dark li {
    Color: #000000;
}
```

---

## CSS (STYLE)
## CSS = *Cascading Style Sheet*
## CSS is used to apply styles to HTML elements.
## Styles affect *position*, *size*, *color*, *depth*, *animate*...
**...way more than we could hope to cover tonight!**

---

```css
.experience {
    background-color: #000000;
}
```
*.experience* is the selector: what element gets styled?
*{ ... }* holds the declaration: what combo of styles should we apply? 
*background-color* is a property: what are we modifying?
*#000000* is the value: how would we like to modify the property?

---

![original](https://images.unsplash.com/photo-1508970057347-0524a45ebdff?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=900&q=60)
## Enough talk.
## Let's do some *__magic__*!!