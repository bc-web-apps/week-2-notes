# Week 2: HTML + CSS

As we learned in the last week, the internet is all built on simple text! Even this website that you are reading right now is designed and rendered from simple lines of text. The language of this text is called `HTML` and it stands for **Hypertext Markup Language**. You can start to think of your web browser as a viewer that can "view" these files. Similar to how you use Microsoft Word to open and view Word documents, you use your web browser to view HTML files. We will discuss later on how CSS fits into this picture as well.

## The Basics of HTML

### Tags
Everything in HTML is built upon HTML tags. These tags are denoted with the carrot `<` `>` symbols. You can think of HTML as being compromised of sentences that represent different page elements that you see. For example, at the top of this page there is a search bar, this is simply an input feild that lets users type into.

Each tag comes in a pair, and has a starting and ending tag. They are usually denoted such that `<tagName>` begins like this, and ends with a backwards slash such as `</tagName>`. Everything between the two tags is the content, and the tags tell the browser what kind of content it will be.

**Note:** you must always have an opening and closing tag, otherwise your page will not load properly.

#### Tag Types
There hundreds of tag types! You can view a full [list here] (https://www.w3schools.com/tags/ref_byfunc.asp), but don't worry, you really only need to understand a few types to get things working. Here's the main ones:

| `<html>`        | Defines and HTML document                                    |
| :-------------- | :----------------------------------------------------------- |
| `<head>`        | Defines information about the document                       |
| `<title>`       | Defines a title for the document                             |
| `<body>`        | Defines the documents body                                   |
| `<h1>`...`<h6>` | Defines Headings of descending size                          |
| `<p>`           | Defines a paragraph                                          |
| `<br>`          | Inserts a single line break (Note: you do not need a closing tag here) |
| `<hr>`          | Inserts a line break (Note: you do not need a closing tag here) |
| `<!--`...`-->`  | Defines a comment (will not appear in the browser)           |
| `<div>`         | Defines a section in a document                              |
| `<span>`         | Defines a section in a document                              |
| `<input>`         | Used to accept user inputs on a page                              |
| `<img>`         | Inserts an img (Note: you do not need a closer tag here)                              |

### Basic HTML Document

Now that we know some of the basic tags, let's take a minute to look at a basic HTML document. Just like any Word document you'd right, there some required components of any `HTML` file. This is what a standard document looks like:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>Homepage Headline</h1>
        <p>This is a paragraph.</p>
    </body>
</html>
```

As you may notice, tags become nested within other tags. You can read this by looking at the indendation structure. There is a `<html>``</html>` tag pair that wraps the entire document, this tells the browser that everything between the two tags is an HTML document. You'll then see that the document has two main sections:

1. `<head>` - The head is at the top of the document and used to define page information and attributes. In this case we define the page title (this appears at the top of your browser), and we can define other attributes such as language and author as well.
2. `<body>` - The body is where the majority of the page content is hosted. This will have all of your text and features and images.

What does this HTML look like now? ![chromeExample](/Users/bdweix/Code/projects/web-app-notes/week-2-notes/note-sources/chromeExample.png)

We can see at the top of our browser the tab shows the "Page Title", which is specifed between the `<title>` tags in the document `<head>`. If you change this title, it will change in your browser! Next we will see that the page has the largest sized header value (`<h1>`) with the words "Homepage Headline". Finally you can see the body text being display. 

Rememeber last week when we learned about Inspecting elements in Chrome? We can do that now too. Simply right click (control-click on Mac) and hit "Inspect". You will now be able to interact directly with the web page HTML, you can even change values.

![chromeExample2](/Users/bdweix/Code/projects/web-app-notes/week-2-notes/note-sources/chromeExample2.png)

### Creating your own HTML Document

Before we dive into more details about HTML, try setting up your own HTML document with what you've learned so far. Open Atom and in hit `Command N` (Mac) to create a new file, or go to the toolbar and hit `File > New File`. In the pop up window, enter the name for your new file: `MyWebpage.html`

You now have a blank HTML document that you can write anything you want in! Try copy/pasting the template we provided above and changing around the values. Go ahead and start playing some of the additional tag types as well. Once you want to see it, simply save the document to your Desktop (or wherever you want). Then go to the document and click it to open - it'll autoamtically open in your browser! Congrats you just made your own website.

### Div's and Span's

### Tag Attributes

#### Example with Images

## Introduction to CSS

### General Style Properties

### Utilizing Class Names

### Linking Stylesheets

### Flexboxs

## Designing Complete Webpage

Example: https://www.w3schools.com/w3css/w3css_templates.asp









