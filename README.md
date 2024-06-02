Headings
You can use the # symbol to create headings. One # creates an H1 heading, two create an H2 heading, and so on, like this:

# A first-level heading
## A second-level heading
### A third-level heading
#### A four-level heading
##### A five-level heading
###### A six-level heading
Create Headings in markdown
Paragraphs
To create paragraphs, you can use a blank line to separate one or more lines of text or paragraphs.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam est odio, commodo id diam sed, pulvinar sagittis tortor. Nam vestibulum purus eros. Sed congue, mi id pretium auctor, nibh augue iaculis arcu, eu tristique quam dolor at erat.

Quisque vel odio condimentum, mollis sem vitae, porta diam. Praesent ligula elit, condimentum eget ex sed, commodo sollicitudin sapien.


Proin volutpat faucibus nulla. Nullam eros sem, ultricies gravida nunc nec, dapibus posuere nisl. Nunc lacinia elementum turpis in pharetra. Aenean eu neque eros.
Create a Paragraph in markdown.
Comments
Comments are available in almost every programming language. They help developers write notes and add additional information to their code, helping other developers understand what's going on and how the code is working.

To add notes and additional information in Markdown, use the following syntax: <!--- Wrap text --->.

Here's an example:

<!-- This content will not appear in the rendered Markdown -->
Create a comment in the markdown
Styling text
You can apply basic styles to your text, such as bold, italic, strikethrough, subscript, or superscript, to improve readability and convey your point more clearly.

For Bold, you can use the following syntax:  **your text**
For italics, you can use the following syntax:  *your text* or _your text_.
For strikethrough, you can use the following syntax: ~~your text~~
For subscript, you can use the following syntax: The subscript <sub> text </sub> is here.
For superscript, you can use the following syntax:  The superscript <sup> text </sup> is here.
## Bold

**your text**

## italics

*your text*
_your text_

## strikethrough

~~your text~~

## subscript

The subscript <sub> text </sub> is here.

## superscript

The subscript <sup> text </sup> is here.
Quotes
A blockquote or quote is a sentence or paragraph formatted to let the reader know that you're quoting someone. To create a blockquote in Markdown, you can use the > symbol.

> Text that is a quote
Create block quote or quote in markdown
Code
Markdown files support two types of code samples: inline and code block.

To add a code block in a Markdown file, use the following syntax: ``` your code ```.
To add inline code to the Markdown file, use the following syntax: `your code`.
## Code Block

```
// ES5 syntax
var multiply = function(x, y) {
  return x * y;
};

// ES6 arrow function
var multiply = (x, y) => { return x * y; };

// Or even simpler
var multiply = (x, y) => x * y;
```

## Inline code 

JavaScript provides three different value comparison operations: strict equality using `===`, loose equality using `==`, and the `Object.is()` method.


Create a code block example.
To support code highlighting in a code block, you can add an optional language identifier after your triple backticks (like JavaScript in the example below):

## Code Block

```javascript

// ES5 syntax
var multiply = function(x, y) {
  return x * y;
};

// ES6 arrow function
var multiply = (x, y) => { return x * y; };

// Or even simpler
var multiply = (x, y) => x * y;   

```
Create a code block with a syntax highlighting example.
Links
A markdown file divides links into two categories: inline and relative.

Inline links
To create an inline link in a Markdown file, wrap the link text in brackets [ ] followed immediately by the URL in parentheses ( ).

This site was built using [GitHub Pages](https://pages.github.com/).

Relative links
Relative links are defined similarly to inline links but they change in the [] section: the [] section contains the path of the file in your repository.

You use relative links to link two files: for example, to link the CONTRIBUTING file into the README file.

[Contribution guidelines](docs/CONTRIBUTING.md)
Relative links starting with / will be relative to the repository root. You can use all relative link operands, such as ./ and ../.:

[Contribution guidelines](../docs/CONTRIBUTING.md)
Images
To add an image in a markdown file, add a ! and then wrap the alt text in []. Then, wrap the image link with parentheses ().

It looks like this:

![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
Lists
A list helps record essential information in order, which can be vital for the reader and makes it easy for people to understand and find information.

Markdown files support three types of lists:

Ordered list
Unordered list
Task list
Ordered list
The first type is an ordered list. To create an ordered list, start with numbers followed by periods.

1. one
2. two
3. three
4. four
Create an ordered list
Unordered list
The second type is an unordered list. To create an unordered list, use -, + or * (depending on your preference - they'll all render as an unordered list):

* First item
* Second item
* Third item
* Fourth item


- First item
- Second item
- Third item
- Fourth item

+ First item
+ Second item
+ Third item
+ Fourth item
Create an unordered list
Task list
The third type is a task list. To create a task list, list items start with a hyphen, followed by a space, followed by square brackets []. You can use an x in the bracket [x] to mark a task as complete.

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
