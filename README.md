# HTML-NOTES-CAPACITI
INTRODUCTION TO HTML 

The Web consists of three programming languages: HTML, CSS, and JavaScript.
 HTML is responsible for marking up a website's content and providing access to built-in browser functionalities. It is a declarative language with a straightforward structure, making it resilient and robust. 
CSS on the other hand, is responsible for the attractiveness of a web page, including colours, fonts, and sizes. It can also add animations and interactions.
JavaScript is a programming language that allows for complex interfaces and can handle complex tasks. However, it is delicate and can be a bit fragile if the browser is outdated or does not understand the code.
The Web is unique in that it runs on various platforms and devices, allowing users to share content even on different computers. By combining these languages, developers can achieve resilience, robustness, and power in their websites. They try to utilize the more robust features of these languages as much as possible.

TEXT FORMATTING
HTML is a language used to structure web pages using tags enclosed in less-than and greater-than symbols. 
Tags types
1.	Br
2.	img
These tags, which come in two types: opening and closing, define elements like packages containing content.
 The purpose of HTML markup is to give meaning to content and help computers understand it.
An entire HTML document is essentially a bunch of HTML elements nested inside each other, creating a tree structure, like a family tree. This structure is called a DOM tree, which is important when working with CSS or JavaScript.
 The browser uses the DOM tree to create an accessibility tree, which impacts the user experience on your website, including people with various disabilities.
 It is important to pay attention to where we open and close our HTML tags and how we nest elements within each other to convey meaning about the content and interfaces.
Types of elements
•	Paragraphs
•	Article
•	Headliners
•	Lists
•	Etc


THE PARAGRAPH ELEMENT
 in HTML consists of three text chunks. To display them as paragraphs, add an opening and closing tag before the first paragraph and a closing tag at the end. The remaining paragraphs should be placed in their own tags, allowing the browser to recognize them as individual pieces of text.
Headlines
 Are essential elements in web pages, dividing content into smaller, more digestible chunks. They are found everywhere and act as clickable titles on landing pages. Headlines come in six types: h1, h2, h3, h4, h5, and h6. 
Each headline has a distinct visual effect and conveys a sense of hierarchy in how the browser interprets and communicates about the page. The choice of headline level is based on its meaning, not appearance. 
The New York Times uses three levels of headlines on their section landing page: h1 for the title, h2 for all article titles, and h3 for smaller headlines. 
This hierarchical system gives meaning to the browser and ensures all article headlines share the same type, which is crucial for screen reader users. It is advisable to follow the guidance of larger teams and consider how different levels of headlines will be utilized across the entire site.
HTML Bold and Italics
HTML has four elements: two for bold and two for italic. The use of bold and italic is crucial in various fields like book publishing, journalism, and magazine production. Italics are used to make a strong point, while italics are used to visually distinguish between words. The "" element is used to apply visual italics, while the "" element adds emphasis. These elements serve different purposes, communicating semantic and human meaning.
It allows for bold visuals without implying any alternative voice or mood. For example, a warning message might use the "" element to emphasize the word "warning" or highlight a specific part of a phrase as more significant than the rest.
In summary, HTML has two elements for bold and italic, each serving different purposes in different contexts. It is essential to use both elements effectively to ensure the correct use of text in various fields.

HTML lists 
are a common feature in daily life, including to-do lists, recipes, wish lists, and bucket lists. There are three types of lists in HTML: unordered lists, ordered lists, and definition lists. Unordered lists are the most commonly used type, with each item enclosed in an <li> element. To define the entire list and specify its type, they are wrapped in an <ul> element. Indentation is optional but is used for convenience.
Ordered lists are similar to unordered lists but with a specific order. They are wrapped in an <ol> element, indicating a specific order.
 Definition lists, on the other hand, are used to create a key-value pair in computer science, with terms and their corresponding descriptions. They are created using specific elements, with the term or key enclosed in a <tag> and the description or value enclosed in a <tag>. The entire list is wrapped in a <tag>, representing the definition list.
 
HTML quotes
 are a crucial aspect of webpage design, serving as a way to format text and provide custom styling. The " " element in HTML stands for quote, and it is used to automatically provide appropriate quote marks. 
Inline elements, such as block quotes, paragraphs, and unordered lists, create separate blocks on the page. These elements can be nested within each other in a way that makes sense. Block quotes and the "" element are used for inline phrases and block contexts, respectively.
 HTML attributes provide additional information to HTML elements, such as the datetime attribute, which allows users to specify the date or time in a format that computers can understand. Understanding the inherent nature of these elements is essential before implementing layout or CSS. In summary, HTML quotes are a crucial aspect of webpage design, allowing users to format text and create unique visual experiences.
The date time attribute in HTML is crucial for conveying time in a machine-readable format. It starts with the year, four digits, followed by the month and date in two digits. Machines prefer a highly standardized format, and can indicate times using the time element. The 24-hour clock format is preferred, and seconds and fractions of a second can be included. The time zone can also be specified. The datetime attribute can combine the date and time, with options for separating them using a T or leaving a space. These formatting rules apply to many programming languages.

HTML Date and Time Input
HTML simplifies the process of dealing with dates and times by using a single element called <time>. This element is used to mark anything that specifies a time of day, date, or duration. 
The <time> element consists of an opening tag (<time>) and a closing tag (</time>). The main purpose of the <time> element is to convey the exact date or time to computers using an HTML attribute called "datetime." 
The datetime attribute allows us to specify the date or time in a format that computers can understand. The format of the time within the datetime attribute must be specific, with a 24-hour clock format and the option to include seconds and fractions of a second. 
Additionally, we can specify the time zone, such as 15:45 -05:00, which means 3:45 PM in the time zone that's five hours behind Greenwich Mean Time (GMT). Combining the date and time using the datetime attribute is also possible.
HTML Code, pre and br
HTML code, pre and br elements are useful tools for showcasing code on a webpage. Code is typically treated as an inline element, meaning it remains part of the sentence it's in. To change the word "H4" into an actual H4 headline, an HTML entity called "<" is needed. This will display a less than sign and a greater than sign.
The br element is a simple tag without an opening or closing tag, indicating where a line break should occur. It does not contain anything inside it, but it indicates where a line break should happen.
The pre-element is used to make the spacing an integral part of the content's meaning. Wrapping the poem in pre tags ensures that the browser respects the spacing, line breaks, and other elements. Even a random character can be inserted and stays exactly where it is placed.
In summary, HTML code, pre and br elements are essential tools for showcasing code on a webpage.
Accessing or targeting mail/sites/docs/pdf
Examples:
  <a href="mailto:214015637@mycput.ac.za" target="_blank">Click here</a>


  <a href="http://google.com" target="_blank">Click here</a>


  <a href="INTRODUCTION TO HTML.docx" target="_blank">Click here</a>


Accessing media
WORKING WITH AUDIO
<audio controls>
    <source src="videoplayback.mp4">
  </audio>

WORKING WITH VIDEO
<video controls>
    <source src="videoplayback.mp4">
  </video>




	
